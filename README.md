#jQuery Plugin Skeleton
##What?
Simple, it's just a skeleton of a jQuery plugin that you can download, clone, fork, whatever. I'm putting it on Github mainly for myself. It also includes an MIT license at the top of the skeleton.

##How?
Only thing you really have to do is edit the MIT license on the first line:

    Copyright (c) <Year> <First & Last Name>, <Your Web Site>

And then name your plugin by replacing "`pluginname`" here:

    pluginname: function(options) {

Lastly, you basically just start writing you plugin right under this line:

    $this = $(this);

Make sure to use `$this` to reference the element selected from the plugin. Example, `$this` in this case:

    $('#myelement').pluginname();

Would equal `#myelement`, or for multiple items selected, the current item the plugin is on while looping through.

##Note!
This plugin allows you to keep on chaining, so, for example:

    $('#myelement').pluginname().css({border:'1px solid blue'});

Would run `pluginname` name on `#myelement` then add a blue border to it after.

##Whats next?

A skeleton that includes ready-to-go functions and callbacks for AJAX based plugins.

##Found a bug? 

Submit a bug report above or here: 

<https://github.com/OscarGodson/jQuery-Plugin-Skeleton/issues>
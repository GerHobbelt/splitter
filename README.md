# jQuery Splitter

This is a fork of the forked copy from from http://methvin.com/splitter/

The original fork is at https://github.com/e1ven/jQuery-Splitter

The original forked copy restored jQuery 1.7 compatibility. But jQuery
1.9 removed `$.browser` therfore breaking the plugin.

This fork uses other means of browser detection to be compatible with
jQuery 1.9 and 1.10.

Apart from that, a few indentation changes and minor cleanup were
performed to make jslint a bit more happy.

I do not recommend to use this plugin for new projects. But legacy
projects, that already use jquery.splitter and want to update their
jQuery version may give it a shot. I have no intend of maintaining this 
plugin. I mangeld it enough to fit my specific use case. Therefore I
really can't recommend basing any new project on this version of the
plugin.

I am also not aware of any good alternatives to this plugin. If possible, 
try to avoid layouts, that use splitting panes in the
first place. They are not that great UX wise to begin with...

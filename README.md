# my-custom-bis-cordova-plugin

Add BIS info to iOS plist file.

This is a single file Cordova plugin meant to be used to add
some keys to the iOS plist file. Only one file is required in
the plugin, it is named `plugin.xml`. 

Clone this plugin repo and update the `[ Key Value ]` part 
of the plugin to fit your BIS encryption compliance code. 
Then add the plugin using the Intel XDK plugin management 
tool on the Projects tab as a git repo plugin. 

Additional info regarding this can be found here > 
https://software.intel.com/en-us/xdk/faqs/general#android-manifest

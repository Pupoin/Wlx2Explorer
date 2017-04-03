Wlx2Explorer
=============

Wlx2Explorer is an application which allows to use Total Commander lister plugins from Windows Explorer.
You open Windows Explorer, select the necessary file and press the hot keys, then you can use the plugin.

Requirements
------------------

* OS Windows XP SP3 and later.
* .NET Framework 4.0

Files
------------------

* Wlx2Explorer.exe - The main executable module.
* Wlx2Explorer.xml - The application settings file.
* Wlx2Explorer.ini - The plugins settings file.

How does it work?
--------------------

* When the application starts, it loads all plugins in the RAM.
* Then it runs the local keyboard hook WH_KEYBOARD_LL.
* When the user presses hot keys, the application detects the selected file in Windows Explorer, matches the file and the plugin, shows the plugin on the screen.
* The user can add any number of plugins through dialogue "Settings...".
* If the application has been configured to use several plugins for one type of the file, the user will see the first one from the list of plugins.
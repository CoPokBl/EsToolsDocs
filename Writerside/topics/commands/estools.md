# /estools

**Minimum Version: None**
```
/estools [reload/reset/test/throw/update/forceupdate]
```

## /estools
**(N) Permission:** `estools.version`  
The command displays the current version of the plugin.

## /estools reload
**(O) Permission:** `estools.reload`  
Running `/estools reload` with reload all plugin config files.

## /estools reset
**(O) Permission:** `estools.reset`  
This command resets all plugin config files. 
Requires confirmation by running `/estools reset confirm`

## /estools test
**(O) Permission:** `estools.test`  
This command will perform a test of all the plugin's commands. 
This command is intended for developers only.
To begin the test type the command. The plugin will automatically execute commands
while you verify that they worked. Sometimes it will prompt you to test a feature
and then rerun `/estools test` to verify that you tested it, it will then move on.
If an error occurs during the execution of a command, you will be notified and a stacktrace
will be printed.

## /estools update
**(O) Permission:** `estools.update`  
This command will download the update ready to be downloaded if one exists.
To check if an update is ready to download, type /estools. It will display
extra text saying that EsTools is out of date if there is an available update.
To force an update to the latest release, type `/estools forceupdate`.

## /estools forceupdate
**(O) Permission:** `estools.forceupdate`  
This command will download the latest available release of EsTools from GitHub.
The new version will be downloaded regardless of whether it is newer than the current
version. There is no way to restore the previous version after an update.
**THIS MAY DOWNGRADE THE PLUGIN**

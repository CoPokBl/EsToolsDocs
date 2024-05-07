# EsTools
A general purpose Essentials like plugin with everything you need but not messing up anything (MC 1.0+)

EsTools is a plugin designed to be like EssentialsX in that it provides heaps of
helpful commands, but unlike essentials it doesn't mess up or override vanilla features (e.g. the give command).
This plugin doesn't override existing Minecraft commands and therefore is less likely to mess stuff up.
EsTools is also completely `/reload` safe.

## These Docs
All the command permissions will look like this:  
**(O) Permission:** `estools.command`  
Where in the brackets it tells you whether the permission is granted by default.
If it is it will display (N) for not op, otherwise it will display (O) for op.

In usages, you will notice the use of square brackets and triangle brackets like so:
```
/command <arg1> [arg2] [arg3]
```
An argument in triangle brackets is required and must be provided, whereas an argument
in square brackets is optional.

Every command also specifies a minimum Minecraft version like this:  
**Minimum Version: 1.3**  
The command will display a disabled message if you attempt to run it on a version of Minecraft that
is lower than the one specified.
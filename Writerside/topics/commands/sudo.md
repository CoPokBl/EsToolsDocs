# /sudo

**Minimum Version: NONE**  
**(O) Permission:** `estools.sudo`  
```
/sudo <player> <command>
```

Forces the specified player to execute the specified command.
The command will be executed as though the specified player executed it,
this means that the specified player will be sent all messages related to the command
and will suffer all the effects inflicted by the command.
The specified player *will not* be notified that they have been sudoed.

### Examples 
`/sudo CoPokBl suicide`  
This command will kill cause CoPokBl to be killed. CoPokBl will see a message in chat 
saying 'Rest in peace.' because that's the output of the /suicide command.

`/sudo Calcilore msg CoPokBl hello there`  
This command will cause CoPokBl to receive a message from Calcilore saying 'hello there'.

`/sudo Calcilore ban CoPokBl`  
Assuming Calcilore does not have any permissions, Calcilore will receive a message
stating that they do not have permission to execute the command.

**THIS COMMAND IS VERY POWERFUL, BE CAREFUL WHO CAN USE IT**  
Anyone who has access to this command can sudo people will more permissions than them to
grant themselves more permissions. This command should only be granted to people whom you
wish to have full access to the server.

# Commands

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

## Example Command

**Minimum Version: 1.9+**  
**(N) Permission:** `estools.music`
```
/music [song]
```
**Player only command**

Plays the selected music disc on the client of the player who executed the command.
Song should be the name of a Minecraft music disc, these will tab complete.

## Explanation
In the above example, we are talking about the [/music](music.md) command. On the actual [/music](music.md) page
the heading will be "/music".

**Minimum Version: 1.9+**  
We see that the command only supports version above 1.8 (1.9 and above).

**(N) Permission:** `estools.music`  
We can see that the command is usable by everyone by default (`(N)`) and has the permission node
`estools.music`.

```
/music [song]
```
We can see that the command takes one optional argument. If you choose to specify a song it will play
that song.

**Player only command**  
We see that the command can only be used by player, meaning it cannot be used by the console.

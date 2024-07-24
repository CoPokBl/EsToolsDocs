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

# Command List

| Command | Minimum Version | Permission                                         | Default                  |
|---------|-----------------|----------------------------------------------------|--------------------------|
| /gms    | NONE            | estools.gamemode.survival                          | OP                       |
| /gmc | NONE            | estools.gamemode.creative                          | OP                       |
| /gma | 1.3             | estools.gamemode.adventure                         | OP                       |
| /gmsp | 1.8             | estools.gamemode.spectator                         | OP                       |
| /tphere | NONE            | estools.gamemode.tp                                | OP                       |
| /tpall | NONE            | estools.gamemode.tp                                | OP                       |
| /feed | NONE            | estools.feed                                       | OP                       |
| /fly | 1.2             | estools.fly                                        | OP                       |
| /smite | NONE            | estools.smite                                      | OP                       |
| /invsee | 1.2             | estools.invsee                                     | OP                       |
| /i | NONE            | estools.give                                       | OP                       |
| /h | NONE            | estools.give                                       | OP                       |
| /estools | NONE            | estools.version                                    | NOT OP                   |
| /estools reload | NONE            | estools.reload                                     | OP                       |
| /estools reset | NONE            | estools.reset                                      | OP                       |
| /estools test | NONE            | estools.test                                       | OP                       |
| /estools throw | NONE            | estools.throw                                      | OP                       |
| /estools update | NONE            | estools.update                                     | OP                       |
| /estools forceupdate | NONE            | estools.forceupdate                                | OP                       |
| /ench | NONE            | estools.ench                                       | OP                       |
| /fix | NONE            | estools.fix                                        | OP                       |
| /cchest | 1.7             | estools.cchest.creative OR estools.cchest.survival | NOT OP (OP for survival) |
| /back | 1.1             | estools.back | OP |
| /setstack | NONE            | estools.setstack | OP |
| /ci | NONE            | estools.clearinv | OP |
| /day | NONE            | estools.time | OP |
| /night | NONE            | estools.time | OP |
| /noon | NONE            | estools.time | OP |
| /midnight | NONE            | estools.time | OP |
| /sun | NONE            | estools.weather | OP |
| /rain | NONE            | estools.weather | OP |
| /thunder | NONE            | estools.weather | OP |
| /walkspeed | 1.4             | estools.walkspeed | OP |
| /flyspeed | 1.3 | estools.flyspeed | OP |
| /setunbreakable | 1.1 | estools.setunbreakable | OP |
| /hideflags | 1.8 | estools.hideflags | OP |
| /eff | 1.1 | estools.effect | OP |
| /safetp | 1.1 | estools.safetp | OP |
| /infinite | 1.1 | estools.infinite | OP |
| /sethunger | NONE | estools.sethunger | OP |
| /setsaturation | NONE | estools.setsaturation | OP |
| /powerpick | 1.1 | estools.powerpick | OP |
| /poweraxe | 1.1 | estools.powerpick | OP |
| /powersword | 1.1 | estools.powerpick | OP |
| /powershovel | 1.1 | estools.powerpick | OP |
| /powerhoe | 1.1 | estools.powerpick | OP |
| /lore | 1.4.6 | estools.lore | OP |
| /rename | 1.4.6 | estools.rename | OP |
| /sudo | NONE | estools.sudo | OP |
| /heal | NONE | estools.heal | OP |
| /suicide | NONE | estools.suicide | NOT OP |
| /sethealth | NONE | estools.sethealth | OP |
| /setmaxhealth | 1.4 | estools.setmaxhealth | OP |
| /getinfo | NONE | estools.getinfo | OP |
| /editsign | NONE | estools.editsign | OP |
| /god | 1.1 | estools.god | OP |
| /buddha | 1.1 | estools.god | OP |
| /music | 1.9 | estools.music | NOT OP |
| /potion | NONE | estools.potion | OP |
| /bukkitdata | 1.14 | estools.bukkitdata | OP |
| /warp | NONE | estools.warps.use | OP |
| /warps | NONE | estools.warps.manage | OP |
| /mount | NONE | estools.mount | OP |
| /dismount | NONE | estools.mount | OP |

# /mount

**Minimum Version: NONE**  
**(O) Permission:** `estools.mount`
```
/mount <ridee> [rider1] [rider2]...
```

Makes the specified riders (separated by spaces) mount the specified
ridee in a stack such that if you ran `/mount player1 player2 player3`
`player3` would be riding `player2` who would be riding `player1`.
All the arguments can be entity UUIDs. If no riders are specified
then it defaults to just the executor. Console must specify at
least one rider.

In pre Minecraft 1.2 all specified entities must

# /warps

**Minimum Version: NONE**  
**(O) Permission:** `estools.warps.manage`

## /warps <add/set>
```
/warps <add/set> <warpname> [LOCAL/global] [x] [y] [z] [yaw] [pitch]
```
**Player only command**

Creates or sets (overrides if it already exists) a warp location.
`warpname` cannot contain spaces. Local/Global defaults to `local`.
A local warp is meant to only be used from the same world whereas
global warps can be used from any world.

If you specify either x, y or z you must specify all 3, you cannot
just specify one.

## /warps list
```
/warps list
```
**Player only command**

Sends the list of all created warps in the server.

## /warps remove
```
/warps remove <warpname>
```
Removes the specified warp. The warp will no longer be able to be
used.

See [/warp](warp.md) for information on using warps.

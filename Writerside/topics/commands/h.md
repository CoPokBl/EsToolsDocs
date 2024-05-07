# /h

**Minimum Version: NONE**  
**(O) Permission:** `estools.give`
```
/h <item> [amount]
```
**Item: The name of the item**  
**Amount (Default 1): The integer amount of the item to give**

Replaces your currently held item with the specified amount of the specified item.
The amount specified is for one stack, so make sure the amount is within Minecraft's limits.
If the amount is more than 127 then the item will become invisible, at least on most modern versions.
You can add custom aliases for item names by changing the `give.yml` configuration file.
By default, there are some aliases such as `water` for `water_bucket`.
Also by default each name is aliased by its name with the underscores removed,
for example `water_bucket` can be referenced with `waterbucket`.
All item based command behaviour can be modified with the `give.yml` configuration file.

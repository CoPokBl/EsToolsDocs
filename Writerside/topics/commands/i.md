# /i

**Minimum Version: NONE**  
**(O) Permission:** `estools.give`
```
/i <item> [amount]
```
**Item: The name of the item**  
**Amount (Default 1): The integer amount of the item to give**

Adds the specified amount of the specified item to your inventory.
You can add custom aliases for item names by changing the `give.yml` configuration file.
By default, there are some aliases such as `water` for `water_bucket`.
Also by default each name is aliased by its name with the underscores removed,
for example `water_bucket` can be referenced with `waterbucket`.
All item based command behaviour can be modified with the `give.yml` configuration file.

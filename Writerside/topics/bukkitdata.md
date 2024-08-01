# /bukkitdata

**Minimum Version: 1.14**  
**(O) Permission:** `estools.bukkitdata`

## /bukkitdata <get/remove>
```
/bukkitdata <get/remove> <key>
```
**Player only command**

Gets or Removes a Bukkit persistent data value from the executor's held
item. The key MUST be the name of the plugin that set the data COLON
the key specified by the plugin, like this: `pluingname:mykey`.

## /bukkitdata set
```
/bukkitdata set <key> <type> <value> 
```
**Player only command**

Creates or overrides a Bukkit persistent data value from the executor's held
item. The key MUST be the name of the plugin that set the data COLON
the key specified by the plugin, like this: `pluingname:mykey`.

Type must be the data type of the value,
see below for a list of valid types, also note that this field
tab completes the full list of valid types. Finally, value
is what the key should be set to, it must be the type
that was specified in `<type>`, for example if you specify
`integer` then the value must be a whole number.

### Data Types
- string
- integer
- double
- float
- long
- short
- byte
- byte_array (Values separated with space)
- int_array (Values separated with space)
- long_array (Values separated with space)

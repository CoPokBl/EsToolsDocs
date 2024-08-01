# /getpersistentdata [removed]

**This command was removed in EsTools Version 5.1**

**Minimum Version: 1.14**  
**(O) Permission:** `estools.getpersistentdata`
```
/getpersistentdata <key> <type>
```
**Player only command**

Gets a Bukkit persistent data value of the executor's held item.
The key MUST be the name of the plugin that set the data COLON
the key specified by the plugin, like this: `pluingname:mykey`.
The type must be the same type that the value was set with,
type will tab complete all possible values, see below for that
list.

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

# /setpersistentdata

**Minimum Version: 1.14**  
**(O) Permission:** `estools.setpersistentdata`
```
/setpersistentdata <key> <type> <value>
```
**Player only command**

Sets a Bukkit persistent data value of the executor's held item.
The key is the key that is used to create a namespaced key, so
the final key will be `pluginname:key` where pluginname is the
name of your plugin as it appears in `plugin.yml` and key
is the specified key. Type must be the data type of the value,
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

# /safetp

**Minimum Version: 1.1**  
**(O) Permission:** `estools.safetp`  
```
/safetp
```

Globally toggles SafeTP for the entire server. **IT IS NOT PER PLAYER**.

When SafeTP is enabled then when players are teleported their fall distance will be set to 0.
This means that if they teleport to the ground after they have been falling for long enough to
take damage, they won't take damage and will land safely. The state of SafeTP will persist between
server restarts. Optionally SafeTP can be toggled from `config.yml` in the plugin's folder.
Modify `safetp: true` and change the value to either `true` or `false` to indicate enabled
or disabled respectively.

### Fall distance is *cancelled* on the following teleport event types:  
- Commands (Like /tp)
- Plugins (Any plugin that causes teleportation, including EsTools commands like /back)
- Unknown event type (Events that Spigot fails to identify)

### Fall distance is *not cancelled* on the following teleport event types:  
- Chorus fruit
- Vehicle dismount (Leaving a boat of horse)
- End gateways
- End portal
- Ender pearl
- Exit bed
- Nether portal
- Spectator teleport (When someone in spectator mode uses their menu to teleport to someone)

# ucp_startResources
UCP3 module for starting resources

## Customizations

Troops and goods use one row per unit or resource, with Normal, Crusader and
Deathmatch columns. Starting gold uses one row per advantage level, with Human
and AI columns. All existing configuration keys, defaults and limits are preserved.

The compact layout uses the frontend's reusable `Group.table` presentation.
Older frontends display the same controls in ordinary groups. This UI update
does not change the module's Lua code.

## Documentation


Linking To API & Http (Found In ReplicatedScriptService "KeyHandler")
```lua
local KeyHandler = {
	APIKey = "ApiKey",
	WebHookHttp = "WebHook"
}
return KeyHandler
```

Enabling/Disabling Mod Type's (Found In ReplicatedScriptService "ModTypes")
```lua
local ModTypes = {
	Textures = true,
	Models = true,
	Audio = true,
	Decals = true
}
return ModTypes
```

Adding Staff/Admins To View Mods (Found In ReplicatedScriptService "StaffAdmin")
```lua
local StaffAdmin = {"PlayerName","PlayerName","PlayerName"}

return StaffAdmin
```

Whitelist Certain Players To Make Mods (Found In ReplicatedScriptService "ModMakingPerms")
```lua
local ModMakingPerms = {
	NeedPermsToMakeMods = false,
	Perms = {"PlayerName","PlayerName","PlayerName"}
}
return ModMakingPerms
```



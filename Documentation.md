<link rel="icon" type="image/png" href="https://i.ibb.co/RcDh0nB/50eacb430487b072ab653a5ead7bdd8c.png" />

## Documentation


Linking To API & Http (Found In ReplicatedScriptService "KeyHandler")
```lua
local KeyHandler = {
	PasteBinKey = "ApiKey",
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



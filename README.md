# KryptonAnimations
Animation ID Player For Roblox ( A stupid one, but works. )

![image](https://github.com/user-attachments/assets/072a5b41-930b-48bd-ae80-51aa4bc940b7)

# Module
```luau
KryptonConfiguration = {
	DestroyHeightOffset = 5, -- Make it higher if your hats fall
	DontStartYet = true,
	ReturnOnDeath = true,
	Refit = true,
	SetCharacter = false,
	Animations = true,
	NoCollisions = true,
	AntiVoiding = false,
	SetSimulationRadius = true,
	DisableCharacterScripts = true,
	AccessoryFallbackDefaults = true,
	OverlayFakeCharacter = false,
	LimitHatsPerLimb = false,
	NoBodyNearby = true,
	PermanentDeath = true,
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/KadeTheExploiter/KryptonAnimations/refs/heads/main/Module.luau"))()
```

# Features
- Runs on official Krypton Reanimate module, so you will be up to date all time.
- Supports Audios
- Supports a lot of rigs
- 20+ Animations (Will add more later on).
- Supports Permanent Death

# Requirements
- Be able to use `InsertService:LoadLocalAsset` (Requires higher priviliges)
- Proper Loadstring
- For Audios: `getcustomasset, writefile, isfile, makefolder`
- For Permanent Death:  `replicatesignal`

# Misc
- Official Discord Server: https://discord.gg/ArpG4kDvW2
- IF anything, open an issue on github for suggestions/bug reports

# Credits
- [Geletek/KadeTheScripter:](https://github.com/KadeTheExploiter) Lead Developer, Krypton Reanimate
- [Kinlei:](https://github.com/Kinlei) Material Lua UI Library

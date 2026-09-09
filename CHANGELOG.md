# v0.8.0
- Updated for Valheim 1.0 (Unity 6)
- Rebuilt against the live 1.0 client (Unity 6000.0.75f1)
- Piece health now reads `ZDOVars.s_health` instead of the string ZDO key
- Call `WearNTear.GetSupport` / `GetMaxSupport` via Harmony Traverse (those methods are still private)
- Harmony patch targets `Hud.UpdateCrosshair(Player, float)` by name; extra HUD children are null-checked
- Build against the game's Managed Unity assemblies (Unity 6 dropped `unstripped_corlib` / `TextCoreModule`)
- BepInEx dependency updated to denikson-BepInExPack_Valheim-5.4.2350
- Piece highlight / custom integrity colours remain disabled (same as 0.7.1)

# v0.7.1
- Commented out piece highlighting until a fix can be provided. Health bar and text still work.

# v0.7.0
- Removed terminal reload
- Added compatibility for v0.217.46

# 0.6.2
- Fixed potential issue with missing assembly file

# 0.6.1
- Changed config file name to cjayride.BuildingHealthDisplay.cfg

# 0.6.0
- 2 changes (commits) by "Aedenthorn" on Aug 24, 2023 and Oct 6, 2023

# 0.4.1
- Verified works on Mistlands update
- Changed config file name to cjayride.BuildingHealthDisplay.cfg
- Changed default value of ShowIntegrityText = false

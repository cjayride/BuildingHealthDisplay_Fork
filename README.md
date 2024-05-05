# BuildingHealthDisplay

Patched for Valheim v0.217.46+

A fork of [aedenthorn/BuildingHealthDisplay](https://github.com/aedenthorn/ValheimMods/tree/master/BuildingHealthDisplay) 

[ThunderStore](https://thunderstore.io/c/valheim/p/cjayride/BuildingHealthDisplay) | [GitHub](https://github.com/cjayride/BuildingHealthDisplay_Fork)

## Display HP of buildings

This is a small quality-of-life mod that lets you tweak the little bar that shows how much health a building piece has.  

-   Lets you optionally set colours for low, mid, and high remaining health, with smooth blending from one colour to another (default  **red, yellow, and green**)
-   Lets you optionally hide the health bar.
-   Lets you optionally show custom health text with the health bar (default shows  **current / max (percent)**)
-   Lets you optionally show piece structural integrity (default shows  **current / max (percent)**)
-   Lets you optionally set colours for low, mid, and high piece integrity, with smooth blending from one colour to another (default  **red, yellow, and green**)

The health and integrity texts are in the format **{0}/{1} ({2})** just as an example to show all three showable values. You can customize this as you like. **{0}** is replaced by current value. **{1}** is replaced by max value. **{2}** is replaced by percentage value. 

## Configuration

A config file **BepInEx/config/cjayride.BuildingHealthDisplay.cfg** is created after running the game once with this mod. 

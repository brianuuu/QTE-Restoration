---------------------------Sonic Generations Mod---------------------------
----------------------------QTE Restoration v1.1---------------------------

This is a mod that restores QTE from Sonic Unleashed, ReactionPlate and TrickJump objects!
This mod can also modify Generations' AdlibTrickJump object to behave like TrickJumper from Unleashed.

------------------------------------------------------------
Mod Usage
------------------------------------------------------------
This is NOT intended as a standalone mod and does NOT modify stages in any way, user must add ReactionPlate and TrickJumper objects to their own mod. This mod is setup as standalone so user can get updates from update server. The objects will have to same parameters as Sonic Unleashed, follow the object parameters there.

It is recommended to use HedgeModManager's dependency system to include this mod if you wish to use this in your own mod. You can do that by Edit Mod on your mod, add "brianuuu.qterestoration" ID to dependencies, then put this page's link to Link section for people can download this accordingly.

You can also enable "Replace Generations Trick Jump as QTE" in configuration, this will replace Generations' trick jump to behave like Unleashed. There are also additional parameters to manually number of buttons/input time etc., please refer to: https://github.com/brianuuu/DllMods/blob/master/Source/QTERestoration/QTEJumpBoard.h

Secret feature: It is also possible to add button spam sequence to TrickJumper, by setting TrickCount as XYY (X = button type, Y = spam count) and TrickTime to a negative number!

Character Mod Compatibility: This mod is automatically compatible with Unleashed Sonic model mods. But for other character mods, QTE animations may not work correctly, you must include SonicTrick.ar.00 in your mod and put the character mod higher priority than QTE Restoration. (Note: You do not have to include "_swa" animations as they will be unused.)

This mod works ONLY with HedgeModManager, SonicGMI is NOT supported!

------------------------------------------------------------
Known Issues
------------------------------------------------------------
-In certain 2D sections, Sonic may slow down excessively and not reach the intended location if you fail a QTE, this does not happen in locked 30fps.

------------------------------------------------------------
Change Log
------------------------------------------------------------
v1.1
-Fixed Gen QTE going backwards sometimes
-Fixed Shadow actvating QTE in his fight
-Fixed quitting stage during QTE will prevent any QTE from working again

v1.0
-Initial release

------------------------------------------------------------
Credits
------------------------------------------------------------
brianuuu - Main Developer
Skyth - Original Developer for ReactionPlate
K1 A1 - Stage testing
Hedgeturd - Redirected animations for Generations Sonic
UltimateDarkman - Custom animations for Unleashed Super Sonic

[Combat Extended] Patch operation Verse.PatchOperationFindMod(Vanilla Factions Expanded - Empire) failed
file: D:\SteamLibrary\steamapps\workshop\content\294100\2890901044\Patches\Vanilla Factions Expanded - Empire\Buildings_Security_Turrets.xml 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

<color=orange>[OskarObnoxious]</color> version 1.4.0
[Vanilla Furniture Expanded - Architect] Activating Replace Stuff compatibility patch
[RimHUD v1.11.3] Initialized
startIndex: 28
endIndex: 36
Start: newobj System.Void System.Text.StringBuilder::.ctor()
End:callvirt virtual System.String System.Object::ToString()
Start: stloc.1 NULL
End:br.s Label4
Could not load UnityEngine.Texture2D at UI/commands/GR_Orbital in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_SetTrap in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_MechaBlast in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_PoisonousCloud in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_AdrenalineBurst in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_CatReflexes in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_Insectclouds in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_StampedeClouds in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_KeenSenses in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_PackTactics in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_Microscope in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_Pounce in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/commands/GR_StraightCharge in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

PickUpAndHaul v0.1.3.2⅔ welcomes you to RimWorld with pointless logspam.
Could not load UnityEngine.Texture2D at UI/GeneticsUI_Hexagon in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/GeneticsUI_Arrow in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load UnityEngine.Texture2D at UI/GeneticsUI_ArrowTwoWays in any active mod or in base resources. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

CE successfully patched 2 animals.
Animal Defs autopatched:AG_OcularSlinger
VRE_CompanionDryad

MVCF successfully applied 47 patches
[net.pardeike.rimworld.mods.achtung] Patches on methods annotated as Obsolete were detected by HugsLib: Verse.Game.DeinitAndRemoveMap 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

[UnlimitedHugs.HugsLib] Patches on methods annotated as Obsolete were detected by HugsLib: Verse.Game.DeinitAndRemoveMap 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

[OskarPotocki.VanillaPsycastsExpanded] Patches on methods annotated as Obsolete were detected by HugsLib: Verse.MapDeiniter.Deinit 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

OnLevelWasLoaded was found on ModInitializerComponent
This message has been deprecated and will be removed in a later version of Unity.
Add a delegate to SceneManager.sceneLoaded instead to get notifications after scene loading has completed 
(Filename:  Line: 369)

[AllowTool] Applied compatibility patch for "Pick Up And Haul"
Combat Extended :: Ammo injected
Exception from long event: System.Exception: GR_FleshFlies.lifeStages[0].bodyGraphicData ---> System.Exception: BoundMap(,) ---> System.Exception: Combat Extended :: CropVertical error while cropping Textures/Things/Pawn/Animal/Special/GR_Transparent_side ---> System.ArgumentException: Color[] has no pixels with alpha < 0.25
  at CombatExtended.Def_Extensions.CropVertical (UnityEngine.Color[] array, System.Int32 width, System.Int32 height) [0x00051] in <93dab220b0264f549bddfd62638b4605>:0 
  at CombatExtended.BoundsInjector.ExtractBounds (Verse.Graphic graphic, CombatExtended.BoundsInjector+GraphicType type) [0x0001b] in <93dab220b0264f549bddfd62638b4605>:0 
   --- End of inner exception stack trace ---
  at CombatExtended.BoundsInjector.ExtractBounds (Verse.Graphic graphic, CombatExtended.BoundsInjector+GraphicType type) [0x00045] in <93dab220b0264f549bddfd62638b4605>:0 
  at CombatExtended.BoundsInjector.BoundMap (Verse.Graphic graphic, CombatExtended.BoundsInjector+GraphicType type) [0x0001e] in <93dab220b0264f549bddfd62638b4605>:0 
   --- End of inner exception stack trace ---
  at CombatExtended.BoundsInjector.BoundMap (Verse.Graphic graphic, CombatExtended.BoundsInjector+GraphicType type) [0x0004b] in <93dab220b0264f549bddfd62638b4605>:0 
  at CombatExtended.BoundsInjector.Inject () [0x00083] in <93dab220b0264f549bddfd62638b4605>:0 
   --- End of inner exception stack trace ---
  at CombatExtended.BoundsInjector.Inject () [0x000bb] in <93dab220b0264f549bddfd62638b4605>:0 
  at Verse.LongEventHandler.UpdateCurrentSynchronousEvent (System.Boolean& sceneChanged) [0x0001d] in <38562b1a2ab64eacb931fb5df05ca994>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Combat Extended :: Checking Vehicle Framework
Combat Extended :: Checking Better Turrets
Combat Extended :: Checking Misc Turrets

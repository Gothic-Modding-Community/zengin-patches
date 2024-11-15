# ZenGin Patches
Repository with various patches for ZenGin, a game engine used in Gothic 1 and 2. Patches are provided in a `.patch` format and can be applied to the original source code by placing in the `<gothic-root>/system` directory with Union installed.

> [!CAUTION]
> The patches are provided as-is and may not work or be broken. Make sure to test the patches before using them in your modification.

## Patches
| Patch | Engine | Author | Description |
| --- | --- | --- | --- |
| [AniRunTransitionFix](patches/AniRunTransitionFix.patch) | G1, G2A | Patrix, Fawkes | Correct transition between run animations with weapon drawn |
| [zModelProtoIndexGuardFix](patches/zModelProtoIndexGuardFix.patch) | G2A | TopLayer | Fixes the engine index guard check |
| [zFootPosFix](patches/zFootPosFix.patch) | G1, G1A, G2, G2A | TopLayer | Fixes foot position calculation for NPCs |
| [MinDialogTime](patches/MinDialogTime.patch) | G2A | Gratt | Allows to set a minimum time for dialogues |
| [Disable_Textures_Check](patches/Disable_Textures_Check.patch) | G2A | Unknown | Disables `zCModelTexAniState::FinishTexList` 4 texture per `.asc` file limit |
| [AI_Output_Fix](patches/AI_Output_Fix.patch) | G2A | Boguś | Fixes not appearing dialog box in specific case |

## Contributing
If you have a patch you would like to submit, please create a pull request with the patch file in the `patches` directory. Make sure to include a description of the patch and the bug it fixes.

## Other Resources
Gothic patches can be also found in the following repositories:

- [UnresolvedExternal/Gothic-Patches](https://github.com/UnresolvedExternal/Gothic-Patches)
- [VaanaCZ/gothic-engine-patches](https://github.com/VaanaCZ/gothic-engine-patches)

## Credits
Special thanks to [Fawkes](https://github.com/Fawkes-dev) for the idea of creating a repository for ZenGin patches.
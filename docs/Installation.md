![](assets/InstallationGuide.png) 

# Installation

This is a complete installation guide on how to install the Promised Worlds mod for Kerbal Space Program.

## System Requirements

| List | Minimum | Recommended |
|----------|----------|----------|
| KSP Version | 1.12.x | 1.12.5 |
| RAM | 16GB | 32GB |
| GPU | 2GB VRAM | 8GB VRAM |
| Storage | 5GB Free Space | 5GB Free Space (SSD) |
| Platforms | Windows/Linux/MacOS* | Windows/Linux/MacOS* |

### Installation on Linux / MacOS
Promised Worlds works on Linux and MacOS, however the ScaledDecorator particle effects (which form Debdeb's protoplanetary disk) do not currently work correctly with OpenGL. 
For Linux, it is recommended to run the Windows version of the game through Proton, which avoids this issue.
We are working on improving compatibility, so we can hopefully support all platforms equally in the future.

## CKAN

- Select "Promised Worlds - Debdeb" for the Debdeb system. CKAN will install the required dependencies.
- Select "Promised Worlds - Tuun" for the Tuun system. CKAN will install the required dependencies.

## SpaceDock 
(SpaceDock is no longer supported as it has caused numerous download issues for users and developers)
  
## Manual (GitHub)

- Download the latest version from [releases](https://github.com/PromisedWorlds/PromisedWorlds/releases). You will need the Core zip file, along with the zip file for any systems you want. You can install any of the systems you like - you don't have to take them all.
- Extract the Core zip file, and put the contents of GameData in your GameData directory.
- For each system you want:
    - Extract the system's zip file, and put the contents of its GameData in your GameData directory. It will add a directory within PromisedWorlds.
- Download the mod's dependencies: 
 - [Kopernicus](https://github.com/kopernicus/kopernicus/releases) (Read the Kopernicus install Guide, as Kopernicus requires its own dependencies)
 - [KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases) (Fixes most issues with interstellar travel.)
 - [Singularity](https://forum.kerbalspaceprogram.com/topic/193709-wip18x-112x-singularity-black-hole-shaders/) (Singularity is only required if you wish to use wormholes)

Other Dependencies are **ALREADY BUNDLED** with Promised Worlds, however, if the files do not correctly install, we've left these links here: 

 - [Duckweed Utils Oblate](https://github.com/jamespglaze/VertexHeightOblateAdvanced/releases) 
 - [Duckweed Utils Emissive](https://github.com/jamespglaze/VertexColorMapEmissive/releases)
 - [Niako's Utils](https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap/releases/tag/0.3)
 - [Kopernicus Expansion-er](https://github.com/VabienArt/KopernicusExpansion-Continueder/releases)
 - [ScaledDecorator](https://github.com/Sushutt/ScaledDecorator/releases)

- Extract these zip files and put all folders in KSP's GameData directory.
  
## Options
Settings can be changed either using the Promised Worlds toolbar icon (on the main menu), or by editing the PromisedWorldsSettings.cfg file (in GameData/PromisedWorlds).

| Option | Description |
|:--|:--|
| **Wormholes** | Enables wormholes *(requires Singularity for shaders)* |
| **RealisticStarSize** | Makes stars more realistically sized relative to the planets. |
| **RemoveStockScreens** | Removes stock loading screens and only shows PW's |
| **Skybox** | Requires DiRT or Sigma Replacements Skybox. Skybox will always be on with TextureReplacer - Set to True to enable the skybox. Set to False for the stock skybox or to use another skybox mod. |
| **DistanceFactor** | Controls how far from Kerbol the systems will be |
| **Rescale** | Resizes the systems *(requires [Sigma Dimensions](https://github.com/Sigma88/Sigma-Dimensions))* |

## Compatible Mods

| Mod Category | Compatibility | Mod | Details |
|----------|----------|----------|----------|
| Gameplay |✅| [Kerbalism](https://github.com/Kerbalism/Kerbalism/releases) | Adds Radiation Belts + More |
||✅| [Rational Resources](https://github.com/JadeOfMaar/RationalResources/releases) | Support Included |
||✅| [Space Dust](https://github.com/post-kerbin-mining-corporation/SpaceDust/releases) | Scoop/Gather Fuels |
| Visuals (Recommended) |✅| [True Volumetric Clouds Release 3 or Higher](https://www.patreon.com/posts/true-volumetric-139879553) | Adds Clouds, Aurora, Atmosphere Scatters |
||✅| [PlanetShine](https://github.com/PapaJoesSoup/ksp-planetshine/releases) | Planet ground/space Reflections |
||✅| [Distant Object Enhancement](https://github.com/net-lisias-ksp/DistantObject/releases) | Planetary Flares |
||✅| [Firefly](https://github.com/M1rageDev/Firefly/releases) | Adds Re-entry effects |
||✅| [Parallax Continued](https://github.com/Gameslinx/Parallax-Continued/releases) | Adds Detailed Terrain |
||✅| [Deferred](https://github.com/LGhassen/Deferred/releases) | Adds Deferred Rendering (Optional) |
| Planet Packs |✅| Outer Planets Mod | Compatibility Checked |
||✅| Minor Planets Expansion | Compatibility Checked |
||✅| Cosmic Serenity | Compatibility Checked |
||✅| Kcalbeloh | Compatibility Checked |
||✅| KSS 2 | Compatibility Checked |
||✅| Sol/RSS | Compatibility Checked (only in 10x Rescale) |
||✅| JNSQ | Compatibility Checked (only in 2.5x Rescale) |

## Outdated Mods/Incompatibility

| Compatibility | Mod | Reason/Conflict |
|----------|----------|----------|
|❌| Parallax V1/V2 | Unsupported/No Configs |
|❓| Principia (N-Body Sim) | No issues/Causes instability in orbits |
|❌| Free EVE Redux | Unsupported/No Configs |
|❓| TiltEm | Adds Axial Tilt - Current TiltEm causes issues but remains useable|
|❓| General/Old planet packs (KSP 1.11.X/prior) | Untested/May cause issues |

## Common fixes (Q/A)

Q: Clouds are not appearing on any Promised Worlds celestial body, what do I do?

A: Check to see if you have EVE Redux. Currently, Promised Worlds does not support EVE Redux/Free EVE, and only supports Blackrack's True Volumetric Clouds, Release 3 or higher. Release 3 is available at no cost. All releases can be found on [Blackrack's Patreon page](https://www.patreon.com/blackrack).

Q: Parallax is giving me errors when I start the game, what do I do?

A: This is due to an incorrect install or missing dependencies for either Promised Worlds or Parallax Continued. Check the install guide at the top of this page, and if the issue still persists, [report an issue](https://github.com/PromisedWorlds/PromisedWorlds/issues) on the repository or ask in the help channel on our Discord.

Q: None of the Promised Worlds bodies load when I go to map view, what is causing this?

A: This is due to missing dependencies for Kopernicus. Check if you have all the dependencies, listed on the [Kopernicus](https://github.com/Kopernicus/Kopernicus) page in the "README" section.

Q: Does Promised Worlds have lower graphics settings?

A: Promised Worlds supports graphics mods to provide better visuals. Those mods themselves include settings to reduce lag and improve performance for lower-end devices. At the top of this page, we have a recommended specs sheet to get the maximum performance out of Promised Worlds.
For True Volumetric Clouds, the temporal upscaling setting 

## Known issues with Promised Worlds:

- With Visual Enhancement Mods installed (Parallax/EVE), Celestial Body eclipses may become out of alignment with their parent object, or may cast a shadow on themselves in pure sunlight.
- Donk sometimes temporarily becomes red when exiting its Sphere of Influence.

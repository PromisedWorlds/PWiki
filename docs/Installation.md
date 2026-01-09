![](assets/InstallationGuide.png) 

# Installation

This is a complete installation guide on how to install Promised Worlds for Kerbal Space Program.

## System Requirements

| List | Minimum | Recommended |
|----------|----------|----------|
| KSP Version | 1.12.x | 1.12.5 |
| RAM | 16GB | 32GB |
| GPU | 2GB VRAM | 4GB VRAM |
| Storage | 5GB Free Space | 10GB Free Space |
| Platforms | Windows | Windows (Linux/MacOS have issues when testing) |

## CKAN

- Select "Promised Worlds - Debdeb" for the Debdeb system. CKAN will install the required dependencies.
- Select "Promised Worlds - Tuun" for the Tuun system. CKAN will install the required dependencies.

## SpaceDock 
(SpaceDock is no longer supported as it has caused numerous download issues upon users and developers)
  
## Manual (GitHub)

- Download the latest version from [releases](https://github.com/Constructalor/PromisedWorlds/releases). You will need the Core zip file, along with the zip file for any systems you want. You can install any of the systems you like - you don't have to take them all.
- Extract the Core zip file, and put the contents of GameData in your GameData directory.
- For each system you want:
    - Extract the system's zip file, and put the contents of its GameData in your GameData directory. It will add a directory within PromisedWorlds.
- Download the mod's dependencies: 
 - [Kopernicus](https://github.com/kopernicus/kopernicus/releases) (Read the Kopernicus install Guide, as Kopernicus requires it's own dependencies)
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
In the PromisedWorlds directory there is PromisedWorldsSettings.cfg with options for the mod:

- Skybox (Requires [Sigma Skybox Replacements](https://github.com/Sigma88/Sigma-Replacements/releases/tag/B_v0.5.1)) (Release 2.0.0 and above)
- Wormholes (Requires [Singularity](https://forum.kerbalspaceprogram.com/topic/193709-wip18x-112x-singularity-black-hole-shaders/) for shaders)
- DistanceFactor (How far from Kerbol the systems will be)
- Rescale (Resize the systems, requires [Sigma Dimensions](https://github.com/Sigma88/Sigma-Dimensions/releases))
- RealisticStarSize (Makes the stars more realistically sized relative to the planets)
- RemoveStockScreens (Removes Stock Loading Screens and only uses Promised Worlds Media as loading screens)

(Upon the release of 2.0.0, you can change these settings in-game with the icon that is in the top right corner of the main menu of KSP, labeled "PW", *requires restart upon changing settings*)

## Compatible Mods

| Mod Category | Compatibility | Mod | Details |
|----------|----------|----------|----------|
| Quality Of Life |✅| [Kerbalism](https://github.com/Kerbalism/Kerbalism/releases) | Adds Radiation Belts + More |
||✅| [Rational Resources](https://github.com/JadeOfMaar/RationalResources/releases) | Support Included |
||✅| [Space Dust](https://github.com/post-kerbin-mining-corporation/SpaceDust/releases) | Scoop/Gather Fuels |
| Visuals (Recommended) |✅| [Volumetrics V5](https://www.patreon.com/posts/true-volumetric-139879553) | Adds Clouds, Aurora, Atmosphere Scatters |
||✅| [PlanetShine](https://github.com/PapaJoesSoup/ksp-planetshine/releases) | Planet ground/space Reflections |
||✅| [Distant Object Enhancement](https://github.com/net-lisias-ksp/DistantObject/releases) | Planetary Flares |
||✅| [Firefly](https://github.com/M1rageDev/Firefly/releases) | Adds Re-entry effects |
||✅| [Parallax Continued](https://github.com/Gameslinx/Parallax-Continued/releases) | Adds Detailed Terrain |
||✅| [Deffered](https://github.com/LGhassen/Deferred/releases) | Adds Deffered Rendering (Optional) |
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
|❌| Volumetrics V4/V3 and prior | Unsupported/No Configs |
|❌| Free EVE | Unsupported/No Configs |
|❓| TiltEm | Adds Axial Tilt - Current TiltEm causes issues but remains useable|
|❓| General/Old planet packs (KSP 1.11.X/prior) | Untested/May cause issues |

## Known issues with Promised Worlds as of (1.2.1):

- With Visual Enhancement Mods installed (Parallax/EVE), Celestial Body eclipses may become out of alignment with their parent object, or may cast a shadow on themselves in pure sunlight.
- With Emissive mods installed, Donk will temporarily become red when Exiting it's Sphere of Influence.
---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
ZPE Propulsion (ZPEP)
created: 17 Jul 2023
updated: 

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->
## [ZPE Propulsion (ZPEP)][mod]

[Home](./index.md)

This is standalone expansion to my Rusty Star Rockets mod. It adds eleven (11) parts for new propulsion system: ZPE (Zero Point Energy) all with Rusty Star Shipyard aesthetics. It also adds new fuel resource: Quantum Fluctuations. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `ZPEPropulsion` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/RustyStar/ZPEPropulsion`
* Extract the package's `RustyStar/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/RustyStar` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/ZPEPropulsion`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/ZPEPropulsion`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/RustyStar/ZPEPropulsion`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [RustyStarShipyards]
      + [Agencies]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      ...
      + [ZPEPropulsion]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [FX]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        + [Sounds]
          ...
        + [Spaces]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-ND-4.0+ARR.txt
        * changelog.md
        * ManualInstallation.htm
        * readme.htm
        * ZPEPropulsion.version
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Rusty Star Shipyards (RSS)](https://www.curseforge.com/kerbal/ksp-mods/RustyStarShipyards)

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/ZPEPropulsion "ZPE Propulsion (ZPEP)"
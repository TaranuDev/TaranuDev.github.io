---
title: "Changes Tracker CTSM"
tags:
enableToc: false # do not show a table of contents on this page
---

## Here we track all modifications done to the land component CTSM/CLM in order to support sectoral water usage

The GitHub fork can be accessed [here](https://github.com/TaranuDev/CTSM)



## List of modifications:
### Namelist modifications
- [CTSM/bld/namelist_files/namelist_definition_ctsm.xml](CTSM/namelist_definition_ctsm.md)
- [CTSM/bld/namelist_files/namelist_defaults_ctsm_tools.xml](CTSM/namelist_defaults_ctsm_tools.md)
- [CTSM/bld/namelist_files/namelist_defaults_ctsm.xml](CTSM/namelist_defaults_ctsm.md)
- [CTSM/bld/CLMBuildNamelist.pm](CTSM/CLMBuildNamelist.md)

### Connect all forks using corresponding repositories and tags
- [Externals.cfg](CTSM/Externals.md)

### Changes to the main
- [CTSM/src/main/clm_driver.F90](CTSM/clm_driver.md)
- [CTSM/src/main/restFileMod.F90](CTSM/restFileMod.md)
- [CTSM/src/main/controlMod.F90](CTSM/controlMod.md)
- [CTSM/src/main/clm_instMod.F90](CTSM/clm_instMod.md)
- [CTSM/src/main/clm_varctl.F90](CTSM/clm_varctl.md)
- [CTSM/src/main/lnd2atmMod.F90](CTSM/lnd2atmMod.md)

### Changes to biogeophys
- [CTSM/src/biogeophys/SectorWaterMod.F90](CTSM/SectorWaterMod.md) `new module`
- [CTSM/src/biogeophys/HydrologyNoDrainageMod.F90](CTSM/HydrologyNoDrainageMod.md)
- [CTSM/src/biogeophys/BalanceCheckMod.F90](CTSM/BalanceCheckMod.md)
- [CTSM/src/biogeophys/Waterlnd2atmType.F90](CTSM/Waterlnd2atmType.md)
- [CTSM/src/biogeophys/CanopyHydrologyMod.F90](CanopyHydrologyMod.md)
- [CTSM/src/biogeophys/WaterFluxType.F90](CTSM/WaterFluxType.md)


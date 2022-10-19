---
title: "clm_instMod.F90"
tags:
- CTSM
- Main
enableToc: false # do not show a table of contents on this page
---

## Overview:
In the new module [CTSM/src/biogeophys/SectorWaterMod.F90](Documentation/CTSM/SectorWaterMod.md) we define a new type: `sectorwater_type`.

In this module we create the instance of this object `sectorwater_inst` which later is used during the run.

We also do here the initialization which include allocating the memory and providing default values to the object fields.


## Code:
```fortran
...

! from new module SectorWaterMod.F90 use the sectorwater_type (provide access)
use SectorWaterMod                  , only : sectorwater_type
...

! create instance of the object
type(sectorwater_type), public          :: sectorwater_inst
...

! Initialization
call sectorwater_inst%init(bounds, nlfilename, use_aquifer_layer = use_aquifer_layer())

...
```
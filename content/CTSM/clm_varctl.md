---
title: "clm_varctl.F90"
tags:
- CTSM
- Main
enableToc: false # do not show a table of contents on this page
---

## Overview:
This module contains the run control variables.

To support sectoral water usage we add the `sectorwater` logic variable.
The default value is `.false.` meaning that by default sectoral water usage is not done (this can be changed in CLM/CTSM user namelist after case setup).
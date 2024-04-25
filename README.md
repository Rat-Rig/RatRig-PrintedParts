<a href="https://ratrig.com/">
    <img src="https://ratrig.com/media/athlete2/default/RR_Logo_White.png" alt="RatRig logo" title="RatRig" height="74" />
</a>

# Printed Parts Repository

## Overview
This repository contains STL files pertaining to all existing, as well as obsolete, 3D-printed elements used in our products.

Each design is named with a unique SKU to distinguish it, along with a version number and a date. In the case where a fresh revision becomes necessary (such as rectifying an issue with the part, significant enhancement, or improving the printability), a new part is released with an incremented version number.

In cases where the part undergoes a complete redesign, the old SKU is retired and a new SKU is assigned to the new design.

In all cases, any STL which has been replaced is relocated into a subfolder labeled "deprecated".

## Repository Layout
- Generic parts which are shared across projects are stored either in 'Alignment Tools' or 'Miscellaneous'
- Unique parts for each project are stored in the project subfolder
- Deprecated parts are stored within a 'Deprecated' subfolder
```
├── Alignment-Tools/
│   ├── PP000001-align_2020_mgn12_V01_20230627.stl
│   ├── PP000002-align_2020_mgn15_V01_20230627.stl
│   └── ...
├── ...
├── V-Core-3.1/
├── V-Hive/
└── V-Minion/
    ├── Deprecated/
    │   └── PP000028-shroud_V01_20230628.stl
    ├── PP000013-40mm_fan_cage_V01_20230628.stl
    └── ...
```

## License
All files contained within this repository are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See LICENSE for the full details.
<a href="https://ratrig.com/">
    <img src="https://ratrig.com/media/athlete2/default/RR_Logo_White.png" alt="RatRig logo" title="RatRig" height="74" />
</a>

# Printed Parts Repository

## Overview
This repository contains STL files pertaining to all existing, as well as obsolete, 3D-printed elements used in our products.

Each file is named with a unique SKU to distinguish its particular version. In case a fresh revision becomes necessary (such as rectifying a mistake or enhancement), the previous file gets relocated into a folder labeled "deprecated" while a brand new SKU is allocated to the replacement file.

## Repository Layout
- Generic parts which are shared across projects are stored either in 'Alignment Tools' or 'Miscellaneous'
- Unique parts for each project are stored in the project subfolder
- Deprecated parts are stored within a 'Deprecated' subfolder
```
├── Alignment-Tools/
│   ├── PP000001-align_2020_mgn12.stl
│   ├── PP000002-align_2020_mgn15.stl
│   └── ...
├── ...
├── V-Core-3.1/
├── V-Hive/
└── V-Minion/
    ├── Deprecated/
    │   └── PP000028-shroud.stl
    ├── PP000013-40mm_fan_cage.stl
    └── ...
```

## License

All files contained within this repository are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See LICENSE for the full details.
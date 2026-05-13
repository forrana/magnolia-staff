# Motivation
Fire spinning and flow arts have been my hobbies for a decade now.
Earning money was never a goal for me in this area.
If you check the market, practice and LED equipment, like staffs, are expensive, and at times, fragile.
The goal of this project is to allow hobbyists, like myself, to make their own good-looking practice (and why not) performance equipment.
Equipment they can make, repair, and customize from the comfort of their own kitchens.
Using components they can easily find locally or make themselves at home or at a makerspace.

# Printing Settings
* No supports.
* Print as placed in STL.
* 20% Infill, 4 perimiters, 5 top and bottom solid layers.
* Beam, Front End Disk and Riser Ring parts designed to be printed from TPU or other soft material.
* Back End and Front End parts designed to be printed from hard materials (Tested with silk PLA).

# Navigation

```
magnolia-staff/
├── README.md                    # Project overview and documentation
├── LICENSE.md                   # License information
│
├── files/                       # All project files and assets
│   ├── CAD/                     # CAD models and designs
│   │   └── FreeCAD/             # FreeCAD design files (.FCStd)
│   │   |   ├── beam24.FCStd                 # Beam component design
│   │   |   ├── front-disk.FCStd             # Front disk design
│   │   |   ├── front-end-base-18mm.FCStd    # Front end base (18mm variant)
│   │   |   ├── front-end-base.FCStd         # Front end base (standard)
│   │   |   ├── rear-end-18mm.FCStd          # Rear end (18mm variant)
│   │   |   ├── rear-end.FCStd               # Rear end (standard)
|   |   |   ├── riser-ring.FCStd             # Optional. Rise beams and changes shape of heads.
|   |   |   ├── riser-ring-18mm.FCStd        # Optional. Rise beams and changes shape of heads. (18mm variant)
│   │   |   └── Assembly/        # Assembled designs
│   │   |       └── a2plusassembly.FCStd     # Complete assembly
│   │   └── STEP/                # STEP files (.step)
│   │       ├── beam24.step                  # Beam component design
│   │       ├── front-disk.step              # Front disk design
│   │       ├── front-end-base-18mm.step     # Front end base (18mm variant)
│   │       ├── front-end-base.step          # Front end base (standard)
│   │       ├── rear-end-18mm.step           # Rear end (18mm variant)
│   │       ├── rear-end.step                # Rear end (standard)
|   |       ├── riser-ring.step              # Optional. Rise beams and changes shape of heads.
|   |       └── riser-ring-18mm.step         # Optional. Rise beams and changes shape of heads. (18mm variant)
│   │
│   └── STLs/                    # 3D printable models (STL format)
│       ├── 18mm/                # 18mm staff diameter components
│       ├── 20mm/                # 20mm staff diameter components
│       └── common/              # Common/shared components
│
└── manual/                      # User documentation
    ├── manual.md                # Detailed assembly and usage guide
    └── images/                  # Screenshots and reference images
```

**Quick Links:**
- 📋 **FreeCAD Models**: Check [files/CAD/FreeCAD/](./files/CAD/FreeCAD/) for freecad designs
- 📋 **CAD STEP Models**: Check [files/CAD/STEP/](./files/CAD/STEP/) for universal STEP designs
- 🖨️ **3D Print Files**: Find ready-to-print models in [files/STLs](./files/STLs/)
- 📖 **Assembly Guide**: See [manual/manual.md](./manual/manual.md) for building instructions
- **Printables page**: [Project page](https://www.printables.com/model/1709430-magnolia-practice-flow-spinning-staff)

# Ways to contribute
Let's figure it out together if this project develops further!
For now:
* Clone the project
* Create a branch
* Make your changes
* Open a PR

For ideas and discussion just open an issue in the github tracker

# kicad-keyboard-parts

A collection of KiCad footprints to make it easier to build keyboards and plates.

## Usage

Clone this repo into a directory somewhere withing your project and add it as
a project-specific library under Preferences -> Manage Footprint/Symbol Libraries.

Example:

```
some_kicad_project
├── README.md
├── extra-parts
│   ├── kicad-keyboard-parts
│   │   ├── <stuff from this repo>
├── some_kicad_project.kicad_pcb
├── some_kicad_project.kicad_pro
├── some_kicad_project.kicad_sch
```

## Slots

The goal of the slot footprints library is to be able to create easily-manufacturable top plates for keyboards. The slots are simple
square cutouts with rounded corners so the tooling at PCB fabrication shops can easily route it.

**Note** - These footprints have not been tested yet for fabrication, or for correct fit on actual stabilizers.

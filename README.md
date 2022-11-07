# kicad-keyboard-parts

A collection of KiCad footprints to make it easier to build keyboards and plates.

## Usage

Clone this repo into a directory named `extra-parts` in your KiCad project's top level directory.
It's unfortunate that this is necessary, but as of KiCad 6, relative paths are not supported for
3D models referenced from footprint files.

https://forum.kicad.info/t/best-way-to-share-footprints-with-3d-model/26743/36

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

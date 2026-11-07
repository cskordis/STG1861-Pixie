# Project Folder Layout

This is a proposed organization for the STG-AVI1861 repository. Directories marked **planned** should be added when corresponding, revision-controlled project files are ready. Keep released manufacturing outputs tied to a specific design revision.

```text
STG-AVI1861/
├── README.md
├── LICENSE                 # Add only after project licensing is decided
├── docs/
│   ├── BOM.md
│   ├── BUILD.md
│   └── PROJECT_STRUCTURE.md
└── hardware/               # Planned
    ├── README.md            # Design source, tools, revision, and release notes
    ├── schematic/           # Native schematic files and exported PDF
    ├── pcb/                 # Native PCB layout files
    ├── fabrication/         # Released fabrication outputs (Gerbers, drill files, etc.)
    └── assembly/            # Assembly drawing and placement outputs, if available
```

## Organization notes

- Preserve native editable design files alongside useful review/export files.
- Identify the CAD tool and version used for each released design.
- Keep fabrication and assembly outputs together under a named release or revision.
- Avoid committing temporary exports, caches, or tool-generated files that can be recreated.
- Update the README and build documentation when the design reaches a verified release.

# ESP32S3_USB

Open-source ESP32-S3 development board project designed in EasyEDA Pro.

This repository keeps the editable design source, manufacturing outputs, and release notes separate so the project is easy to review, reproduce, and publish.

## Project Summary

ESP32S3_USB is an open-source ESP32-S3 development board.

Current published assets:

- `design/ProPrj_ESP32S3_USB_2026-05-20.epro2` - Editable EasyEDA Pro project archive
- `manufacturing/gerber/Gerber_PCB2_2026-05-20.zip` - Gerber and drill package
- `manufacturing/gerber/PCB2_2026-05-20/` - Expanded fabrication files for inspection
- `manufacturing/3d/3D_PCB2_2026-05-20.step` - PCB 3D model exported from EasyEDA Pro
- `docs/PCB下单必读.txt` - Original PCB ordering note from the fab package

## What This Repository Contains

- `design/` for the editable source archive
- `manufacturing/` for fabrication and assembly outputs
- `docs/` for build, ordering, and release notes
- `mechanical/` for enclosure or bracket files
- `assets/` for images and diagrams
- `releases/` for frozen release snapshots

## How To Use It

1. Open the `design/` archive in EasyEDA Pro when you want to inspect or edit the source.
2. Use the files under `manufacturing/gerber/` to order PCBs.
3. Use the STEP file in `manufacturing/3d/` for enclosure checks or assembly previews.
4. Read `docs/PCB下单必读.txt` before placing a PCB order.
5. Publish frozen snapshots under `releases/` when you are ready to tag a version.

## Likely Board Features

Verify these against the actual schematic before presenting the project as finished:

- ESP32-S3 based development board
- USB-connected programming and debugging
- Power input and regulation section
- General-purpose I/O broken out for prototyping
- Expansion headers for peripherals or modules

## Keep In Git

- The EasyEDA Pro local project archive
- Gerber, drill, and assembly outputs
- BOM and placement files
- STEP or other 3D exports
- Documentation that helps other people build or review the board
- The project license

## Leave Out Of Git

- Autosave, temp, cache, and lock files
- Local editor settings
- Private keys, tokens, or credentials
- Machine-specific clutter
- Reproducible build artifacts that are not part of a release

## License

This repository uses `CERN Open Hardware Licence Version 2 - Strongly Reciprocal`.

That license is a good fit when you want hardware derivatives to remain open.

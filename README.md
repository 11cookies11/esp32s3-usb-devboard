# ESP32S3_USB

Open-source ESP32-S3 development board project created in EasyEDA Pro.

This repository separates the editable design source from generated manufacturing outputs so the project is easy to review, reproduce, and publish.

## Recommended Layout

- `design/` - Editable EasyEDA Pro project source
- `manufacturing/` - Release files for board houses and assembly
- `mechanical/` - Enclosure, brackets, and other mechanical files
- `docs/` - Assembly notes, test notes, changelog, and project docs
- `assets/` - Images, diagrams, photos, and presentation materials
- `releases/` - Frozen release snapshots for published versions

## Current Files

- `design/ProPrj_ESP32S3_USB_2026-05-20.epro2` - EasyEDA Pro source project
- `manufacturing/gerber/Gerber_PCB2_2026-05-20.zip` - Gerber and drill package
- `manufacturing/gerber/PCB2_2026-05-20/` - Expanded fabrication package for browsing
- `manufacturing/3d/3D_PCB2_2026-05-20.step` - 3D board model exported from EasyEDA Pro
- `docs/PCB下单必读.txt` - Original PCB order note extracted from the fab package

## Project Notes

- The project title inside the source archive is `ESP32S3_USB`.
- The introduction inside the source archive describes it as an ESP32-S3 development board.
- The Gerber package includes fabrication files and a small order note file.
- The expanded gerber folder contains top/bottom copper, solder mask, silkscreen, outline, drill, and flying-probe data.
- The STEP model can be used for enclosure checks, assembly previews, and render generation.

## Suggested Feature Summary

Use this section in the final public README after you verify the board details in EasyEDA Pro.

- ESP32-S3 based development board
- USB-connected programming and debugging
- Power input and regulation section
- General-purpose I/O broken out for prototyping
- Expansion headers for sensors, peripherals, or modules

If any of the items above do not match the real board, trim them before publishing.

## Repository Structure

The repository is set up in release-friendly layers:

- `design/` keeps the editable source archive
- `manufacturing/` keeps fabrication outputs
- `docs/` keeps human-readable instructions
- `releases/` keeps versioned snapshots when you tag a public release

## What To Commit

Commit these first:

- The EasyEDA Pro local project archive exported from `File -> Project Save as (Local)`
- Schematic and PCB source exports if you keep them separately
- BOM export
- Gerber / drill files
- Pick-and-place / assembly files
- 3D exports such as STEP or OBJ
- Documentation that helps others build or verify the hardware
- The project `LICENSE`

## What Not To Commit

Keep these out of Git:

- Autosave, temp, cache, and lock files
- Local editor preferences and machine-specific settings
- Private credentials, API keys, or account tokens
- Personal notes that are not meant for publication
- Raw build clutter that can be regenerated from the source

## EasyEDA Pro Workflow

1. Design the project in EasyEDA Pro.
2. Export a local project archive so others can reopen the editable source.
3. Export Gerber, BOM, placement, and 3D files for manufacturing.
4. Put the source and release files into the matching folders in this repo.
5. Add or update docs before publishing.

## License

This repository uses `CERN Open Hardware Licence Version 2 - Strongly Reciprocal`.

For hardware projects, that is a common choice when you want improvements and redistributions of derivative hardware to stay open as well.

# ESP32S3_USB

Open-source ESP32-S3 development board designed in EasyEDA Pro.

This repository publishes the editable source, fabrication outputs, and supporting documents in one place so the board is easy to review, build, and reuse.

## At A Glance

- Project: `ESP32S3_USB`
- Platform: ESP32-S3
- CAD tool: EasyEDA Pro
- License: CERN Open Hardware Licence Version 2 - Strongly Reciprocal

## Included Files

- `design/ProPrj_ESP32S3_USB_2026-05-20.epro2` - editable EasyEDA Pro project archive
- `manufacturing/gerber/Gerber_PCB2_2026-05-20.zip` - fabrication-ready Gerber package
- `manufacturing/gerber/PCB2_2026-05-20/` - expanded Gerber and drill files for inspection
- `manufacturing/bom/BOM_ESP32S3FN8_USB_PCB2_2026-05-20.xlsx` - BOM export
- `manufacturing/pnp/PickAndPlace_PCB2_2026_05_20.xlsx` - pick-and-place / centroid export
- `manufacturing/3d/3D_PCB2_2026-05-20.step` - 3D board model export
- `docs/PCB下单必读.txt` - PCB ordering note extracted from the fab package

## What The Repo Is Organized For

- `design/` keeps the source project that you edit in EasyEDA Pro
- `manufacturing/` keeps release artifacts for PCB fabrication and assembly
- `docs/` keeps human-readable notes, ordering guidance, and release support files
- `mechanical/` keeps enclosure and bracket assets
- `assets/` keeps pictures, diagrams, and presentation material
- `releases/` keeps frozen snapshots for published versions

## Typical Use

1. Open the EasyEDA Pro archive from `design/` if you need to inspect or revise the schematic or PCB.
2. Send the files in `manufacturing/gerber/` to your board house.
3. Use the BOM in `manufacturing/bom/` for sourcing and assembly.
4. Use the STEP model in `manufacturing/3d/` for enclosure fit checks and assembly previews.
5. Read `docs/PCB下单必读.txt` before placing an order.

## Likely Board Characteristics

These are the expected characteristics of the board, based on the current project name and exported files. Verify them against the schematic before describing the board publicly.

- ESP32-S3 development board
- USB-based programming and debugging
- Power regulation section
- General-purpose I/O broken out for prototyping
- Expansion headers for peripherals or modules

## Source Of Truth

For the current public snapshot, the key artifacts are:

- Source: `design/ProPrj_ESP32S3_USB_2026-05-20.epro2`
- Fabrication: `manufacturing/gerber/Gerber_PCB2_2026-05-20.zip`
- BOM: `manufacturing/bom/BOM_ESP32S3FN8_USB_PCB2_2026-05-20.xlsx`
- 3D: `manufacturing/3d/3D_PCB2_2026-05-20.step`

## License

This repository uses `CERN Open Hardware Licence Version 2 - Strongly Reciprocal`.

That is a good fit when you want derivative hardware to remain open.

# Publish Checklist

Before publishing the repository, make sure these items are present.

## Source

- [ ] EasyEDA Pro local project archive
- [ ] Schematic and PCB source exports if needed
- [ ] Custom part libraries if the design depends on them

## Manufacturing

- [ ] Gerber and drill package
- [ ] BOM export
- [ ] Pick-and-place file
- [ ] 3D export if the enclosure or assembly benefits from it

## Documentation

- [ ] README with project overview
- [ ] Assembly instructions
- [ ] BOM notes or sourcing notes
- [ ] Revision history
- [ ] License file

## For This Repo

- [x] `design/ProPrj_ESP32S3_USB_2026-05-20.epro2`
- [x] `manufacturing/gerber/Gerber_PCB2_2026-05-20.zip`
- [x] `manufacturing/gerber/PCB2_2026-05-20/`
- [x] `manufacturing/bom/BOM_ESP32S3FN8_USB_PCB2_2026-05-20.xlsx`
- [x] `manufacturing/pnp/PickAndPlace_PCB2_2026_05_20.xlsx`
- [x] `manufacturing/3d/3D_PCB2_2026-05-20.step`
- [x] `LICENSE`
- [x] Root `README.md`
- [x] `docs/PCB下单必读.txt`
- [x] `manufacturing/bom/`
- [x] `manufacturing/pnp/`
- [x] `manufacturing/3d/`
- [x] `releases/`

## Sanity Check

- [ ] No secrets or account-specific data
- [ ] No temp or cache files
- [ ] Files open correctly from a clean clone

# Manufacturing

Put fabrication and assembly outputs here.

Recommended contents:

- `gerber/` for PCB fabrication files
- `bom/` for bill of materials exports
- `pnp/` for pick-and-place or centroid files
- `3d/` for STEP or OBJ exports

These files are usually generated from the design source and should be versioned together with the source release they belong to.

Current contents:

- `bom/BOM_ESP32S3FN8_USB_PCB2_2026-05-20.xlsx` - BOM export with part, footprint, and supplier mapping
- `gerber/Gerber_PCB2_2026-05-20.zip` - Original fabrication archive
- `gerber/PCB2_2026-05-20/` - Expanded fabrication files for inspection

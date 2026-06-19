# PCB Files

KiCad project for a 98% ISO Italian layout (100 keys). Includes schematics (`.kicad_sch`), layout (`.kicad_pcb`), and Gerber exports.

## How to export from KiCad

1. Open your project in KiCad and launch **PCB Editor**
2. Go to **File → Fabrication Outputs → Gerbers (.gbr)**
3. Select all layers (F.Cu, B.Cu, F.Silkscreen, B.Silkscreen, F.Mask, B.Mask, Edge.Cuts) and click **Plot**
4. Click **Generate Drill Files** to export the `.drl` file
5. Zip the output folder and commit it alongside your `.kicad_pcb` and `.kicad_sch` files

Gerber exports go in the `gerbers/` subdirectory.

# Miró Extruder (Public **Beta**)
![Miró Extruder](resources/images/miró_isometric.png)

## General Information

The **Miró Extruder** is a high-performance 3D printer extruder that uses two sets of dual-drive gears to provide precise and reliable filament control. It features a compact design, with a bolt pattern fully compatible with the Sherpa Mini extruder.

Unlike my (**knight_rad.iant**) previous Sherpa Mini Crew design, this extruder has been created with no work products from Annex Engineering.  While inspiored by the Sherpa Mini extruder, the Miró extruder is a completely new design, and is not a derivative of the Sherpa Mini extruder.

This extruder is the work product of a collaboration between wick69 from Discord and knight_rad.iant.  Notable testers include Meelis from Discord.

Please use GitHub issues for any questions, feedback, or suggestions you may have. We appreciate your support and hope you enjoy using the Miró Extruder!

Only STLs are provided in this repository.

---


## Bill of Materials (BOM)

| Part Name             | Quantity | Notes                          |
|-----------------------|----------|--------------------------------------|
| 5mm OD x 8mm length shaft          | 1        |               |
| 5mm OD x 20mm length shaft          | 1        |               |
| MR85ZZ bearing          | 3        |               |
| Bondtech EXT-KIT-100             | 1        |     |
| Bondtech EXT-KIT33       | 1        | |
| ECAS04 Collet | 1 | |
| 3mm OD x 28mm length shaft | 1 | |
| M3 nut | 1 | |
| NEMA 14 Pancake Stepper Motor | 1 | |
| M2 heat set insert | 1 | |
| M2 x 6mm screw | 1 | Loctite *must* be used on the screw to keep alignment|


## Printing Instructions
You will need to print one of each the following parts:

- `miró_body_x1.stl`
- `miró_rear_x1.stl`
- `miró_upper_guilder[a]_x1.stl`
- `miró_lower_guilder[a]_x1.stl`

Print one of the front cover from these options available:

- `miró_front[a].stl` (standard front cover)
- `miró_front_k[a].stl` (extended cover, that provides a third attachment point)

Optionally, a `miró_thumbscrew.stl` is provided if you want to use it instead of a standard M3 thumbscrew.  You will also need an M3 x 25mm screw and insert it into the printed part using a soldering iron with a proper tip.

Parts are designed to be printed on ABS @ 0.2mm layer height, 4 perimeters, 5 top/bottom layers, and 40% infill or higher.  Only the guilders are designed to be printed with supports (touching buildplate only).  The direction of the STLs is the direction they should be printed in.

It is important to make sure the extrusion multiplier on your printer is properly calibrated.  The parts are designed to be a tight fit, the parts will not fit correct and align properly if the extrusion multiplier is not correctly.  If you find the main body and rear body are too tight, decrease your EM until they are satisfying fit.

---

## Assembly Instructions

No instructions are provided, but here is a video that shows the assembly process: [Miró Extruder Assembly](resources/videos/miró_assembly.mp4)

---

## Important notes for the assembly

The upper drive gear should be installed without the set screw. and the 5mm x 20mm shaft should be lubricated with EP2 grease.

Once the assembly is complete, use loctite on the M2 x 6mm screw that pushes the 3mm shaft for the middle idler.  This screw is used to keep the correct meshing for the gears. If this screw is not used, the gears will not mesh correctly and the extruder will not work.

The procedure for alignment is as follows:
- Undo the tensioner all the way
- Place loctite on the M2 x 6mm screw
- Tighten the m2 until you find medium resistance
- Turn the POM 50T gear by and and feel for any binding
- If there is binding, loosen the screw 1/8 of a turn at a time, and repeat the process until there is no binding.

## License
[Creative Commons - Attribution - Non-Commercial - No Derivatives](LICENSE-CC-BY-NC-ND-4.0.md)

If you are interested in using this design for commercial purposes, please contact either wick69 or knight_rad.iant on Discord.

## Credits

This project is a collaborative effort between **wick69** and **knight_rad.iant** on Discord. 

2023-2024 by the authors, all rights are reserved.

---

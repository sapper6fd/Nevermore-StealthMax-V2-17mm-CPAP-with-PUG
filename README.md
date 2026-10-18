# Nevermore 17 mm CPAP + PUG Chamber-Side Panel

**A combined Nevermore-style rear chamber panel featuring two angled 17 mm CPAP tube connections and an integrated PUG chamber-side umbilical interface.**

This 3D-printable part brings the two duct connections and the PUG cable pass-through into one housing, while retaining the central vent opening and the familiar **NEVERMORE** front-panel styling.

![3D CAD preview of the Nevermore 17 mm CPAP and PUG chamber-side panel](/17mm_CPAP_Tube_with_PUG_Chamber_Side.png)

![3D CAD preview of the Nevermore 17 mm CPAP and PUG chamber-side panel](/17mm_CPAP_Tube_with_PUG_Chamber_Side_b.png)

## Features

- **Dual angled CPAP tube connections** — one on each side of the panel, for routing flexible ducting.
- **Integrated PUG chamber-side mounting interface** — accommodates the PUG-style umbilical/cable-gland arrangement in the same panel.
- **Central multi-channel opening** — retains the original four-section vent geometry.
- **Original panel details** — includes the visible mounting openings and NEVERMORE lettering.
- **Editable CAD format** — provided as an SLT file for CAD inspection, adjustment, and export to a slicer-friendly format.

## Model file

| File | Description |
| --- | --- |
| [17mm_CPAP_Tube_with_PUG.stl](/17mm_CPAP_Tube_with_PUG.stl) | Complete combined part in SLT format. |

**Approximate overall CAD envelope:** 185.1 × 48.7 × 31.3 mm (X × Y × Z, as oriented in the supplied SLT model). These are bounding-box dimensions, **not** hole spacing or verified installation clearances.

## Intended use and compatibility

Designed for makers adapting a Nevermore/StealthMax-style printer enclosure arrangement to use **two 17 mm CPAP-style ducts** alongside a **PUG chamber-side umbilical pass-through**.

Before printing, verify:

- The panel's footprint, mounting pattern, and clearance against **your** printer's rear panel and filtration hardware.
- The actual mating diameter and fit of your CPAP tubing or couplers; "17 mm" identifies the source design and is not a guarantee of a particular hose tolerance.
- The PUG hardware's fastener spacing, cable path, and strain-relief requirements.
- Clearance for gantry/toolhead travel and for the tubing throughout the printer's full movement range.

This is a custom CAD part; fit has **not** been established for every Nevermore variant or printer configuration.

## Suggested 3D printing setup

The settings below are starting points to tune for your printer and material, rather than a validated print profile.

| Setting | Suggested starting point |
| --- | --- |
| Material | ABS or ASA for enclosed, warm-chamber printers |
| Layer height | 0.20 mm |
| Walls/perimeters | 4–5 |
| Infill | 25–40% |
| Supports | Check overhangs, connector undersides, and the PUG mounting geometry in the slicer |
| Bed adhesion | Consider a brim, especially for ABS/ASA |

Inspect the sliced toolpaths for closed walls, correctly formed tube bores, and unobstructed air passages. Select a build orientation based on which surfaces need the best dimensional accuracy and least support scarring.

## Basic installation

1. **Prepare the print.** Remove any supports, clean the duct openings, and check all mounting interfaces.
2. **Test-fit the panel.** Confirm its position and mounting points against the printer's enclosure/filter assembly before tightening fasteners.
3. **Attach the ducting.** Connect the two CPAP-style tubes and provide suitable retention so the hoses cannot pull the panel loose.
4. **Install the PUG interface.** Fit the matching PUG-side hardware and secure the umbilical cable with appropriate strain relief.
5. **Check operation.** Confirm there are no obstructions, moving-part collisions, cable snags, or major unwanted air leaks.

Use fastener sizes and any additional sealing materials that suit **your specific mating hardware**; a verified bill of materials was not supplied with this part.

## Notes

- The SLT file is a CAD model; export an STL or 3MF from your CAD application if needed by your slicer.
- A SLT model and preview image are provided; hoses, PUG umbilical hardware, screws, and the rest of the printer are **not** included.
- The term *CPAP* describes a style of flexible duct used in printer mods here. **This part is for 3D-printer use only and is not medical equipment.**
- Inspect and test your own print for mechanical strength and fit before use.

## Related projects

- [Nevermore / StealthMax V2](https://github.com/nevermore3d/Stealthmax_V2) — background on Nevermore filtration, CPAP duct routing, and PUG umbilical routing.

This is a community CAD adaptation and is **not an official Nevermore release**. Review the licenses of any upstream designs before redistributing modified geometry, and include an appropriate `LICENSE` file if publishing the repository.

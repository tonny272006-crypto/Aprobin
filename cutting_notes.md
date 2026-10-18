# RoboBin - Laser Cutting Notes (300 x 450 mm sheets)

Source: Cool_Jarv-Blad__1_.stl  |  Material: 2 mm acrylic  |  Units: mm

## Layout
- Sheet size: 300 x 450 mm. 6 sheets needed, 30 parts total, ~72% material use.
- 3 mm gap between parts. No border: the three 300 x 300 plates (P1, P2 x2) are exactly as wide
  as the sheet, so their edges sit on the sheet edge. Measure your real sheets; if they are
  even 1 mm under 300, those plates will come out slightly short.
- No kerf compensation (all joints are plain glued butt joints).
- Lines: red, 0.1 mm, layer CUT.

## Parts (mm)
| ID | Shape | Qty | Notes |
|----|-------|-----|-------|
| P1 | 300 x 300 plate | 1 | Solid base plate |
| P2 | 300 x 300 plate | 2 | 95 x 95 square hole, 49 from left, 148.8 from bottom |
| P3 | 200 x 200 panel | 4 | Bin walls / dividers |
| P4 | 202 x 200 panel | 2 | Bin walls |
| P5 | 20 x 270 strip | 8 | Lower corner strips |
| P6 | 20 x 70 strip | 8 | Upper corner strips |
| P7 | 95 x 70 panel | 3 | Upper chamber walls |
| P8 | 117 x 70, corner notch 22 x 11 | 1 | Upper chamber wall |
| P9 | 95 x 117, notch 80 x 22, small hole | 1 | See warning 1 |

## Warnings
1. P9: the small hole (~11.7 x 14.7 mm) leaves only ~1.2 mm of acrylic next to the notch edge.
   It will snap in 2 mm acrylic. Widen that tab to leave 5 mm or more around the hole.
2. P3 dividers: two 200 x 200 dividers cross in the middle of the bin box. They need a 2 mm
   wide, 100 mm deep slot each (one from the top edge, one from the bottom). Not added.
3. No tabs or slots anywhere; parts must be glued or bracketed.
4. In the STL the second top plate is offset 1 mm (X) and 3.6 mm (Y) from the first. The flat
   parts are identical, so stacked edge to edge their holes line up exactly.
5. Not cut (hardware placeholders in the STL): a 52 x 52 x 45 mm block, a 12 x 34 x 23 mm
   servo-like block, and a few tiny 0.25 mm items.

## Before cutting
- Open an SVG in Inkscape and measure P1 (must be exactly 300 x 300 mm).
- Ask the shop which colour/layer means "cut".
- Cut one small test piece first.

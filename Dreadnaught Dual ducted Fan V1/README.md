<img width="1193" height="641" alt="image" src="https://github.com/user-attachments/assets/5461ccb0-508d-4671-8776-c0e7842ba2fc" />


## Dreadnaught Dual Ducted Fan v1 Release

The Dreadnaught Dual Ducted Fan v1 is a high-power fan-based toolhead for Monolith belt path and Voron-style printers (Soon), built around an underslung hotend mount and dual 30 mm ducted fans.

Using two 130 W / 5.5 A ducted fans, the toolhead has a combined fan capacity of 260 W and 11 A. This makes it one of the most powerful integrated fan-cooled toolhead designs currently released for this printer class.

The design carries over the core Dreadnaught layout goals: high hotend rigidity, compact packaging, no Xy-travel loss, and a centre of mass kept close to the MGN12H rail carriage. The underslung hotend layout keeps the filament path tight to the rail while leaving room for an accessible belt clamp arrangement supporting up to 12 mm belts.

This version replaces the external CPAP-style airflow approach with a self-contained dual ducted fan system, targeting extreme part cooling for high-speed printing while retaining the compact Dreadnaught toolhead architecture.

## Features
- For Monolith Belt path style Core XY printers
- Support for belts up to 12 mm wide.
- 28mm Fans used: https://github.com/Thescarecow/130K-RPM-28mm-ducted-fan-Cad-COM 
- No Xy-travel loss from the toolhead package size.
- Underslung hotend layout for improved centre-of-mass placement.
- Removable centre core with replaceable square nut interface.
- Reinforced hotend mounting through longer front bolts into the rail carriage.
- Combined hotend mounting pattern for Chube, Tricore, and Goliath hotends (providing the mounting bolts are tapped to M3).
- M3 washer support for more secure hotend mounting.
- Two versions
  Chube / Tricore length
  Goliath length
- Internal cable routing paths for cleaner hotend fan and probe wiring from the front of the toolhead down through the ducts.

## NOTES: These fans are LOUD and pull a lot of power (24v 130W 5.5A EACH) Also the combo of  High RPM + Metal fan = will eat fingers, tools, bolts alike with stunning results, never run them with loose items around that could be sucked/fall into the blades while they are running

## Hotends supported
- Chube Air
- Tricore
- Goliath

## Extruders supported
- Orb2
- Sherpa mini

## Print settings & Filament types

6/6/6 40%

Recommended:
Annealed
- PET-CF/GF
- PPS-CF/GF

Avoid:
- ABS
- ASA
- Most PC-CF's

## BOM
- 8x M3 washers 7mm OD 1mm thick <- use the washers they are here for a reason for both the rail carriage mounting bolts and the hotend mounting bolts
- 4x m2.5 SHCS 16mm <-Delta fan mount
- 4x m2.5 heatsets 
- 10x m3 square nuts (5.5mm x 3.5mm)
- 2x m3 Heatsets (4.7mm x 3mm) 2 for the beacon mount
- 2x m3 SHCS 25mm <- Stiffner bolt
- 2x m3 SHCS 16mm <-Extruder mount
- 2x m3 SHCS 8mm <-rear hotend bolts
- 2x m3 SHCS 45mm <-front hotend bolts 

## Fan wiring and Klipper control
[Fan Motor Wiring](https://github.com/Thescarecow/Dreadnaught-Toolhead/blob/main/Dreadnaught%20Dual%20ducted%20Fan%20V1/Fan%20Installation%20and%20cable%20routing.md)

[Fan Driver Wiring Guide](https://github.com/Thescarecow/Dreadnaught-Toolhead/blob/main/Dreadnaught%20Dual%20ducted%20Fan%20V1/Fan%20Driver%20Wiring%20and%20Klipper%20Code.md)


## Repository notices

Licence scope, third-party compatibility targets, and image-reference handling are documented in `LICENSE.txt`, `THIRD_PARTY_REFERENCES.md`, and `IMAGE_REFERENCES.md`.

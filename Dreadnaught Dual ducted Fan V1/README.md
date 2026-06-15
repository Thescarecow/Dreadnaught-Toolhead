<img width="561" height="578" alt="image" src="https://github.com/user-attachments/assets/85a6fcf0-bb26-4314-856c-97eef1b19b81" />

## Dreadnaught Multicore CPAP v1 Release

The Dreadnaught Multicore CPAP v1 is a high performance 3D printer toolhead design built around an underslung hotend mount. The design goal was to improve hotend rigidity, belt mounting flexibility, and centre-of-mass placement while retaining a compact package with no X-travel loss.

Underslinging the hotend below the MGN12H rail allows the filament path to sit close to the rail carriage. This helps keep the toolhead COM concentrated near the X gantry Rail carraige as much as possible, allowing for faster printing speeds while still keeping high print quailties.

The underslung layout also allows for a compact belt clamp arrangement. The belt path supports up to 12 mm belts while keeping the clamp accessible, robust, and easy to adjust.

## Features
- For Monolith Belt path style Core XY printers
- Support for belts up to 12 mm wide.
- 16mm tube CPAP
- No X-travel loss from the toolhead package size.
- Underslung hotend layout for improved centre-of-mass placement.
- Removable centre core with replaceable square nut interface.
- Reinforced hotend mounting through longer front bolts into the rail carriage.
- Combined hotend mounting pattern for Chube, Tricore, and Goliath hotends (providing the mounting bolts are tapped to M3).
- M3 washer support for more secure hotend mounting.
- Multiple CPAP duct length options:
  Chube / Tricore length CPAP duct.
  Goliath length CPAP duct.
- Internal cable routing paths for cleaner hotend fan and probe wiring from the front of the toolhead down through the ducts.

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
- 4x m3 Heatsets (4.7mm x 3mm) <- 2 for the rear duct mount & 2 for the beacon mount
- 2x m3 SHCS 35mm <- front Duct to main body mounting
- 2x m3 SHCS 12mm <- rear Duct to main body mounting
- 2x m3 SHCS 16mm <-Extruder mount
- 2x m3 SHCS 8mm <-rear hotend bolts
- 2x m3 SHCS 45mm <-front hotend bolts 


## Core Structure

<img width="753" height="391" alt="image" src="https://github.com/user-attachments/assets/ace6bc66-f6fb-4593-b429-44ce511236ab" />

The centre core houses a seperate part for the Belt clamp nuts. This means that if a bolt breaks, a nut galls, or the thread interface is damaged, the centre core can be replaced without reprinting the entire toolhead.

The centre core also forms part of the reinforced hotend mounting structure. Longer front mounting bolts tie the hotend mount back into the rail carriage, which should improve stiffness compared with shorter bolts lacking the same support structure

## Backstory

Development started at the start of 2025 with the aim of producing a high-performance plastic toolhead wiht a focus on optimal COM placement, flexability in extruder and hotend options and the added benifit of the undersling hoend allowing both better COM placement but also microbowden performance to add in PA tuning

The main design direction was to place the hotend underslung below the MGN12H rail, with the filament path positioned as close to the rail as practical. This was considered a viable way to improve centre-of-mass placement compared with more conventional front-mounted toolhead layouts.

<img width="350" height="597" alt="image" src="https://github.com/user-attachments/assets/ee56b00a-ab72-4c49-b1a8-b5b305b78730" />


## Repository notices

Licence scope, third-party compatibility targets, and image-reference handling are documented in `LICENSE.txt`, `THIRD_PARTY_REFERENCES.md`, and `IMAGE_REFERENCES.md`.

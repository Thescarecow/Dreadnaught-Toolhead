# Dreadnaught Toolhead
<img width="2494" height="1297" alt="image" src="https://github.com/user-attachments/assets/45135bdc-d54e-4c15-a5c7-8f52e41cee55" />

Welcome to Dreadnaught, a high-performance 3D printer toolhead platform for Monolith belt path and Voron belt path (soon) CoreXY printers, built around an underslung hotend mount, compact belt path, and high-output part-cooling options.

The platform supports currently both the Multicore CPAP version and the Dual Ducted Fan version. The CPAP variant is designed around external high-flow CPAP cooling and maximising COM and Toolhead stiffness, while the Dual Ducted Fan version uses a pair of integrated 28 mm ducted fans rated at 130 W / 5.5 A each, giving a combined fan capacity of 260 W and 11A. 

This makes the dual fan version the most powerful integrated fan-cooled toolhead design currently released for these types of printers and provides more part cooling potential then a WS7040 or even a WS9290 CPAP. 

The underslung hotend layout keeps the filament path and centre of mass close to the MGN12H rail carriage while also allowing for up to 12mm belts supported, improving rigidity and high-speed print stability while retaining compact packaging and no XY-travel loss.

## Key features

- Up to 12 mm belt support
- Monolith-style belt path with voron planed in the future
- CPAP and fan-cooled variants
- Extruder mounting support for Orbiter v2.0 and Sherpa Mini bolt patterns
- Hotend mounting support for Chube Air, Goliath Air, and Tricore Long Air
- Belt clamp options for 6 mm, 9 mm, and 12 mm belts

## Current Release versions

### Dreadnaught Multicore CPAP v1
[Dreadnaught Multicore CPAP](https://github.com/Thescarecow/Dreadnaught-Toolhead/tree/main/Dreadnaught%20Multicore%20CPAP%20v1)

Supported hotends:

- Chube Air
- Goliath Air
- Tricore Long Air
- Other hotends with the same total length as the ones listed providing they also match the bolt mounting locations as well
Note: Some hotend mounting configurations may require tapping hotend mounts to M3.

Supported extruder mounting patterns:

- Orbiter v2.0
- Sherpa Mini

## Dreadnaught Dual 28 mm Ducted Fans v1 ##
[Dreadnaught Dual 28mm Ducted Fans](https://github.com/Thescarecow/Dreadnaught-Toolhead/tree/main/Dreadnaught%20Dual%20ducted%20Fan%20V1)
Fans used: https://github.com/Thescarecow/130K-RPM-28mm-ducted-fan-Cad-COM

Supported hotends:

- Chube Air
- Goliath Air
- Tricore Long Air
- Other hotends with the same total length as the ones listed providing they also match the bolt mounting locations as well
Note: Some hotend mounting configurations may require tapping hotend mounts to M3.

Supported extruder mounting patterns:

- Orbiter v2.0
- Sherpa Mini

## Core Structure ##
<img width="753" height="391" alt="Dreadnuaght core" src="https://github.com/user-attachments/assets/6f67a3eb-c137-4010-acf0-03fd3681e8f0" />

The centre core houses a seperate part for the Belt clamp nuts. This means that if a bolt breaks, a nut galls, or the thread interface is damaged, the centre core can be replaced without reprinting the entire toolhead.

The centre core also forms part of the reinforced hotend mounting structure. Longer front mounting bolts tie the hotend mount back into the rail carriage, which should improve stiffness compared with shorter bolts lacking the same support structure

## Backstory ## 
Development started at the start of 2025 with the aim of producing a high-performance plastic toolhead wiht a focus on optimal COM placement, flexability in extruder and hotend options, part of this was moving the hotend back and slighty under the rail carriage to undersling it, allowing both better COM placement but also microbowden performance to add in PA tuning.

The main design direction was to place the hotend underslung below the MGN12H rail, with the filament path positioned as close to the rail as practical. This was considered a viable way to improve centre-of-mass placement compared with more conventional front-mounted toolhead layouts.


<img width="350" height="597" alt="Dreadnaught Cpap section veiw" src="https://github.com/user-attachments/assets/e117b89b-3afd-49ff-a1d1-930f72ed9994" /><img width="350" height="597" alt="dreadnaught early prototype" src="https://github.com/user-attachments/assets/70efcccf-9775-4e16-afae-0acd9b567a5b" />


## Planned future versions

- Single 30 mm ducted fan version
- Dual 3268 fan version
- Dual 5015 fan version
- Integrated Orbiter 2.5 gear set version
- Topology-optimized SLM version
- CNC version


## Repository notices

Licence scope, third-party compatibility targets, and image-reference handling are documented in `LICENSE.txt`, `THIRD_PARTY_REFERENCES.md`, and `IMAGE_REFERENCES.md`.

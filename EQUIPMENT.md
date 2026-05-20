# Brewery Equipment

Small craft brewery in Loznica, Serbia.
All recipes in this repository are calibrated to this setup.

---

## Brew System

**Type:** Single-vessel RIMS with malt basket and bottom-up wort recirculation  
**Model:** Bavaria, BrauMeister-style clone based on Speidel Braumeister architecture  
**Vessel capacity:** 69 L to upper rim  
**Working volume:** 50 L mash water + 12 L sparge for a standard batch  
**Heating element:** 3.2 kW, submerged  
**Temperature control:** Automated, programmable mash steps

Wort is recirculated upward through the grain basket by magnetic centrifugal pumps.

---

## Pumps

| Parameter | Value |
| --- | --- |
| Count | 2 × magnetic centrifugal |
| Flow control | Manual |
| Operating flow | Maximum during mash recirculation |
| Estimated max flow | ~1200 L/h, no load |
| Function | Mash recirculation |

---

## Mill

| Parameter | Value |
| --- | --- |
| Type | Two-roller mill |
| Roller gap | 1.1 mm |

---

## Chiller

| Parameter | Value |
| --- | --- |
| Type | Immersion, copper coil |
| Current config | 25 turns, 8 mm tube, 41 cm coil diameter |
| Planned addition | 2nd inner coil, 20 turns, 32–33 cm diameter |
| Planned water path | Single inlet, both coils in series |

The current single-coil configuration is functional but undersized for rapid chilling at full batch volume.
The planned concentric inner coil increases heat exchange surface area while keeping the same vessel footprint.

---

## Fermenters

| Parameter | Value |
| --- | --- |
| Material | Food-grade plastic |
| Volume | 60 L |
| Sealing | Airtight lid with gasket |
| Airlock | Standard water airlock |

---

## Kegs

| Parameter | Value |
| --- | --- |
| Type | C-type |
| Sizes | 20 L and 30 L |

---

## Fermentation Chambers

| Component | Spec |
| --- | --- |
| Insulation | 10 cm expanded polystyrene |
| Cooling | Glycol line from repurposed refrigerator compressor |
| Heating | Incandescent lamps |
| Air circulation | 100 mm inline fan, 220V |
| Controller | CS3008, PID, ±0.5°C |
| Chamber capacity | Up to 6 × 60 L fermenters |
| Chambers | 4 total |

---

## Notes

- All recipes assume this system unless stated otherwise
- Process details and calibrated operating parameters are documented in [PROCESS.md](./PROCESS.md)
- Brewers on different setups should adjust for their own efficiency, evaporation rate, chilling speed, and fermentation control

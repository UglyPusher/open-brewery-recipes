# Brewery Process

Standard operating procedure for all recipes in this repository.
Recipes reference this document for process details not repeated in each recipe file.

---

## Water

**Source:** Spring water, Serbia, Loznica, Banja Koviljača, Banjski izvor  
**Treatment:** None  
**Character:** Softer than Loznica municipal tap water, calcium-forward

This water suits hop-forward and Belgian styles well.
Full lab mineral data is not currently available.
The practical target is soft water with noticeable calcium and lower hardness than the local municipal supply.

Brewers on hard or mineralised water should adjust accordingly, especially for roasted-malt recipes where chloride and carbonate levels affect perceived bitterness.

---

## Sanitation

| Step | Agent | Temp | Time | Notes |
| --- | --- | --- | --- | --- |
| Pre-rinse | Cold water | Cold | 3 min | Remove beer residue |
| Wash | NaOH 1.5% | 70°C | 8 min | All contact surfaces |
| Rinse | Municipal tap water | Cold | 2 min | Remove caustic residue |
| Sanitise | Ethanol 75% | Ambient | 5 min contact | Final step before use, no rinse |

Applied to fermenters, open kegs, chiller, transfer lines, and all wort-contact surfaces.

---

## Mash

Mash water volume and temperature steps are specified per recipe.
Malt is milled on a two-roller mill with a 1.1 mm roller gap.
Ireks malt is treated as stable between batches; color drift has not been significant in practice.

Standard system assumptions:

| Parameter | Value |
| --- | --- |
| Standard mash water | 50 L |
| Standard sparge water | 12 L |
| Pre-boil volume | ~46–48 L |
| Mash pH target | 5.3 |
| Mash efficiency | 75–78%, Weyermann baseline; Ireks may vary slightly |

Sparge water is poured over the grain basket after it is lifted clear of the wort.
It drains through the grain bed by gravity back into the vessel.
Sparge temperature is mash-out temperature, around 78°C.

---

## Boil & Hops

Boil duration and hop additions are specified per recipe.
All hops are T90 pellets.

| Parameter | Value |
| --- | --- |
| Standard boil | 90 minutes unless stated otherwise |
| Boil vigor | Normal rolling boil |
| Evaporation rate | ~6 L per 90 min at 80% heater power |
| Post-boil volume before top-up | ~50–52 L |
| Top-up volume range | Usually 2–5 L |
| Volume into fermenter | 52–53 L, normally 52+ L |
| Kettle dead space/losses | ~1–2 L, including hop and trub losses |
| Gravity correction | Top-up with hot water at end of boil |
| Gravity measurement | Refractometer |

OG is adjusted at the end of boil by topping up with hot water to reach target gravity.
This is the primary correction method, not mash adjustment.
The kettle valve sits approximately 3 cm above the bottom; everything left below the valve is counted as process loss.

---

## Gravity Measurement

Gravity is measured with a Chinese handheld refractometer.
The instrument has been checked against laboratory readings; it has a small bias but is stable enough for brewery use.
It has been used as the house reference instrument for about 15 years.

Calibration is done with water at 20°C.
OG and FG values in recipes are refractometer readings.
FG values are corrected for alcohol content.

---

## Chilling

Immersion copper chiller is used directly in the brew vessel.
Wort is chilled in the vessel to pitching temperature before transfer.
There is no intermediate step: chilling target and pitching temperature are the same.

Chiller spec: see [EQUIPMENT.md](./EQUIPMENT.md).

| Season | Cooling water temp | Typical chilling time for 50 L |
| --- | --- | --- |
| Winter | +10–12°C | ~15–20 min |
| Summer | +17–18°C | ~25–35 min |

Cooling water flow rate has not been measured.

---

## Transfer & Aeration

Transfer to fermenter is done by gravity from approximately 1 m height.
Flow is intentionally turbulent to improve wort aeration before yeast pitch.
Natural splash aeration during transfer is sufficient for the target pitch rates.
There is no separate aeration step.

---

## Yeast Pitch

Dry yeast is pitched directly into the fermenter, with no rehydration.
Yeast is added at the wort pitching temperature specified per recipe.

Standard pitch for most 50 L batches: 2 × 11.5 g sachets.
Recipe-specific pitch rates override this where stated.

---

## Fermentation

Fermenters are placed in insulated temperature-controlled chambers.
Fermentation temperature profiles are specified per recipe.

Temperature-control hardware is documented in [EQUIPMENT.md](./EQUIPMENT.md).

---

## Transfer to Keg

Standard batch output is 50 L, split into two kegs: 20 L + 30 L.

Kegs are C-type, 20 L and 30 L.
They are purged with CO₂ before filling.
CO₂ blanket pressure is not measured.

Transfer is open, by gravity, with laminar flow and minimal oxygen contact.
The transfer hose end is kept below the beer level in the keg.

To distribute trub evenly between two kegs, transfer is done in alternating passes:

1. Fill first keg to half volume
2. Switch to second keg, fill to half volume
3. Return to first keg, complete fill
4. Complete second keg

This keeps settled material proportional between kegs instead of concentrating it in the last keg.

---

## Conditioning & Carbonation

Conditioning temperature, duration, and carbonation method are specified per recipe.

Most Belgian and wheat recipes use natural carbonation in keg under a CO₂ blanket, with no forced carbonation.
Carbonation comes from residual fermentation after transfer to keg, not from priming sugar.
Beer is transferred before fermentation is completely finished, leaving enough residual fermentable sugar for carbonation in keg.
The transfer timing was calibrated experimentally for this brewery.
Because fermentation temperature is controlled, recipe timings are repeatable within normal batch variation.
Recipes that specify pressure carbonation, such as the IPA, follow the pressure and temperature stated in the recipe.

---

## Notes

- Total brew session duration: approximately 5 hours, including mash, boil, transitions, chilling, transfer, and equipment cleaning
- All recipes assume the equipment described in [EQUIPMENT.md](./EQUIPMENT.md)
- Process deviations, such as a different chiller, forced carbonation, or different fermenter type, will affect results

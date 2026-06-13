# Barber Brief Schema

The barber brief turns a StyleOS hairstyle recommendation into salon-ready language.

## Object: `styleos_barber_brief`

```yaml
version: "0.2"
user_goal:
  - "softer"
  - "more professional"
current_concern:
  - "jawline feels over-emphasized by current hair end position"
keep:
  - "medium length"
adjust:
  - "soft face-framing layer"
  - "control jawline weight"
avoid:
  - "blunt end exactly at widest jawline point"
length_direction: "collarbone-length transition"
bangs_direction: "no heavy bangs, optional light side pieces"
layer_direction: "soft layer, face-framing starts below cheekbone"
volume_direction: "natural crown support, side volume controlled"
color_direction: "natural black / near black"
maintenance_level: "medium"
reference_keywords:
  - "soft face framing"
  - "client-facing clean"
do_not_do_list:
  - "do not cut a blunt chin-length line"
creator_note: "Synthetic example. Creator should manually review before delivery."
```

## Field Notes

- `user_goal`: what the user wants the haircut to support.
- `current_concern`: neutral description of the current issue.
- `keep`: what should remain unchanged.
- `adjust`: what the stylist should change.
- `avoid`: risk areas.
- `length_direction`: target length range.
- `bangs_direction`: bangs or no-bangs direction.
- `layer_direction`: layer position and intensity.
- `volume_direction`: crown, side, and jawline weight.
- `color_direction`: direction only, not product code.
- `maintenance_level`: low, medium, or high.
- `reference_keywords`: searchable or verbal keywords, not private photos.
- `do_not_do_list`: clear execution boundaries.
- `creator_note`: manual review and assumptions.

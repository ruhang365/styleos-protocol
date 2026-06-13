# Synthetic Hairstyle Case 001: Square Jaw Soft Goal

## Case ID

`SYNTH-HAIR-001`

## Synthetic Disclaimer

This is a synthetic case for protocol testing. It does not describe a real person and includes no photos, names, contacts, or private records.

## User Profile

- Age range: 25-34
- Context: client-facing work
- Hair length: medium
- Hair volume: medium
- Maintenance willingness: medium

## Target Scenario

- Primary: client meeting
- Secondary: work profile photo

## Input Tags

- `face_shape_square`
- `jawline_width_visible`
- `goal_look_softer`
- `goal_look_more_professional`
- `maintenance_medium`

## Key Concerns

- The user wants a softer workday impression.
- The current end length sits close to the strongest jawline point.
- The change should remain moderate and easy to explain to a stylist.

## Selected Rule Cards

- [HAIR-RULE-001](../../rules/hairstyle/HAIR-RULE-001.md)
- [HAIR-RULE-021](../../rules/hairstyle/HAIR-RULE-021.md)
- [HAIR-RULE-039](../../rules/hairstyle/HAIR-RULE-039.md)

## Lite Recommendation

Move the end point away from the jawline widest point and add soft side layers. Keep the overall shape clean and stable for client-facing days.

## Barber Brief

Use [Barber Brief Card](../../execution-cards/barber-brief-card.md).

```yaml
goal: "softer, cleaner workday outline"
keep:
  - "medium length"
  - "professional daily shape"
adjust:
  - "soft side layers"
  - "end point away from jawline widest point"
avoid:
  - "blunt chin-length end"
  - "heavy side volume at jawline"
maintenance_level: "medium"
```

## Feedback Placeholder

- Clarity score:
- User actionability:
- Stylist communication risk:

## Privacy Note

No identifiable data is included.

# Synthetic Hairstyle Case 010: Glasses and Hairstyle Balance

## Case ID

`SYNTH-HAIR-010`

## Synthetic Disclaimer

This is a synthetic case for protocol testing. It does not describe a real person and includes no photos, names, contacts, or private records.

## User Profile

- Age range: 24-40
- Context: glasses worn daily
- Hair length: medium
- Hair volume: medium
- Maintenance willingness: medium

## Target Scenario

- Primary: video call
- Secondary: client meeting

## Input Tags

- `accessory_glasses`
- `bangs_present`
- `goal_look_cleaner`
- `scenario_video_call`
- `maintenance_medium`

## Key Concerns

- Bangs and frame compete around the eyes.
- Sideburn shape looks crowded with frame temples.
- Video lighting creates shadows around the eye area.

## Selected Rule Cards

- [HAIR-RULE-018](../../rules/hairstyle/HAIR-RULE-018.md)
- [HAIR-RULE-036](../../rules/hairstyle/HAIR-RULE-036.md)
- [HAIR-RULE-037](../../rules/hairstyle/HAIR-RULE-037.md)

## Lite Recommendation

Lighten bangs, control sideburn shape, and keep the eye area open for glasses and video lighting.

## Barber Brief

```yaml
goal: "clean glasses-compatible hairstyle"
keep:
  - "medium length"
adjust:
  - "lighten bangs"
  - "reduce sideburn crowding near frame temples"
  - "keep eye area open"
avoid:
  - "bangs pressing into glasses"
  - "heavy side pieces casting eye shadow"
maintenance_level: "medium"
```

## Feedback Placeholder

- Clarity score:
- User actionability:
- Glasses fit:

## Privacy Note

No identifiable data is included.

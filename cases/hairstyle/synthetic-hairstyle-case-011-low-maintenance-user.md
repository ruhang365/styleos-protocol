# Synthetic Hairstyle Case 011: Low Maintenance User

## Case ID

`SYNTH-HAIR-011`

## Synthetic Disclaimer

This is a synthetic case for protocol testing. It does not describe a real person and includes no photos, names, contacts, or private records.

## User Profile

- Age range: 21-39
- Context: busy weekday schedule
- Hair length: collarbone
- Hair volume: medium
- Maintenance willingness: low

## Target Scenario

- Primary: daily commute
- Secondary: casual work

## Input Tags

- `maintenance_low`
- `haircut_risk_low`
- `goal_look_cleaner`
- `salon_return_long`
- `layer_low_maintenance`

## Key Concerns

- The user has little time for daily styling.
- The user returns to salon infrequently.
- The recommendation should still be actionable for a stylist.

## Selected Rule Cards

- [HAIR-RULE-017](../../rules/hairstyle/HAIR-RULE-017.md)
- [HAIR-RULE-033](../../rules/hairstyle/HAIR-RULE-033.md)
- [HAIR-RULE-034](../../rules/hairstyle/HAIR-RULE-034.md)

## Lite Recommendation

Choose forgiving layers, stable length, and a simple reset routine. Avoid precision features that need frequent trimming or daily tools.

## Barber Brief

```yaml
goal: "clean low-maintenance daily haircut"
keep:
  - "collarbone length"
  - "forgiving grow-out"
adjust:
  - "subtle low layers"
  - "simple parting"
avoid:
  - "precise short bangs"
  - "style dependent on daily hot tools"
maintenance_level: "low"
salon_return_cycle: "long"
```

## Feedback Placeholder

- Clarity score:
- User actionability:
- Grow-out fit:

## Privacy Note

No identifiable data is included.

# Synthetic Hairstyle Case 012: Creator Before Haircut Brief

## Case ID

`SYNTH-HAIR-012`

## Synthetic Disclaimer

This is a synthetic case for protocol testing. It does not describe a real person and includes no photos, names, contacts, handles, or private records.

## User Profile

- Age range: 25-44
- Context: creator preparing for profile refresh
- Hair length: medium-long
- Hair volume: medium
- Maintenance willingness: medium-high

## Target Scenario

- Primary: pre-shoot haircut
- Secondary: personal IP update

## Input Tags

- `scenario_pre_shoot`
- `scenario_personal_ip`
- `goal_creator_presence`
- `haircut_risk_medium`
- `maintenance_medium`

## Key Concerns

- The user needs a haircut before a camera-facing refresh.
- The hairstyle should keep one recognizable cue.
- The change should stay stable for photos and short video.

## Selected Rule Cards

- [HAIR-RULE-035](../../rules/hairstyle/HAIR-RULE-035.md)
- [HAIR-RULE-038](../../rules/hairstyle/HAIR-RULE-038.md)
- [HAIR-RULE-039](../../rules/hairstyle/HAIR-RULE-039.md)
- [HAIR-RULE-040](../../rules/hairstyle/HAIR-RULE-040.md)

## Lite Recommendation

Keep one controlled memory cue, avoid large last-minute changes, and turn the creator goal into a structured barber brief.

## Barber Brief

```yaml
goal: "camera-stable creator hairstyle with one memory cue"
scenario: "profile refresh and short video"
keep:
  - "medium-long length"
  - "recognizable side part cue"
adjust:
  - "clean ends"
  - "soft face-side movement"
  - "reduce unstable flyaway pieces"
avoid:
  - "large change right before shoot"
  - "multiple strong cues stacked together"
maintenance_level: "medium-high"
creator_note: "Synthetic example for StyleOS v0.2."
```

## Feedback Placeholder

- Clarity score:
- User actionability:
- Camera stability:
- Creator memory cue:

## Privacy Note

No identifiable data is included.

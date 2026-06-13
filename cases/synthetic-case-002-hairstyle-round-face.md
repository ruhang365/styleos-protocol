# Synthetic Case 002: Hairstyle Round Face

## Case ID

`SYNTH-CASE-002`

## Synthetic Disclaimer

This is a synthetic case for protocol demonstration only.

中文说明：这是合成案例，不对应真实人物。

## User Profile

- Age range: 18-24
- Context: student transitioning to internship
- Hair volume: medium
- Hair shape: straight
- Maintenance willingness: low

## Target Scenario

- Primary: internship workday
- Secondary: profile photo

## Input Tags

- `face_shape_round`
- `feature_weight_soft`
- `goal_look_cleaner`
- `maintenance_low`

## Key Concerns

- Wants a cleaner impression.
- Does not want heavy daily styling.
- Unsure whether full bangs are needed.

## Selected Rule Cards

- [HAIR-RULE-002](../rules/hairstyle/HAIR-RULE-002.md)
- [HAIR-RULE-009](../rules/hairstyle/HAIR-RULE-009.md)

## Lite Recommendation

Use light face-framing and controlled side volume. Avoid thick straight bangs as the default answer. Keep daily styling simple and repeatable.

## Execution Card

Use [Barber Brief Card](../execution-cards/barber-brief-card.md).

```yaml
goal: "cleaner internship-ready hairstyle"
current_concern: "side hair feels close to the cheeks"
keep:
  - "low maintenance"
adjust:
  - "light face-framing"
  - "moderate crown support"
avoid:
  - "very thick straight bangs"
  - "side hair pressing against cheeks"
reference_keywords:
  - "light layers"
  - "clean workday"
maintenance_level: "low"
```

## Feedback Placeholder

- Was it easy to explain to a hairstylist?
- Did the recommendation fit the scenario?

## Privacy Note

No real student, school, workplace, or image data is included.

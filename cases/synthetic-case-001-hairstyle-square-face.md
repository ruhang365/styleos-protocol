# Synthetic Case 001: Hairstyle Square Face

## Case ID

`SYNTH-CASE-001`

## Synthetic Disclaimer

This is a synthetic case. It does not describe a real person and does not include real photos, names, contacts, or private data.

中文说明：这是合成案例，仅用于协议演示。

## User Profile

- Age range: 25-34
- Context: office worker
- Maintenance willingness: medium
- Hair length: medium
- Hair volume: medium

## Target Scenario

- Primary: client meeting
- Secondary: social profile photo

## Input Tags

- `face_shape_square`
- `goal_balance_jawline`
- `goal_look_softer`
- `maintenance_medium`

## Key Concerns

- Wants a softer workday impression.
- Does not want a major haircut.
- Wants a clear barber communication card.

## Selected Rule Cards

- [HAIR-RULE-001](../rules/hairstyle/HAIR-RULE-001.md)
- [HAIR-RULE-012](../rules/hairstyle/HAIR-RULE-012.md)

## Lite Recommendation

Use soft side layers and avoid a blunt length ending exactly at the widest jawline point. Keep the overall shape clean for work, with a low-to-medium maintenance plan.

## Execution Card

Use [Barber Brief Card](../execution-cards/barber-brief-card.md).

```yaml
goal: "softer and professional"
current_concern: "hair length stops near the strongest jawline area"
keep:
  - "medium length"
adjust:
  - "soft side layers"
  - "avoid hard stop at jawline"
avoid:
  - "blunt chin-length cut"
reference_keywords:
  - "soft face framing"
  - "workday clean"
maintenance_level: "medium"
```

## Feedback Placeholder

- Clarity score:
- User actionability:
- Creator notes:

## Privacy Note

No real photo, identity, contact, or service record is included.

# HAIR-RULE-003

```yaml
rule_id: "HAIR-RULE-003"
rule_name: "Long face crown height caution"
module: "hairstyle"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "face_shape_long"
    - "goal_look_softer"
  signals:
    - "vertical face impression is already strong"
recommendation:
  summary: "Avoid adding excessive crown height when the goal is a softer balance."
  details:
    - "Use moderate side movement or soft layers instead of more vertical lift."
    - "Keep top volume controlled."
avoid:
  - "High crown lift as the default."
  - "Very long straight vertical lines with no soft break."
scenario:
  primary: "daily upgrade"
  secondary:
    - "portrait photo"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "barber_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

如果用户已经有明显纵向视觉，继续拉高头顶可能让比例更纵向。starter 策略是控制高度，并在侧向或发尾加入柔和过渡。

## Execution Notes

- Barber brief: "Please keep crown volume natural, not high."
- Use soft side movement if maintenance allows.

## Limitations

- Not applicable when the user intentionally wants taller, sharper styling.
- Needs review with forehead exposure and hair volume.

## Privacy Note

Use only synthetic descriptions in public rule discussion.

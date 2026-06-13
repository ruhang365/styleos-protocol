# SCENARIO-RULE-004

```yaml
rule_id: "SCENARIO-RULE-004"
rule_name: "Photoshoot strategy considers light, background, lens, and upper body"
module: "scenario"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  scenario:
    - "photoshoot"
    - "profile photo"
recommendation:
  summary: "Plan photoshoot styling around lighting, background, lens framing, and upper-body priority."
  details:
    - "Coordinate hair outline, top color, neckline, makeup intensity, and accessories."
avoid:
  - "Planning full styling without knowing lighting or background."
scenario:
  primary: "photoshoot"
confidence_level: "medium"
evidence_type:
  - "heuristic"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "photo_shoot_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

拍摄场景要考虑灯光、背景、镜头和上半身优先级。单独看服装或妆容可能不足。

## Execution Notes

- Use [Photo Shoot Brief Card](../../execution-cards/photo-shoot-brief-card.md).
- Capture lighting, background, top color, neckline, and makeup direction.

## Limitations

- Professional shoot teams may override based on actual setup.
- Test shots are valuable when possible.

## Privacy Note

Do not publish real shoot files or private client references.

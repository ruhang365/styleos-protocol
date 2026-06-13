# COLOR-RULE-001

```yaml
rule_id: "COLOR-RULE-001"
rule_name: "Low contrast should not default to extreme black-white contrast"
module: "color"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "contrast_low"
  scenario:
    - "daily commute"
    - "workday"
recommendation:
  summary: "Start with low-to-medium contrast combinations before using very high contrast near the face."
  details:
    - "Use softer dark-light differences or add a mid-tone bridge."
avoid:
  - "Defaulting to strong black-white contrast near the face."
scenario:
  primary: "daily styling"
confidence_level: "medium"
evidence_type:
  - "heuristic"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "shopping_keyword"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

低对比面部在极强黑白撞色旁边可能被压过。starter 建议先输出柔和对比方向，再按场景测试。

## Execution Notes

- Shopping keywords: "soft contrast", "medium contrast", "neutral mid-tone".

## Limitations

- High-contrast styling can still work for strong personal-brand goals.
- Needs review with makeup, lighting, and scenario.

## Privacy Note

Do not include real user photos or brand purchase records.

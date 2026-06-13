# COLOR-RULE-002

```yaml
rule_id: "COLOR-RULE-002"
rule_name: "Warm tendency and neon cool caution"
module: "color"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "undertone_warm_tendency"
  signals:
    - "user wants large-area cool bright colors"
recommendation:
  summary: "Use neon or highly cool colors cautiously, especially near the face."
  details:
    - "Try warmer neutral bases or small-area cool accents first."
avoid:
  - "Large-area fluorescent cool colors as the default."
scenario:
  primary: "daily styling"
  secondary:
    - "camera"
confidence_level: "low"
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

暖感明显时，荧光冷色可能带来不稳定的近脸效果。可以先降低面积或改为点缀。

## Execution Notes

- Search direction: warm neutral base, small cool accent.

## Limitations

- Not a fixed color identity rule.
- Lighting and makeup can change the result.

## Privacy Note

Use synthetic color examples only.

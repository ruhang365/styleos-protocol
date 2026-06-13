# ACCESSORY-RULE-003

```yaml
rule_id: "ACCESSORY-RULE-003"
rule_name: "Accessory scale should match feature weight and formality"
module: "accessories"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  signals:
    - "user chooses earrings, necklace, bag, or statement accessory"
recommendation:
  summary: "Match accessory visual weight with feature weight and scenario formality."
  details:
    - "Use smaller or cleaner pieces for stable professional settings."
    - "Use one stronger accessory when a memorable creator cue is needed."
avoid:
  - "Large accessories competing with face and outfit in formal settings."
scenario:
  primary: "workday"
  secondary:
    - "content creation"
confidence_level: "low"
evidence_type:
  - "heuristic"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "outfit_styling_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

配饰大小应匹配五官量感和场景正式度。强配饰可以成为记忆点，但需要控制数量和位置。

## Execution Notes

- Brief: accessory visual weight, scenario, one focal point, avoid.

## Limitations

- Personal taste and cultural context matter.
- Accessibility and comfort should be respected.

## Privacy Note

Do not include real jewelry purchase records.

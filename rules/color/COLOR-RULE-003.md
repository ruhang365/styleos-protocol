# COLOR-RULE-003

```yaml
rule_id: "COLOR-RULE-003"
rule_name: "Cool tendency and yellow muddy color caution"
module: "color"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "undertone_cool_tendency"
  signals:
    - "near-face colors look yellow or muddy in test"
recommendation:
  summary: "When cool tendency is present, test overly yellow or muddy colors before using them near the face."
  details:
    - "Try cleaner cool-neutral or balanced muted colors."
avoid:
  - "Large areas of yellow-muddy near-face colors without testing."
scenario:
  primary: "workday"
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

冷感明显时，过黄过浊色可能让整体显得疲惫。该规则只建议谨慎测试，不做绝对排除。

## Execution Notes

- Search direction: cool neutral, clean muted, medium brightness.

## Limitations

- Some yellow-based colors can work as accents or away from face.
- Needs lighting review.

## Privacy Note

Do not post real face color test photos publicly.

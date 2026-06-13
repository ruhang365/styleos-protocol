# ACCESSORY-RULE-001

```yaml
rule_id: "ACCESSORY-RULE-001"
rule_name: "Glasses shape should match line goals"
module: "accessories"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  signals:
    - "user is choosing glasses frames"
  goals:
    - "softer"
    - "sharper"
    - "professional"
recommendation:
  summary: "Choose glasses shape by face-line signal and personal goal, not by trend alone."
  details:
    - "Softer goals may use softer frame corners."
    - "Sharper goals may use clearer frame lines."
avoid:
  - "Selecting frames only because they are popular."
scenario:
  primary: "daily commute"
  secondary:
    - "client meeting"
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

眼镜形状应考虑脸型线条和个人目标。圆框、方框、轻框、重框都可能适合不同场景。

## Execution Notes

- Shopping keywords: frame shape, visual weight, scenario, avoid.

## Limitations

- Prescription, comfort, and fit are practical constraints.
- Try-on is important.

## Privacy Note

Do not post real prescription or face photos publicly.

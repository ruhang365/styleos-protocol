# HAIR-RULE-034

```yaml
rule_id: "HAIR-RULE-034"
rule_name: "Salon return maintenance"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  constraints:
    - "salon return cycle unknown"
  tags:
    - "maintenance_cycle"
recommendation:
  summary: "Match haircut precision and color change to the user's salon return cycle."
  details:
    - "Use forgiving layers and stable length when return intervals are long."
    - "Reserve precise bangs, sharp edges, or high-change color for users who accept upkeep."
avoid:
  - "High-frequency maintenance styles for users who rarely return to salon."
  - "Ignoring visible grow-out or shape collapse."
scenario:
  primary: "risk review"
  secondary:
    - "barber communication"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Some hairstyles depend on periodic trimming or refresh; return cycle affects whether the direction remains usable."
execution_notes: "Add 'expected return cycle' to the barber brief."
limitations: "Salon access, budget, and personal schedule can change."
privacy_note: "Do not publish salon appointment history or payment details."
```

## Explanation

返店周期会决定刘海、短发边缘、颜色和层次是否能稳定维持。v0.2 将返店周期加入约束字段。

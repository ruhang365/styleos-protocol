# HAIR-RULE-026

```yaml
rule_id: "HAIR-RULE-026"
rule_name: "Color direction before exact shade"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "color_direction_needed"
  constraints:
    - "shade uncertainty"
recommendation:
  summary: "Define color direction before naming an exact shade."
  details:
    - "Start with warmth, depth, contrast, brightness, and scenario fit."
    - "Leave exact shade and technique to qualified salon consultation."
avoid:
  - "Giving exact shade formulas in starter content."
  - "Recommending real product brands or salon formulas."
scenario:
  primary: "creator report"
  secondary:
    - "barber communication"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Color direction is safer and more reusable than exact shade instructions in open starter documentation."
execution_notes: "Use fields such as warm/cool, low/high contrast, subtle/visible change."
limitations: "Final color depends on hair condition, prior color, stylist judgment, and salon process."
privacy_note: "Do not include private salon formulas, product purchase records, or user photos."
```

## Explanation

v0.2 只定义发色方向，不给具体色号、品牌或配方。这样能降低误导，也保持开源协议边界。

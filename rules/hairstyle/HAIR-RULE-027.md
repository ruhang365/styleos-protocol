# HAIR-RULE-027

```yaml
rule_id: "HAIR-RULE-027"
rule_name: "High-risk color constraints"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "color_high_change"
  constraints:
    - "workplace constraint"
    - "maintenance constraint"
    - "hair condition constraint"
recommendation:
  summary: "Review work context, maintenance cost, and hair condition before high-change color directions."
  details:
    - "Prefer staged change when the user is uncertain or has formal work constraints."
    - "State refresh effort and visible grow-out risk."
avoid:
  - "Large color shift without maintenance note."
  - "Assuming high-change color fits every work context."
scenario:
  primary: "risk review"
  secondary:
    - "creator service"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "High-change color can affect professional context, upkeep, and hair integrity; starter content should frame it as a risk review."
execution_notes: "Add 'work context', 'maintenance', and 'condition check' fields to the brief."
limitations: "Only a qualified stylist can evaluate technical feasibility and hair condition."
privacy_note: "Do not publish private workplace details, salon records, or hair-condition photos."
```

## Explanation

高变化发色要先做约束检查。公开协议只写方向和风险，不写品牌、配方和具体操作。

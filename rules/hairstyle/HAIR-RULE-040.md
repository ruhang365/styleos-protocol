# HAIR-RULE-040

```yaml
rule_id: "HAIR-RULE-040"
rule_name: "Multiple hairstyle directions"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  constraints:
    - "multiple viable options"
  goals:
    - "goal_decision_support"
recommendation:
  summary: "Offer multiple viable hairstyle directions with tradeoffs instead of one fixed answer."
  details:
    - "Present 2-3 directions when goals or constraints allow multiple paths."
    - "Explain maintenance, risk, scenario fit, and what changes for each path."
avoid:
  - "Claiming one unique direction for every user."
  - "Hiding uncertainty when input is incomplete."
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
explanation: "Hairstyle recommendations are decision support. Multiple directions can be valid when priorities differ."
execution_notes: "Use option cards with benefit, cost, avoid note, and barber brief delta."
limitations: "Too many options can confuse the user; keep the set small and ranked."
privacy_note: "Use synthetic examples and avoid private identity details."
```

## Explanation

发型建议不是唯一答案。v0.2 要求在合适场景下给出 2-3 个方向、取舍和执行差异。

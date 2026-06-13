# HAIR-RULE-020

```yaml
rule_id: "HAIR-RULE-020"
rule_name: "Side part can balance asymmetry without over-covering"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "face_asymmetry_visible"
    - "parting_side"
  goals:
    - "goal_balance_face"
recommendation:
  summary: "Use a side part as a balancing tool while keeping the face open and readable."
  details:
    - "Let the side part soften asymmetry instead of hiding an entire side."
    - "Keep eye area and cheek area from becoming heavily covered."
avoid:
  - "Large hair curtain covering one side of the face."
  - "Explaining asymmetry as a flaw."
scenario:
  primary: "profile photo"
  secondary:
    - "client meeting"
confidence_level: "low"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "A light side part can reduce visual imbalance, while over-covering can look intentional and reduce clarity."
execution_notes: "Use neutral words such as 'balance' and 'open face area' in the barber brief."
limitations: "Asymmetry signals are angle-sensitive and should be reviewed with multiple references."
privacy_note: "Do not store or publish identifiable multi-angle face references."
```

## Explanation

侧分可以帮助平衡，但不是遮住脸的工具。v0.2 规则要求保持脸部开放度，并避免把不对称描述成缺陷。

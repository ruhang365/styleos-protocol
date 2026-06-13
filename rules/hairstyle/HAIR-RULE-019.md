# HAIR-RULE-019

```yaml
rule_id: "HAIR-RULE-019"
rule_name: "Center part is not the default for long hair"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "hair_length_long"
    - "parting_uncertain"
  goals:
    - "goal_look_cleaner"
    - "goal_balance_face"
recommendation:
  summary: "Compare center part, soft side part, and off-center part before treating center part as the baseline."
  details:
    - "Use parting to manage crown support, forehead exposure, and face-side openness."
    - "Select the parting direction that matches the user's goal and maintenance."
avoid:
  - "Using center part as the automatic answer for long hair."
  - "Keeping a flat center part when crown support is low."
scenario:
  primary: "barber communication"
  secondary:
    - "daily upgrade"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Long hair changes greatly with parting, especially when crown support, forehead exposure, or asymmetry signals are present."
execution_notes: "Add a 'parting test' note before cutting face-side layers."
limitations: "Hair growth direction can limit parting options."
privacy_note: "Use synthetic parting examples; do not publish private photos."
```

## Explanation

长发不需要默认中分。分线本身是调节头顶、额头和脸侧开放度的工具，应先试再写进剪发方案。

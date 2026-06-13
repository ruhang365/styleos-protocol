# HAIR-RULE-024

```yaml
rule_id: "HAIR-RULE-024"
rule_name: "Soft curl as softness direction"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "curl_soft"
  goals:
    - "goal_look_softer"
recommendation:
  summary: "Use soft curl as one possible softness direction while checking volume and maintenance."
  details:
    - "Keep curl size, volume position, and daily routine explicit."
    - "Prefer loose movement when the user wants softness but low visual noise."
avoid:
  - "Adding curl without discussing volume expansion."
  - "Suggesting curls when the user cannot maintain the shape."
scenario:
  primary: "style direction"
  secondary:
    - "creator report"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Soft curl can reduce hard edges, but curl also changes volume, upkeep, and silhouette."
execution_notes: "Pair curl direction with maintenance level and fallback straight or wave option."
limitations: "Curl results depend on hair texture, humidity, tools, and stylist technique."
privacy_note: "Do not include private salon formula, product records, or user photos."
```

## Explanation

柔和感可以来自弧度，但卷度会改变发量感和维护成本。v0.2 规则要求同时写体积和维护。

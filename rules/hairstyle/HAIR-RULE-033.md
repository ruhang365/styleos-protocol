# HAIR-RULE-033

```yaml
rule_id: "HAIR-RULE-033"
rule_name: "Daily styling willingness"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  constraints:
    - "daily styling time unknown"
  tags:
    - "maintenance_unknown"
recommendation:
  summary: "Confirm daily styling willingness before recommending shape-dependent haircuts."
  details:
    - "Ask for daily time, tool availability, and tolerance for refresh work."
    - "Use lower-burden options when the answer is unclear."
avoid:
  - "Recommending a style that only works after careful daily styling."
  - "Leaving maintenance cost out of the report."
scenario:
  primary: "intake"
  secondary:
    - "creator service"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "A haircut recommendation is incomplete without knowing whether the user can reproduce it."
execution_notes: "Add a maintenance field to every report and barber brief."
limitations: "User willingness can change for events, travel, or season."
privacy_note: "Do not publish private schedule details or routine logs."
```

## Explanation

每日打理意愿是发型建议的先决条件。没有这个字段，创作者报告容易给出无法复现的方向。

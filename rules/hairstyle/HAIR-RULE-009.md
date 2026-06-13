# HAIR-RULE-009

```yaml
rule_id: "HAIR-RULE-009"
rule_name: "Workplace cleanliness first"
module: "hairstyle"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "scenario_client_meeting"
    - "goal_look_more_professional"
  constraints:
    - "low or medium maintenance"
recommendation:
  summary: "For workplace settings, prioritize clean outline and repeatable maintenance over complex styling."
  details:
    - "Keep flyaway control, stable parting, and manageable length."
    - "Use styling that can be repeated on a normal workday."
avoid:
  - "High-maintenance styling that only works once."
  - "Overly complex layers that the user cannot maintain."
scenario:
  primary: "workday"
  secondary:
    - "client meeting"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "barber_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

职场场景中，持续清爽比一次性的复杂造型更稳定。发型建议应考虑用户每天能否复现。

## Execution Notes

- Ask for "clean, workday repeatable, low maintenance."
- Define daily styling time.

## Limitations

- Creative industries may allow stronger style expression.
- Needs scenario clarification.

## Privacy Note

Do not include employer or private workplace identifiers.

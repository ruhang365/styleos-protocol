# HAIR-RULE-017

```yaml
rule_id: "HAIR-RULE-017"
rule_name: "Low-maintenance complexity filter"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "maintenance_low"
  constraints:
    - "limited daily styling time"
recommendation:
  summary: "Filter out haircut directions that require complex daily styling."
  details:
    - "Prefer stable length, forgiving layers, and simple parting."
    - "State the expected daily effort before recommending curls, precise bangs, or high-shape styling."
avoid:
  - "Describing a high-maintenance look as easy to maintain."
  - "Recommending daily hot-tool styling without a time note."
scenario:
  primary: "creator service"
  secondary:
    - "barber communication"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "A direction that cannot be reproduced by the user becomes a poor service recommendation even if it works in a styled photo."
execution_notes: "Add a maintenance line such as 'daily 5-10 minutes' or 'wash-and-go oriented'."
limitations: "Maintenance tolerance can change by season, job schedule, and tools available."
privacy_note: "Do not publish private routine details unless anonymized and authorized."
```

## Explanation

低维护用户的核心限制是复现成本。建议要先过维护过滤器，再讨论长度、层次、刘海和卷度。

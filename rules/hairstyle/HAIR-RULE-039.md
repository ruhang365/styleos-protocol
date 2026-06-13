# HAIR-RULE-039

```yaml
rule_id: "HAIR-RULE-039"
rule_name: "Barber brief describes goal, keep, adjust, and avoid"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  scenarios:
    - "barber_communication"
  constraints:
    - "haircut execution risk"
recommendation:
  summary: "Use goal, keep, adjust, and avoid fields to make the haircut request actionable."
  details:
    - "Describe desired impression, current constraints, length boundary, layer direction, bangs or parting, volume, and maintenance."
    - "Include what should remain unchanged to reduce unintended changes."
avoid:
  - "Only saying 'trim a little' without boundaries."
  - "Only showing a reference image without explaining the reason."
scenario:
  primary: "barber communication"
  secondary:
    - "creator service"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "A structured brief reduces ambiguity between user, creator, and stylist."
execution_notes: "Use the v0.2 Barber Brief Card and check every required field."
limitations: "The stylist still needs to adjust based on live hair condition and technique."
privacy_note: "Do not publish private consultation notes, photos, real names, contacts, or salon records."
```

## Explanation

理发师沟通卡的价值在于减少歧义。v0.2 要求把目标、保留、调整、避雷和维护写清楚。

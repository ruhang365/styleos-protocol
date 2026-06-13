# HAIR-RULE-012

```yaml
rule_id: "HAIR-RULE-012"
rule_name: "Barber brief over reference-only communication"
module: "hairstyle"
status: "starter / unverified"
version: "0.1.2"
applicable_conditions:
  signals:
    - "user plans to communicate with a hairstylist"
  constraints:
    - "reference images may not match hair attributes or maintenance"
recommendation:
  summary: "Describe goals, constraints, and avoid notes instead of only showing reference images."
  details:
    - "Include desired impression, length boundary, maintenance level, and avoid list."
    - "Use reference keywords, not private or unauthorized images, in public templates."
avoid:
  - "Only giving one internet reference image without explaining why."
  - "Using real user photos in public issues or examples."
scenario:
  primary: "barber communication"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "community starter"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0"
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

理发师沟通卡应该描述目标和避雷。网图只能作为参考，不能替代发质、发量、维护成本和场景说明。

## Execution Notes

- Use [Barber Brief Card](../../execution-cards/barber-brief-card.md).
- Add "keep", "adjust", and "avoid" sections.

## Limitations

- Some stylists still need visual references; use authorized private references only.
- Final cut depends on stylist assessment.

## Privacy Note

Do not upload real reference photos or user photos to public issues.

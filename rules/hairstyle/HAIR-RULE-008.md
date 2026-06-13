# HAIR-RULE-008

```yaml
rule_id: "HAIR-RULE-008"
rule_name: "Sharp features with soft layers"
module: "hairstyle"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "feature_weight_sharp"
    - "goal_look_softer"
  signals:
    - "user wants lower distance or softer impression"
recommendation:
  summary: "Use soft layers or natural movement to reduce overly hard visual edges."
  details:
    - "Keep structure where needed, but soften face-adjacent lines."
    - "Use gentle curvature if maintenance allows."
avoid:
  - "All-hard straight lines near the face."
  - "Very sharp angles when the target is softer."
scenario:
  primary: "client meeting"
  secondary:
    - "date"
confidence_level: "low"
evidence_type:
  - "heuristic"
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

五官锐度高并不是问题；当目标是亲和或柔和时，可通过柔和层次降低线条的紧张感。

## Execution Notes

- Brief: "Keep the haircut clean, but soften the lines around the face."
- Avoid language that labels sharpness negatively.

## Limitations

- If the target is strong personal brand, sharpness may be useful.
- Needs review with outfit and makeup choices.

## Privacy Note

Use synthetic feature descriptions only in public examples.

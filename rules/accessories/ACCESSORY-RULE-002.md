# ACCESSORY-RULE-002

```yaml
rule_id: "ACCESSORY-RULE-002"
rule_name: "Hat advice must consider face, hair, and scenario"
module: "accessories"
status: "starter / unverified"
version: "0.1.2"
applicable_conditions:
  signals:
    - "user wants hat recommendation"
recommendation:
  summary: "Consider face-shape signal, hair volume, hat crown, brim, and scenario together."
  details:
    - "Hat brim and crown can change face proportion and hair volume impression."
avoid:
  - "Recommending hats by face shape alone."
scenario:
  primary: "daily commute"
  secondary:
    - "photoshoot"
confidence_level: "low"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "shopping_keyword"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

帽子建议必须考虑脸型、发量和场景。帽檐、帽顶高度和发型体积会一起影响最终观感。

## Execution Notes

- Shopping keywords: brim width, crown height, hair volume compatibility.

## Limitations

- Head size, comfort, weather, and dress code matter.
- Try-on is recommended.

## Privacy Note

Do not include real head measurements in public issues.

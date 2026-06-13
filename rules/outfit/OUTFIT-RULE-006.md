# OUTFIT-RULE-006

```yaml
rule_id: "OUTFIT-RULE-006"
rule_name: "Outfit advice must separate scenarios"
module: "outfit"
status: "starter / unverified"
version: "0.1.2"
applicable_conditions:
  signals:
    - "one outfit advice is being used across work, date, content, and commute"
recommendation:
  summary: "Separate outfit advice by work, date, content appearance, and daily commute scenarios."
  details:
    - "Define the target scenario before recommending silhouette, color, and formality."
avoid:
  - "One universal outfit rule for all scenarios."
scenario:
  primary: "multi-scenario planning"
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
execution_card_type: "outfit_styling_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

穿搭建议必须区分工作、约会、内容出镜和日常通勤。同一个人可以有多个场景策略。

## Execution Notes

- Add `scenario` as the first field in outfit briefs.

## Limitations

- Capsule wardrobes can still unify some pieces across scenarios.
- Needs user priority ranking.

## Privacy Note

Do not reveal private events or exact locations.

# SCENARIO-RULE-001

```yaml
rule_id: "SCENARIO-RULE-001"
rule_name: "Same person can use different image strategies"
module: "scenario"
status: "starter / unverified"
version: "0.1.2"
applicable_conditions:
  signals:
    - "user has multiple styling contexts"
recommendation:
  summary: "Define separate strategies for different scenarios instead of forcing one universal style."
  details:
    - "Work, date, commute, content, and public speaking may need different priorities."
avoid:
  - "Treating one style direction as the only correct identity."
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

同一个人不同场景可以有不同形象策略。StyleOS 不应把用户固定成单一风格身份。

## Execution Notes

- Start every report by naming primary and secondary scenarios.

## Limitations

- Too many scenarios at once can make advice vague.
- Ask the user to rank top priorities.

## Privacy Note

Do not include real event details that identify a person.

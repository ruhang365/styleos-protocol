# COLOR-RULE-006

```yaml
rule_id: "COLOR-RULE-006"
rule_name: "Color direction before product color codes"
module: "color"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  signals:
    - "user asks for exact color or product code before direction is clear"
recommendation:
  summary: "Output color direction first, then optional product or shade references in private service contexts."
  details:
    - "Use dimensions such as temperature, brightness, saturation, and contrast."
avoid:
  - "Forcing exact brand shade codes at the start."
  - "Publicly recommending real product purchases as protocol examples."
scenario:
  primary: "color consultation"
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
execution_card_type: "shopping_keyword"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

色彩建议应先给方向：冷暖、明度、饱和度、对比度和场景。具体色号容易受品牌、光线和库存影响。

## Execution Notes

- Shopping keyword card should contain color direction, not required brand codes.

## Limitations

- Paid private services may later include specific shopping support.
- Exact colors require real-world testing.

## Privacy Note

Do not include real purchase histories or private shopping accounts.

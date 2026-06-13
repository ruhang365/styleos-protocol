# MAKEUP-RULE-004

```yaml
rule_id: "MAKEUP-RULE-004"
rule_name: "Makeup color direction before products"
module: "makeup"
status: "starter / unverified"
version: "0.1.2"
applicable_conditions:
  signals:
    - "user asks for specific products before direction is defined"
recommendation:
  summary: "Separate makeup color direction from specific product recommendations."
  details:
    - "Define warm, cool, neutral, soft, clear, daily, or camera direction first."
avoid:
  - "Starting with brand or product names as the protocol output."
scenario:
  primary: "makeup planning"
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
execution_card_type: "makeup_artist_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

妆容建议应区分“颜色方向”和“具体产品”。产品受肤质、预算、库存和偏好影响，不适合写成开放协议默认内容。

## Execution Notes

- Brief: lip color direction, cheek direction, eye emphasis, avoid.

## Limitations

- Private paid services may include product suggestions under separate terms.
- Patch testing and allergies are outside protocol scope.

## Privacy Note

Do not include private purchase histories or skin photos.

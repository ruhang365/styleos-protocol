# COLOR-RULE-005

```yaml
rule_id: "COLOR-RULE-005"
rule_name: "Camera scenario top color priority"
module: "color"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "scenario_color_camera_friendly"
  scenario:
    - "content creation"
    - "live streaming"
    - "photoshoot"
recommendation:
  summary: "Prioritize upper-body and near-face colors for camera scenarios."
  details:
    - "Top color usually affects face impression more than bottom color on camera."
avoid:
  - "Only optimizing pants or shoes while ignoring the top near the face."
scenario:
  primary: "camera"
confidence_level: "medium"
evidence_type:
  - "heuristic"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "photo_shoot_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

镜头场景里，上衣、领口和近脸色对观感影响更直接。色彩建议应先处理上半身。

## Execution Notes

- Photo shoot brief: specify top color, background color, and lighting context.

## Limitations

- Full-body shots still require whole outfit review.
- Lighting and background can shift color perception.

## Privacy Note

Do not include private platform account identifiers.

# MAKEUP-RULE-003

```yaml
rule_id: "MAKEUP-RULE-003"
rule_name: "Camera makeup must account for lighting"
module: "makeup"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "makeup_camera_look"
  scenario:
    - "content creation"
    - "photoshoot"
    - "live streaming"
recommendation:
  summary: "Camera makeup should consider lighting, lens softness, and color loss."
  details:
    - "Increase definition only as much as the lighting requires."
    - "Coordinate makeup with top color and background."
avoid:
  - "Using daily makeup intensity unchanged under strong lights."
  - "Overcorrecting without testing lighting."
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

镜头妆面需要考虑光线吃妆。日常看足够的妆面，在强光或镜头中可能变弱；但也不应盲目加重。

## Execution Notes

- Photo shoot brief: lighting context, skin finish, brow/eye definition, lip direction.

## Limitations

- Camera, lens, and post-processing can change results.
- Needs test shot when possible.

## Privacy Note

Do not post real unedited photos publicly.

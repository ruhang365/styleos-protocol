# Hairstyle Input Schema

This schema defines hairstyle module input fields. It does not store real photos.

中文说明：
本文件只定义发型咨询字段结构。公开仓库不要提交真实照片、可识别个人身份信息或未经授权案例。

## Object: `styleos_hairstyle_input`

```yaml
schema_version: "0.2"
profile_id: "synthetic-hairstyle-profile-001"
profile_type: "synthetic"
basic_profile:
  age_range: "25-34"
  gender_expression: "optional self-description"
  daily_context: "office / school / creator / service / other"
target_scenario:
  primary: "client meeting"
  secondary:
    - "daily commute"
current_hairstyle_description:
  length: "shoulder-length"
  bangs: "no bangs"
  parting: "center-part"
  color_direction: "natural black / near black"
face_shape_tag: "face_shape_square"
face_proportion_tags:
  - "lower_face_proportion_visible"
  - "face_width_impression_medium"
jawline_cheekbone_forehead_signals:
  jawline: "strong_jawline"
  cheekbone: "mixed_uncertain"
  forehead: "balanced_forehead"
hair_attributes:
  hair_volume: "hair_volume_medium"
  hair_texture: "hair_texture_medium"
  hair_shape: "hair_shape_straight"
  hairline_visibility: "hairline_partially_covered"
  forehead_exposure: "forehead_exposure_medium"
  crown_height: "crown_height_medium"
maintenance:
  maintenance_willingness: "maintenance_medium"
  daily_styling_time: "5-10 minutes"
willingness:
  cut_short: "medium"
  perm: "low"
  color: "low"
constraints:
  workplace_or_school: "client-facing, conservative"
  no_coloring: true
  no_short_cut: false
styling_goals:
  - "goal_look_softer"
  - "goal_look_more_professional"
risk_tolerance: "haircut_risk_medium"
creator_notes:
  assumptions:
    - "Synthetic example only."
  manual_review_required: true
```

## Field Notes

- `basic_profile`: broad context only, not identity verification.
- `target_scenario`: where the hairstyle needs to work.
- `current_hairstyle_description`: text description, not a photo upload.
- `face_shape_tag`: starter tag for contour tendency.
- `face_proportion_tags`: proportion signals that may influence length, bangs, and volume.
- `jawline_cheekbone_forehead_signals`: local visual signals for rule selection.
- `hair_attributes`: volume, texture, shape, hairline, forehead exposure, and crown height.
- `maintenance`: daily styling time and upkeep willingness.
- `willingness`: whether the user accepts cutting short, perming, or coloring.
- `constraints`: workplace, school, budget, hair condition, and user boundaries.
- `creator_notes`: assumptions, follow-up questions, and manual review notes.

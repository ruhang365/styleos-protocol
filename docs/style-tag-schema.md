# Style Tag Schema

The Style Tag Schema defines shared labels for describing styling inputs, diagnosis, recommendations, and rule-card conditions.

中文说明：
标签体系用于统一描述面部、比例、发型、色彩、穿搭、妆容和场景信号，方便创作者和开发者复用经验。

## Tag Object

```yaml
tag_id: "face_shape_soft_oval"
tag_group: "face_shape"
display_name: "Soft Oval"
cn_name: "柔和鹅蛋脸"
description: "Synthetic protocol tag for a soft oval face-shape tendency."
status: "draft"
```

## Tag Groups

### Face Shape

Suggested values:

- `face_shape_oval`
- `face_shape_round`
- `face_shape_square`
- `face_shape_long`
- `face_shape_heart`
- `face_shape_diamond`
- `face_shape_mixed`
- `face_shape_uncertain`

### Facial Proportion

Suggested values:

- `proportion_balanced`
- `proportion_upper_face_dominant`
- `proportion_mid_face_dominant`
- `proportion_lower_face_dominant`
- `proportion_short_midface`
- `proportion_long_midface`
- `proportion_uncertain`

### Facial Feature Weight

Suggested values:

- `feature_weight_light`
- `feature_weight_medium`
- `feature_weight_strong`
- `feature_weight_sharp`
- `feature_weight_soft`
- `feature_weight_mixed`
- `feature_weight_uncertain`

### Hairstyle

Suggested values:

- `hairstyle_short`
- `hairstyle_medium`
- `hairstyle_long`
- `hairstyle_layered`
- `hairstyle_soft_wave`
- `hairstyle_straight`
- `hairstyle_volume_crown`
- `hairstyle_face_framing`
- `hairstyle_low_maintenance`
- `hairstyle_avoid_heavy_bangs`

v0.2 hairstyle extension groups:

- `haircut_shape`: `haircut_bob_soft`, `haircut_lob`, `haircut_layered_medium`, `haircut_pixie_soft`, `haircut_long_layer`
- `hair_length`: `hair_length_chin`, `hair_length_shoulder`, `hair_length_collarbone`, `hair_length_long`
- `bangs`: `bangs_none`, `bangs_light`, `bangs_side`, `bangs_curtain`, `bangs_full_heavy`
- `layer_volume`: `layer_face_framing`, `layer_low`, `layer_weight_control`, `volume_crown_support`, `volume_side_reduce`
- `curl_perm`: `curl_none`, `curl_soft_wave`, `curl_structured`, `curl_natural`, `curl_uncertain`
- `maintenance`: `maintenance_low`, `maintenance_medium`, `maintenance_high`, `salon_return_long`
- `constraints`: `constraint_workplace`, `constraint_pre_shoot`, `constraint_glasses`, `constraint_low_risk`, `constraint_color_caution`

See [Hairstyle Module](../modules/hairstyle/README.md) for the full v0.2 starter taxonomy.

### Color Direction

Suggested values:

- `color_warm_soft`
- `color_warm_clear`
- `color_cool_soft`
- `color_cool_clear`
- `color_neutral`
- `color_low_contrast`
- `color_medium_contrast`
- `color_high_contrast`
- `color_work_safe`
- `color_statement_accent`

### Outfit Direction

Suggested values:

- `outfit_clean_basic`
- `outfit_business_casual`
- `outfit_soft_feminine`
- `outfit_minimal`
- `outfit_smart_casual`
- `outfit_structured`
- `outfit_relaxed`
- `outfit_social_media_ready`
- `outfit_event_ready`

### Makeup Direction

Suggested values:

- `makeup_no_makeup`
- `makeup_clean_base`
- `makeup_soft_definition`
- `makeup_warm_daily`
- `makeup_cool_daily`
- `makeup_event_polished`
- `makeup_camera_ready`
- `makeup_low_maintenance`

### Scenario

Suggested values:

- `scenario_workday`
- `scenario_interview`
- `scenario_dating`
- `scenario_wedding_guest`
- `scenario_social_profile`
- `scenario_live_stream`
- `scenario_photo_session`
- `scenario_daily_upgrade`
- `scenario_creator_content`

### Creator-Specific Tags

Creators may define extension tags when the shared taxonomy is not enough.

Recommended format:

```yaml
tag_id: "creator_example_soft_commute"
tag_group: "creator_specific"
namespace: "creator_example"
display_name: "Soft Commute"
cn_name: "柔和通勤"
description: "A creator-defined styling direction for low-maintenance commute looks."
status: "experimental"
```

## Tag Status

- `draft`: proposed tag.
- `active`: accepted for current protocol use.
- `deprecated`: no longer recommended.
- `experimental`: creator-specific or under review.

## Compatibility Rule

Compatible tools should preserve unknown tags instead of deleting them, so creator-specific extensions can travel through workflows without breaking the core schema.

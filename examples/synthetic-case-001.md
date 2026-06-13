# Synthetic Case 001

This is a synthetic example. It does not describe a real person.

中文说明：
这是合成案例，不包含真实用户照片、真实姓名、真实联系方式或真实隐私数据。

## Input Profile

```yaml
schema_version: "0.1"
profile_id: "synthetic-profile-001"
profile_type: "synthetic"
basic_profile:
  age_range: "25-34"
  gender_expression: "optional feminine styling preference"
  occupation_context: "office worker"
  location_context: "large city, broad context only"
target_scenario:
  primary_scenario: "scenario_workday"
  secondary_scenarios:
    - "scenario_social_profile"
  urgency: "normal"
photos_metadata:
  photo_submitted: false
  photo_type:
    - "metadata only"
  lighting_quality: "unknown"
  permission_status: "not_applicable_for_synthetic_case"
styling_goals:
  desired_impression:
    - "clean"
    - "approachable"
    - "more polished"
  priority_modules:
    - "hairstyle"
    - "outfit"
  change_level: "moderate"
constraints:
  hair_length_limit: "keep medium length"
  workplace_constraints: "business casual"
  maintenance_level: "low"
  avoid:
    - "high-maintenance daily styling"
budget:
  currency: "CNY"
  range: "500-1500"
  flexibility: "medium"
creator_notes:
  notes: "Synthetic demonstration case for StyleOS Protocol v0.1."
  assumptions:
    - "No real photos were used."
    - "Tags are illustrative and require manual review in real service."
```

## Candidate Tags

- `face_shape_round`
- `feature_weight_soft`
- `hairstyle_face_framing`
- `hairstyle_low_maintenance`
- `color_neutral`
- `outfit_business_casual`
- `scenario_workday`
- `scenario_social_profile`

## Candidate Rule Cards

- `rule-synthetic-hairstyle-001`
- `rule-synthetic-outfit-001`

## Privacy Status

- Synthetic: yes
- Real photos: no
- Real name: no
- Contact information: no
- Authorized real case: not applicable

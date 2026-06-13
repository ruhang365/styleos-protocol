# Input Schema

The Input Schema defines the structured information a creator or compatible tool may collect before producing StyleOS-compatible tags, rule cards, or lite reports.

This schema describes fields only. Do not include real photos or personal data in this repository.

中文说明：
本文件只定义字段结构，不接收真实照片、真实姓名、联系方式或未经授权的案例。

## Object: `styleos_input_profile`

```yaml
schema_version: "0.1"
profile_id: "synthetic-profile-001"
profile_type: "synthetic"
basic_profile:
  age_range: "25-34"
  gender_expression: "optional self-description"
  occupation_context: "office / creative / student / service / other"
  location_context: "optional broad region only"
target_scenario:
  primary_scenario: "workday"
  secondary_scenarios:
    - "dating"
    - "social media profile"
  urgency: "normal"
photos_metadata:
  photo_submitted: false
  photo_type:
    - "front-facing reference"
    - "side reference"
  lighting_quality: "unknown"
  permission_status: "not_applicable_for_synthetic_case"
styling_goals:
  desired_impression:
    - "clean"
    - "approachable"
  priority_modules:
    - "hairstyle"
    - "outfit"
  change_level: "moderate"
constraints:
  hair_length_limit: "keep current length"
  workplace_constraints: "business casual"
  comfort_constraints:
    - "low maintenance"
  avoid:
    - "high-maintenance styling"
budget:
  currency: "CNY"
  range: "500-1500"
  flexibility: "medium"
creator_notes:
  notes: "Synthetic notes for protocol demonstration only."
  assumptions:
    - "No real photos were used."
```

## Field Groups

### Basic Profile

Basic Profile provides broad context without identifying a real person.

Recommended fields:

- `age_range`: broad age range, such as `18-24`, `25-34`, `35-44`.
- `gender_expression`: optional self-description.
- `occupation_context`: broad work or lifestyle context.
- `location_context`: broad region only; do not include exact address.

### Target Scenario

Target Scenario defines where the styling advice will be used.

Recommended fields:

- `primary_scenario`: main use case.
- `secondary_scenarios`: optional additional scenarios.
- `urgency`: `low`, `normal`, or `high`.
- `event_date_type`: optional, such as `no_fixed_date`, `within_30_days`, or `future_event`.

### Photos Metadata

Photos Metadata describes photo availability and quality without storing photos.

Recommended fields:

- `photo_submitted`: boolean.
- `photo_type`: metadata only.
- `lighting_quality`: `good`, `mixed`, `poor`, or `unknown`.
- `angle_quality`: `front`, `side`, `mixed`, or `unknown`.
- `permission_status`: `synthetic`, `authorized`, `not_authorized`, or `not_applicable`.

Do not place image URLs, file paths, or real photo descriptions in public examples.

### Styling Goals

Styling Goals describe intended outcomes.

Recommended fields:

- `desired_impression`: array of desired impressions.
- `priority_modules`: `hairstyle`, `color`, `outfit`, `makeup`, or `complete`.
- `change_level`: `minimal`, `moderate`, or `bold`.
- `reference_preference`: synthetic or generic references only.

### Constraints

Constraints describe practical limitations.

Recommended fields:

- `hair_length_limit`
- `workplace_constraints`
- `maintenance_level`
- `comfort_constraints`
- `cultural_or_event_constraints`
- `avoid`

### Budget

Budget defines commercial and practical boundaries.

Recommended fields:

- `currency`
- `range`
- `flexibility`
- `priority_spend`

### Creator Notes

Creator Notes capture professional judgment and assumptions.

Recommended fields:

- `notes`
- `assumptions`
- `manual_review_required`
- `follow_up_questions`

## Privacy Requirements

- Use synthetic profile IDs in examples.
- Do not include real names, contacts, photos, or exact locations.
- Do not include private messages.
- Real cases must be authorized and fully anonymized before being shared outside a private service workflow.

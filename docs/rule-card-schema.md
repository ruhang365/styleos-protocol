# Rule Card Schema

Rule Cards are reusable units of styling logic.

中文说明：
Rule Card 用来把创作者经验结构化：什么条件下适用、建议什么、避免什么、适合什么场景、可信度如何。

## Object: `styleos_rule_card`

```yaml
rule_id: "rule-synthetic-hairstyle-001"
rule_name: "Soft face framing for round-soft face tendency"
applicable_conditions:
  tags:
    - "face_shape_round"
    - "feature_weight_soft"
  scenario:
    - "scenario_workday"
    - "scenario_social_profile"
  constraints:
    - "low maintenance"
recommendation:
  summary: "Use soft face-framing layers and moderate crown volume."
  details:
    - "Keep the outline light around the cheek area."
    - "Use moderate crown lift to lengthen the visual proportion."
avoid:
  - "Heavy straight bangs that shorten the face."
  - "Flat roots with wide side volume."
scenario:
  primary: "daily upgrade"
  secondary:
    - "social profile"
confidence_level: "medium"
evidence_type:
  - "creator_experience"
  - "synthetic_example"
source_type: "synthetic"
contributor:
  name: "StyleOS Maintainers"
  url: ""
status: "draft"
```

## Required Fields

### `rule_id`

Stable unique identifier.

Recommended format:

- `rule-[module]-[short-topic]-[number]`
- Example: `rule-hairstyle-face-framing-001`

### `rule_name`

Human-readable name that explains the rule.

### `applicable_conditions`

Conditions under which the rule may apply.

Recommended subfields:

- `tags`
- `scenario`
- `constraints`
- `budget`
- `change_level`

### `recommendation`

Concrete styling advice.

Recommended subfields:

- `summary`
- `details`
- `execution_notes`
- `related_tags`

### `avoid`

List of choices that may reduce fit, clarity, comfort, or scenario match.

### `scenario`

Target service or life scenario.

Recommended subfields:

- `primary`
- `secondary`

### `confidence_level`

Allowed values:

- `low`
- `medium`
- `high`

### `evidence_type`

Allowed values:

- `synthetic_example`
- `creator_experience`
- `community_feedback`
- `expert_review`
- `anonymized_case`

### `source_type`

Allowed values:

- `synthetic`
- `abstracted_creator_practice`
- `fully_anonymized_authorized_case`
- `expert_reviewed`

### `contributor`

Contributor information. Do not include private contact details.

Recommended subfields:

- `name`
- `profile_url`
- `organization`

### `status`

Allowed values:

- `draft`
- `under_review`
- `accepted`
- `deprecated`

## Review Notes

Rule Cards should be practical, narrow enough to apply, and safe for creators to explain manually. Avoid overclaiming, medical claims, or deterministic judgments based on limited inputs.

# Rule Card Schema

Rule Cards are reusable units of styling logic.

中文说明：
Rule Card 用来把创作者经验结构化：什么条件下适用、建议什么、避免什么、适合什么场景、可信度如何。

## Object: `styleos_rule_card`

```yaml
rule_id: "rule-synthetic-hairstyle-001"
rule_name: "Soft face framing for round-soft face tendency"
module: "hairstyle"
version: "0.1.1"
status: "starter / unverified"
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
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "barber_brief"
```

## Required Fields

### `rule_id`

Stable unique identifier.

Recommended format:

- `rule-[module]-[short-topic]-[number]`
- Example: `rule-hairstyle-face-framing-001`

### `rule_name`

Human-readable name that explains the rule.

### `module`

Module that owns the rule.

Allowed starter values:

- `hairstyle`
- `color`
- `outfit`
- `makeup`
- `accessories`
- `scenario`

### `version`

Protocol or seed-pack version that introduced or last updated the rule.

Example: `0.1.1`

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

For v0.1.1 seed rules, use:

- `starter / unverified`

### `evidence_level`

Evidence support level.

Recommended values are defined in [Evidence Levels](../validation/evidence-levels.md):

- `E0 Synthetic starter rule`
- `E1 Community submitted rule`
- `E2 Repeated creator observation`
- `E3 Expert reviewed rule`
- `E4 Data-validated rule`
- `E5 Pro model validated pattern`

### `review_status`

Review lifecycle status.

Recommended values are defined in [Rule Status](../validation/rule-status.md):

- `starter`
- `community-submitted`
- `under-review`
- `expert-reviewed`
- `data-supported`
- `deprecated`
- `pro-only`

### `pro_candidate`

Boolean value indicating whether the rule may be considered for future Pro library review.

This does not mean the rule is already Pro, certified, or commercially validated.

### `privacy_risk`

Privacy risk level for contribution or public examples.

Suggested values:

- `low`
- `medium`
- `high`

Rules that require real photos, private service records, or sensitive attributes should not be accepted as public examples without authorization and anonymization.

### `execution_card_type`

Execution card that can turn the rule into an actionable brief.

Suggested values:

- `barber_brief`
- `shopping_keyword`
- `makeup_artist_brief`
- `outfit_styling_brief`
- `photo_shoot_brief`
- `none`

## Review Notes

Rule Cards should be practical, narrow enough to apply, and safe for creators to explain manually. Avoid overclaiming, medical claims, or deterministic judgments based on limited inputs.

Seed rules should also avoid appearance-shaming, body-shaming, gender stereotypes, absolute claims, real-person examples, real brand recommendations, and medical or cosmetic surgery advice.

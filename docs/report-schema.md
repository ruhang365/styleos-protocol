# Report Schema

The Lite Report Schema defines the output structure for creator-delivered StyleOS reports.

中文说明：
Lite Report 是创作者交付给粉丝或客户的轻量报告结构，重点是清晰、可执行、可复盘，而不是自动化取代人工判断。

## Object: `styleos_lite_report`

```yaml
report_id: "synthetic-report-lite-001"
schema_version: "0.1"
profile_ref: "synthetic-profile-001"
summary:
  one_line: "A clean, approachable daily-work style direction with soft structure."
  change_level: "moderate"
style_keywords:
  - "clean"
  - "approachable"
  - "soft structure"
diagnosis_tags:
  face_shape:
    - "face_shape_round"
  facial_feature_weight:
    - "feature_weight_soft"
  scenario:
    - "scenario_workday"
recommendations:
  hairstyle:
    - "Use soft face-framing layers."
  color:
    - "Use neutral-to-warm soft colors near the face."
  outfit:
    - "Choose clean business-casual lines with moderate structure."
  makeup:
    - "Keep base clean and add soft definition."
avoid_list:
  - "Avoid heavy straight bangs."
  - "Avoid overly loose outfits with no shape."
creator_notes:
  - "Synthetic report for protocol demonstration only."
execution_card:
  first_step: "Adjust hairstyle outline before changing full wardrobe."
  shopping_notes:
    - "Start with one structured jacket."
next_action_checklist:
  - "Confirm comfort constraints."
  - "Review one mirror photo privately with the creator."
```

## Sections

### Summary

Short conclusion of the report.

Recommended fields:

- `one_line`
- `change_level`
- `primary_direction`
- `manual_review_note`

### Style Keywords

Three to seven words that summarize the styling direction.

### Diagnosis Tags

StyleOS tags used to support the report.

Recommended groups:

- `face_shape`
- `facial_proportion`
- `facial_feature_weight`
- `hairstyle`
- `color_direction`
- `outfit_direction`
- `makeup_direction`
- `scenario`

### Recommendations

Actionable advice grouped by module.

Recommended modules:

- `hairstyle`
- `color`
- `outfit`
- `makeup`
- `photo_or_content`

### Avoid List

Specific items to avoid, with short reasons when useful.

### Creator Notes

Manual review notes, assumptions, and service boundary.

### Execution Card

Small action plan that helps the user execute.

Recommended fields:

- `first_step`
- `within_7_days`
- `shopping_notes`
- `styling_notes`
- `review_method`

### Next Action Checklist

Checklist for follow-up, feedback, or next service step.

## Safety Requirements

- Do not include real photos.
- Do not include personal contact information.
- Do not make medical, psychological, or identity claims.
- Do not present low-confidence tags as certain facts.
- Make clear when the report is based on synthetic or incomplete inputs.

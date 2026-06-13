# Hairstyle Creator Workflow

Version: 0.2

This workflow connects intake, tags, rules, report writing, barber brief, and feedback.

中文说明：
这是发型创作者工作流，用于把 StyleOS Protocol v0.2 转成服务步骤。它不替代专业理发师判断。

## Step 1: Collect Intake

Use [Hairstyle Intake Form](./hairstyle-intake-form.md).

Minimum fields:

- target scenario
- current length
- hair volume
- hair texture
- maintenance willingness
- primary goal
- avoid list

## Step 2: Assign Tags

Use:

- [Hairstyle Input Schema](../modules/hairstyle/hairstyle-input-schema.md)
- [Hair Attribute Tags](../modules/hairstyle/hair-attribute-tags.md)
- [Face Proportion Tags](../modules/hairstyle/face-proportion-tags.md)
- [Maintenance Tags](../modules/hairstyle/maintenance-tags.md)
- [Constraints Tags](../modules/hairstyle/constraints-tags.md)

Mark uncertain inputs instead of forcing a confident label.

## Step 3: Select Rules

Use:

- [Hairstyle Rule Index](../modules/hairstyle/hairstyle-rule-index.md)
- [Hairstyle Mapping Matrix](../modules/hairstyle/hairstyle-mapping-matrix.md)

Select 2-5 rules. More rules can make the report harder to act on.

## Step 4: Draft Report

Use [Hairstyle Lite Report Template](./hairstyle-lite-report-template.md).

Output should include:

- input summary
- selected tags
- rule references
- 1-2 directions
- tradeoff note
- maintenance note
- barber brief draft

## Step 5: Build Barber Brief

Use:

- [Barber Brief Schema](../modules/hairstyle/barber-brief-schema.md)
- [Barber Brief Card](../execution-cards/barber-brief-card.md)

Include `keep`, `adjust`, and `avoid`. Do not only provide a reference image.

## Step 6: Review Quality

Use:

- [Hairstyle Quality Checklist](../modules/hairstyle/quality-checklist.md)
- [Hairstyle Review Checklist](../validation/hairstyle-review-checklist.md)

Reject output that uses shaming language, fixed promises, or private examples.

## Step 7: Collect Feedback

Use [Hairstyle Feedback Form](../validation/hairstyle-feedback-form.md).

Feedback should capture clarity, actionability, maintenance fit, and stylist communication risk.

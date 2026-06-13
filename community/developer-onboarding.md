# Developer Onboarding

This page helps developers understand how to build around StyleOS Protocol.

## Protocol

StyleOS is a documentation-first open protocol. It defines reusable formats for personal styling workflows rather than shipping an app in this repository.

Start with:

- [Input Schema](../docs/input-schema.md)
- [Style Tag Schema](../docs/style-tag-schema.md)
- [Rule Card Schema](../docs/rule-card-schema.md)
- [Report Schema](../docs/report-schema.md)
- [Evaluation Framework](../docs/evaluation-framework.md)

## Schema

Compatible tools should preserve:

- unknown tags
- evidence levels
- rule status
- limitations
- privacy notes
- creator notes
- open-core boundary metadata

## Rule Card

Rule cards express reusable logic:

- applicable conditions
- recommendation
- avoid list
- scenario
- confidence level
- evidence type
- source type
- limitations

Do not treat starter rules as verified model truth.

## Report Schema

Lite reports are creator-facing outputs. AI tools can draft them, but creator review should remain visible.

Recommended tool flow:

1. collect intake
2. assign tags
3. select rule cards
4. draft report
5. build execution card
6. run validation checklist
7. collect feedback

## Future API Draft

Future hosted products may expose APIs for:

- intake submission
- tag suggestions
- rule-card retrieval
- report draft generation
- feedback submission
- creator workspace sync

This repository does not include hosted API code or runtime services.

## Open-Core Boundary

Open:

- protocol documents
- schemas
- starter rules
- synthetic examples
- templates

Commercial or future hosted:

- StyleOS Cloud
- StyleOS Pro
- expert-reviewed libraries
- verified case databases
- certification workflows
- hosted dashboards
- advanced model tools

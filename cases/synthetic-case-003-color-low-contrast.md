# Synthetic Case 003: Color Low Contrast

## Case ID

`SYNTH-CASE-003`

## Synthetic Disclaimer

This is a synthetic case. It contains no real photo, real color test, or real person.

## User Profile

- Age range: 25-34
- Context: daily work and occasional content photos
- Color preference: calm neutrals
- Shopping goal: build stable tops

## Target Scenario

- Primary: daily commute
- Secondary: camera-friendly profile updates

## Input Tags

- `contrast_low`
- `brightness_medium`
- `saturation_muted`
- `scenario_color_work_stable`

## Key Concerns

- High black-white outfits feel visually strong.
- Wants stable colors near the face.
- Does not want exact product colors yet.

## Selected Rule Cards

- [COLOR-RULE-001](../rules/color/COLOR-RULE-001.md)
- [COLOR-RULE-006](../rules/color/COLOR-RULE-006.md)

## Lite Recommendation

Start with low-to-medium contrast near-face colors. Use soft neutrals or mid-tone combinations before testing very high contrast. Output color direction first, not exact product codes.

## Execution Card

Use [Shopping Keyword Card](../execution-cards/shopping-keyword-card.md).

```yaml
color_direction:
  - "soft neutral"
  - "medium brightness"
  - "low-to-medium contrast"
silhouette:
  - "clean basic top"
fabric:
  - "medium weight"
scenario:
  - "daily commute"
  - "profile photo"
avoid_keywords:
  - "extreme black-white contrast"
  - "large neon blocks"
```

## Feedback Placeholder

- Did search keywords return usable options?
- Did near-face color feel stable in private test photos?

## Privacy Note

No real color analysis photos, purchase history, or account data is included.

# Barber Brief Card

Version: 0.2

This card helps users communicate hairstyle goals to a hairstylist.

中文说明：
这张卡可以给理发师看，用来说明目标、场景、保留项、调整项、避雷和维护成本。它不是只给网图，也不是专家诊断。

## Short Version

```yaml
execution_card_type: "barber_brief"
version: "0.2"
goal: ""
scenario: ""
keep:
  - ""
adjust:
  - ""
avoid:
  - ""
maintenance_level: "low / medium / high"
creator_note: "Starter / unverified StyleOS brief."
```

## Detailed Version

```yaml
execution_card_type: "barber_brief"
version: "0.2"
goal: ""
scenario: ""
current_concern: ""
hair_signals:
  length: ""
  volume: ""
  texture: ""
  natural_shape: ""
  crown_support: ""
face_proportion_signals:
  forehead: ""
  cheekbone: ""
  jawline: ""
  uncertainty: ""
keep:
  - ""
adjust:
  - ""
avoid:
  - ""
length_boundary: ""
layer_direction: ""
bangs_parting_direction: ""
volume_direction: ""
color_direction: ""
maintenance:
  daily_time: ""
  salon_return_cycle: ""
  tool_tolerance: ""
reference_keywords:
  - ""
creator_note: ""
privacy_note: "Do not publish identifiable photos, names, contacts, or private service notes."
```

## Field Notes

- Goal: 想达到的整体方向，如 cleaner、softer、professional、creator memory cue。
- Scenario: 日常、客户会议、拍摄、直播、个人 IP 等。
- Keep: 明确不想改变的长度、颜色、分线或维护方式。
- Adjust: 希望理发师调整的层次、分线、体积、发尾、刘海。
- Avoid: 明确避雷，例如发尾不要卡在下颌最宽处。
- Maintenance: 每日打理时间、返店周期和工具接受度。
- Creator note: 标注该建议来自 starter / unverified 规则，并写出不确定点。

## Do-Not-Do

- Do not describe face shape, hair volume, age, or gender as a flaw.
- Do not promise a fixed result.
- Do not use private photos or unauthorized public references in public examples.
- Do not recommend exact color formulas, real product brands, or invasive paths.
- Do not hide maintenance cost.

## Maintenance Guide

| Level | Daily effort | Suitable direction | Avoid |
| --- | --- | --- | --- |
| low | 0-5 minutes | stable length, forgiving layers, simple parting | precise bangs, high-change curl, frequent refresh |
| medium | 5-15 minutes | light styling, controlled waves, planned volume | unclear routine |
| high | 15+ minutes | structured curl, stronger creator cue, visible color direction | calling it low effort |

## Creator Note

Use this card after selecting 2-5 rule cards from [Hairstyle Rule Index](../modules/hairstyle/hairstyle-rule-index.md). If multiple directions are valid, create one brief per direction and explain the tradeoff.

## Synthetic Example Brief

```yaml
execution_card_type: "barber_brief"
version: "0.2"
goal: "cleaner and softer client-facing hairstyle"
scenario: "client meeting and profile photo"
current_concern: "side weight sits near the jawline"
hair_signals:
  length: "medium"
  volume: "medium-high"
  texture: "medium"
  natural_shape: "slight wave"
  crown_support: "medium"
face_proportion_signals:
  forehead: "medium exposure"
  cheekbone: "visible"
  jawline: "stronger lower-face line"
  uncertainty: "needs stylist review"
keep:
  - "medium length"
  - "low-to-medium daily maintenance"
adjust:
  - "soft side layers"
  - "reduce lower-side weight"
  - "keep crown support natural"
avoid:
  - "blunt end at jawline widest point"
  - "heavy side volume near cheekbone"
length_boundary: "around collarbone, not chin-stop"
layer_direction: "soft face-side transition"
bangs_parting_direction: "light off-center part, no heavy full bangs"
volume_direction: "moderate crown support, lighter lower side"
color_direction: "no color change in this brief"
maintenance:
  daily_time: "5-10 minutes"
  salon_return_cycle: "6-10 weeks"
  tool_tolerance: "basic blow-dry only"
reference_keywords:
  - "soft face framing"
  - "clean workday outline"
creator_note: "Synthetic example built from StyleOS v0.2 starter rules."
privacy_note: "No identifiable data included."
```

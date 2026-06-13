# Barber Brief Card

This card helps users communicate hairstyle goals to a hairstylist.

中文说明：
这张卡可以给理发师看，用来说明目标、当前担忧、保留项、调整项和避雷，不要只给网图。

## Template

```yaml
execution_card_type: "barber_brief"
goal: ""
current_concern: ""
keep:
  - ""
adjust:
  - ""
avoid:
  - ""
reference_keywords:
  - ""
maintenance_level: "low / medium / high"
```

## Field Notes

- Goal: 想达到的整体方向，如 clean、softer、professional。
- Current concern: 当前最困扰的问题，用中性语言描述。
- Keep: 明确不想改变的长度、颜色或维护方式。
- Adjust: 希望理发师调整的层次、分线、体积、发尾。
- Avoid: 明确避雷，例如不要发尾卡在下颌最宽处。
- Reference keywords: 关键词，不用真实人物照片。
- Maintenance level: 每天可接受的打理成本。

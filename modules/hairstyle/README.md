# Hairstyle Module

Hairstyle module focuses on helping creators structure hairstyle suitability reasoning based on face shape, hair attributes, styling goals, constraints, and execution cards for hairstylists.

中文说明：
发型模块用于帮助造型 / 发型 / 形象创作者，将“适合什么发型”这件事结构化，输出可解释的发型建议和理发师沟通卡。

## What this module covers

- Face-shape starter tags.
- Hair attribute tags.
- Hairstyle goal tags.
- Starter hairstyle mapping matrix.
- Public starter hairstyle Rule Cards.
- Barber brief execution template.

## What this module does not cover

- It does not diagnose identity, attractiveness, health, age, or personality.
- It does not replace professional hairstylist consultation.
- It does not include expert-certified hairstyle libraries.
- It does not include real customer photos or verified case databases.
- It does not recommend medical, cosmetic surgery, or body modification.

## Input Signals

- Face-shape tendency.
- Facial feature weight.
- Hair volume, texture, shape, and crown height.
- Hairline and forehead exposure.
- Maintenance willingness.
- Haircut risk tolerance.
- Target scenario.
- Styling goal.

## Output Recommendations

- Length range.
- Layer direction.
- Bangs or parting strategy.
- Volume strategy.
- Face-framing strategy.
- Avoid notes.
- Barber communication notes.

## Relationship with Barber Brief Card

The module should convert abstract recommendations into a practical [Barber Brief Card](../../execution-cards/barber-brief-card.md).

The brief card should describe goals, current concerns, what to keep, what to adjust, what to avoid, reference keywords, and maintenance level.

## Starter Rule Status

All public hairstyle rules in v0.1.1 are `starter / unverified`.

中文说明：
当前发型规则仅用于协议演示和社区共创，不代表专家认证结论。真实服务中需要创作者人工判断和用户确认。

## Files

- [Hairstyle Taxonomy](hairstyle-taxonomy.md)
- [Face Shape Tags](face-shape-tags.md)
- [Hair Attribute Tags](hair-attribute-tags.md)
- [Hairstyle Goal Tags](hairstyle-goal-tags.md)
- [Hairstyle Rule Index](hairstyle-rule-index.md)
- [Barber Brief Template](barber-brief-template.md)
- [Hairstyle Mapping Matrix](hairstyle-mapping-matrix.md)

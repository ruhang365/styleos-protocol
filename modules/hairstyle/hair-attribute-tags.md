# Hair Attribute Tags

Hair attribute tags describe practical input signals for hairstyle decisions.

中文说明：
发型相关输入标签用于描述发量、发质、头顶高度、发际线、露额程度、维护意愿和剪发风险承受度。它们是服务沟通字段，不是评价用户外貌的标签。

## Hair Volume

### `hair_volume_low`

- 中文解释：发量视觉存在感偏低，容易贴头皮或显得轮廓支撑不足。
- 使用场景：需要增加蓬松感、避免过度打薄、控制直发贴头皮效果。

### `hair_volume_medium`

- 中文解释：发量支撑较稳定，发型选择空间较大。
- 使用场景：适合根据脸型、目标和维护意愿调整层次与长度。

### `hair_volume_high`

- 中文解释：发量视觉存在感偏高，可能带来厚重、堆积或难打理问题。
- 使用场景：重点不是一味剪短，而是减轻重量感和控制轮廓。

## Hair Texture

### `hair_texture_fine`

- 中文解释：发丝细软，容易塌，也可能更容易塑造轻盈感。
- 使用场景：关注支撑、层次和低维护定型方式。

### `hair_texture_medium`

- 中文解释：发丝粗细中等，适配范围较广。
- 使用场景：可作为默认基线，再结合发量和发型目标判断。

### `hair_texture_coarse`

- 中文解释：发丝偏粗硬，轮廓支撑强，但可能显得厚或硬。
- 使用场景：适合考虑重量控制、柔化层次和易打理方案。

## Hair Shape

### `hair_shape_straight`

- 中文解释：自然状态较直，线条清晰。
- 使用场景：可支持利落感，但需要避免过度贴脸或贴头皮。

### `hair_shape_wavy`

- 中文解释：自然带波纹或可形成柔和曲线。
- 使用场景：适合做柔化轮廓、增加自然层次。

### `hair_shape_curly`

- 中文解释：卷度明显，需要考虑体积、层次和维护方式。
- 使用场景：输出建议时应考虑真实打理能力，避免高维护方案。

### `hair_shape_natural_curl`

- 中文解释：自然卷或不规则卷曲较明显。
- 使用场景：需要尊重原生形态，优先考虑可持续打理方案。

## Scalp Flatness / Crown Height

### `crown_height_low`

- 中文解释：头顶或颅顶视觉支撑不足，容易显扁。
- 使用场景：可考虑轻度头顶蓬松、分线调整或层次支撑。

### `crown_height_medium`

- 中文解释：头顶支撑相对平衡。
- 使用场景：根据脸型和场景微调即可。

### `crown_height_high`

- 中文解释：头顶高度明显，可能加强纵向视觉。
- 使用场景：长脸或想显柔和时应避免继续拉高。

## Hairline Visibility

### `hairline_visible`

- 中文解释：发际线在常规发型中容易被看到。
- 使用场景：可用轻刘海、侧分或碎发调整露额比例。

### `hairline_partially_covered`

- 中文解释：发际线部分被刘海、碎发或分线遮挡。
- 使用场景：适合微调遮挡，而不是直接厚重覆盖。

## Forehead Exposure

### `forehead_exposure_low`

- 中文解释：额头大部分被遮挡。
- 使用场景：可能影响清爽度和成熟度，需要结合目标判断。

### `forehead_exposure_medium`

- 中文解释：露额比例适中。
- 使用场景：通常更容易在清爽和柔和之间平衡。

### `forehead_exposure_high`

- 中文解释：额头露出较多。
- 使用场景：额头偏高或想显柔和时，可考虑轻遮挡或侧分平衡。

## Neck Length Impression

### `neck_length_short_impression`

- 中文解释：颈部视觉留白偏少或被发型/衣领压住。
- 使用场景：发尾长度、层次和衣领需要协同，避免全部重量压在颈侧。

### `neck_length_long_impression`

- 中文解释：颈部留白较明显。
- 使用场景：可支持更利落或优雅的发型轮廓。

## Maintenance Willingness

### `maintenance_low`

- 中文解释：用户不愿每天花较多时间打理。
- 使用场景：避免需要频繁卷发、复杂定型或高频修剪的方案。

### `maintenance_medium`

- 中文解释：用户可以接受基础吹整和少量工具。
- 使用场景：适合轻层次、可复现的发型方向。

### `maintenance_high`

- 中文解释：用户愿意投入较多时间维护造型。
- 使用场景：可以讨论更明显的卷度、层次、颜色或风格变化。

## Haircut Risk Tolerance

### `haircut_risk_low`

- 中文解释：用户不希望变化过大。
- 使用场景：先做局部调整，如分线、刘海轻量化、发尾层次。

### `haircut_risk_medium`

- 中文解释：用户可以接受可见变化，但希望可控。
- 使用场景：适合中等层次、长度微调和轮廓修正。

### `haircut_risk_high`

- 中文解释：用户愿意接受明显发型变化。
- 使用场景：仍需明确避雷和维护成本，不应只追求冲击感。

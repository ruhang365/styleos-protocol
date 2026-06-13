# Hairstyle Module

This is the first deep module of StyleOS Protocol.

中文说明：
发型模块是 StyleOS 第一个深度模块，用于帮助造型、发型、形象博主把“适合什么发型”结构化，并生成可解释、可复核、可执行的理发师沟通卡。

## What is the Hairstyle Module

The Hairstyle Module structures hairstyle suitability reasoning across user goals, face-shape signals, face proportions, local facial signals, hair attributes, constraints, rule cards, lite reports, and barber briefs.

It is not an automatic haircut decision engine. It is a protocol layer that helps creators explain and deliver hairstyle advice more consistently.

## Why Hairstyle is the First Deep Module

Hairstyle advice is a high-frequency creator service request. It is also difficult to standardize because it depends on face signals, hair attributes, maintenance willingness, risk tolerance, workplace or school constraints, and offline execution quality.

中文说明：
“适合什么发型”是造型咨询中最常见的问题之一，也最容易因为信息不完整、沟通不清、理发师执行偏差而翻车。因此发型模块适合作为 StyleOS 的第一个深度示范模块。

## Who Can Use It

- styling creators
- hairstyle creators
- image consultants
- hairstylists
- career image creators
- photography / styling studios
- small beauty and styling businesses
- developers building StyleOS-compatible tools

## What Inputs It Uses

- basic profile
- target scenario
- current hairstyle description
- face shape tag
- face proportion tags
- jawline / cheekbone / forehead signals
- hair volume, texture, and shape
- hairline visibility and forehead exposure
- crown height
- maintenance willingness
- willingness to cut short, perm, or color
- workplace / school constraints
- styling goals
- risk tolerance
- creator notes

See [Hairstyle Input Schema](hairstyle-input-schema.md).

## What Outputs It Generates

- hairstyle direction
- suitable options
- avoid list
- hair color direction
- barber brief
- lite report sections
- feedback notes
- abstracted rule improvements

## How Creators Can Use It

Creators can use the module to collect structured intake, tag the fan profile, select starter rule cards, draft a lite report, manually review recommendations, deliver a barber brief, collect feedback, and abstract reusable rule improvements.

See [Creator Guide](creator-guide.md).

## How Barber Brief Works

The barber brief converts abstract advice into execution language:

- user goal
- current concern
- keep
- adjust
- avoid
- length direction
- bangs direction
- layer direction
- volume direction
- color direction
- maintenance level
- do-not-do list

See [Barber Brief Schema](barber-brief-schema.md) and [Barber Brief Card](../../execution-cards/barber-brief-card.md).

## What is Open Source

The open repository includes:

- taxonomy
- starter tags
- starter / unverified rules
- synthetic cases
- barber brief template
- creator workflow
- validation checklist

## What Belongs to Future StyleOS Pro

Future StyleOS Pro may include:

- expert-reviewed hairstyle rules
- verified case database
- advanced face / hair mapping engine
- creator-specific model
- high-quality before / after feedback loop
- salon partner execution network

These are not part of the Apache-2.0 open repository unless explicitly released under a separate open license.

## Important Disclaimer

All v0.2 hairstyle rules are `starter / unverified`. They are for protocol demonstration and community iteration, not expert-certified recommendations, scientific conclusions, or data-validated results.

中文说明：
当前内容用于公开协议演示和创作者共创。真实服务中必须由创作者人工复核，并结合用户目标、约束、维护成本和线下执行条件判断。

## Files

- [Diagnosis Workflow](hairstyle-diagnosis-workflow.md)
- [Input Schema](hairstyle-input-schema.md)
- [Face Shape Tags](face-shape-tags.md)
- [Hair Attribute Tags](hair-attribute-tags.md)
- [Hairstyle Goal Tags](hairstyle-goal-tags.md)
- [Haircut Taxonomy](haircut-taxonomy.md)
- [Hair Length Taxonomy](hair-length-taxonomy.md)
- [Bangs Taxonomy](bangs-taxonomy.md)
- [Layer and Volume Taxonomy](layer-volume-taxonomy.md)
- [Curl / Perm Taxonomy](curl-perm-taxonomy.md)
- [Hair Color Direction](hair-color-direction.md)
- [Face Proportion Tags](face-proportion-tags.md)
- [Jawline / Cheekbone / Forehead Tags](jawline-cheekbone-forehead-tags.md)
- [Maintenance Tags](maintenance-tags.md)
- [Constraints Tags](constraints-tags.md)
- [Barber Brief Schema](barber-brief-schema.md)
- [Creator Guide](creator-guide.md)
- [Quality Checklist](quality-checklist.md)
- [Pro Boundary](pro-boundary.md)
- [Mapping Matrix](hairstyle-mapping-matrix.md)
- [Rule Index](hairstyle-rule-index.md)
- [Barber Brief Template](barber-brief-template.md)

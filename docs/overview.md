# Overview

StyleOS Protocol is an open protocol for AI-powered personal styling workflows.

It provides shared formats for:

- collecting fan or client styling inputs;
- tagging appearance and scenario signals;
- expressing reusable styling rules;
- generating lite reports;
- evaluating rule and report quality;
- organizing seed knowledge modules;
- converting recommendations into execution cards;
- reviewing evidence level and rule status.

中文说明：
StyleOS Protocol 的目标是把个人造型经验从零散表达变成结构化资产，让创作者、小型服务团队和开发者能围绕同一套字段、标签、规则卡和报告格式协作。

## Three Layers

StyleOS now contains three layers:

1. Protocol layer
2. Creator launch layer
3. Seed knowledge layer

### 1. Protocol Layer

The protocol layer defines schemas, contribution rules, data policy, commercial boundary, trademarks, privacy, and security.

中文说明：
Protocol layer 是底层标准，负责字段、Schema、数据边界、贡献规则和互操作基础。

### 2. Creator Launch Layer

The creator launch layer explains Creator Studio Lite, Creator Alpha, launch copy, GitHub Star growth, open-core strategy, hosted service boundary, and small-B use cases.

中文说明：
Creator launch layer 用来对外传播、招募创作者内测，并说明未来托管产品和 GitHub 协议之间的边界。

### 3. Seed Knowledge Layer

The seed knowledge layer contains starter modules, starter tags, starter / unverified rules, synthetic cases, validation framework, and execution cards.

中文说明：
Seed knowledge layer 让仓库不只是概念，而是有可阅读、可引用、可贡献、可扩展的初始内容库。当前内容不是专家认证库。

v0.2 expands the hairstyle module into the first deeper module pack. It adds richer hairstyle taxonomies, 40 hairstyle starter rules, 12 synthetic hairstyle cases, creator-kit templates, validation forms, and a v0.2 barber brief.

## Core Objects

### Modules

Modules organize starter knowledge by domain: hairstyle, color, outfit, makeup, accessories, and scenario.

See [Modules](../modules/README.md).

### Input Profile

Input Profile describes the user's basic profile, target scenario, photo metadata, goals, constraints, budget, and creator notes.

See [Input Schema](input-schema.md).

### Style Tags

Style Tags describe reusable labels for face shape, facial proportion, facial feature weight, hairstyle, color, outfit, makeup, scenario, and creator-specific extensions.

See [Style Tag Schema](style-tag-schema.md).

### Rule Card

Rule Card describes reusable styling logic: when certain conditions apply, what to recommend, what to avoid, and how confident the rule is.

See [Rule Card Schema](rule-card-schema.md).

Starter Rule Cards are stored in [Rules](../rules/README.md). They are `starter / unverified`; the v0.2 hairstyle expansion remains E0 starter content.

### Lite Report

Lite Report describes the creator-facing output format for summary, diagnosis tags, recommendations, avoid list, execution card, and next action checklist.

See [Report Schema](report-schema.md).

### Evaluation Framework

Evaluation Framework helps reviewers assess clarity, applicability, consistency, creator usefulness, user actionability, feedback score, and expert review status.

See [Evaluation Framework](evaluation-framework.md).

### Execution Cards

Execution Cards convert recommendations into practical briefs for hairstylists, shopping, makeup artists, outfit styling, or photo shoots.

See [Execution Cards](../execution-cards/README.md).

### Synthetic Cases

Synthetic Cases demonstrate how inputs, rule cards, lite recommendations, and execution cards connect.

See [Synthetic Cases](../cases/README.md).

The hairstyle v0.2 synthetic cases live in [Hairstyle Synthetic Cases](../cases/hairstyle/README.md).

### Validation

Validation defines evidence levels, rule status, and review process.

See [Validation](../validation/README.md).

## Repository Scope

This repository is protocol-first and documentation-only.

It does not include an application, frontend framework, backend service, package manifest, hosted platform, expert model library, verified case database, or certification system.

## Seed Content Disclaimer

The current seed rules are starter content for protocol demonstration and community iteration. They are not expert-certified recommendations.

中文说明：
当前种子规则用于协议演示和社区共创，不代表专家认证结论。真实服务中必须由创作者人工复核，并遵守隐私、授权和数据边界。

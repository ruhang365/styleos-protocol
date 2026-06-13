# Overview

StyleOS Protocol is an open protocol for AI-powered personal styling workflows.

It provides shared formats for:

- collecting fan or client styling inputs;
- tagging appearance and scenario signals;
- expressing reusable styling rules;
- generating lite reports;
- evaluating rule and report quality.
- organizing seed knowledge modules;
- converting recommendations into execution cards;
- reviewing evidence level and rule status.

中文说明：
StyleOS Protocol 的目标是把个人造型经验从零散表达变成结构化资产，让创作者、小型服务团队和开发者能围绕同一套字段、标签、规则卡和报告格式协作。

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

v0.1.1 starter Rule Cards are stored in [Rules](../rules/README.md). They are `starter / unverified` and mostly E0 synthetic starter rules.

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

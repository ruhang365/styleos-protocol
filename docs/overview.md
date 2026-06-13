# Overview

StyleOS Protocol is an open protocol for AI-powered personal styling workflows.

It provides shared formats for:

- collecting fan or client styling inputs;
- tagging appearance and scenario signals;
- expressing reusable styling rules;
- generating lite reports;
- evaluating rule and report quality.

中文说明：
StyleOS Protocol 的目标是把个人造型经验从零散表达变成结构化资产，让创作者、小型服务团队和开发者能围绕同一套字段、标签、规则卡和报告格式协作。

## Core Objects

### Input Profile

Input Profile describes the user's basic profile, target scenario, photo metadata, goals, constraints, budget, and creator notes.

See [Input Schema](input-schema.md).

### Style Tags

Style Tags describe reusable labels for face shape, facial proportion, facial feature weight, hairstyle, color, outfit, makeup, scenario, and creator-specific extensions.

See [Style Tag Schema](style-tag-schema.md).

### Rule Card

Rule Card describes reusable styling logic: when certain conditions apply, what to recommend, what to avoid, and how confident the rule is.

See [Rule Card Schema](rule-card-schema.md).

### Lite Report

Lite Report describes the creator-facing output format for summary, diagnosis tags, recommendations, avoid list, execution card, and next action checklist.

See [Report Schema](report-schema.md).

### Evaluation Framework

Evaluation Framework helps reviewers assess clarity, applicability, consistency, creator usefulness, user actionability, feedback score, and expert review status.

See [Evaluation Framework](evaluation-framework.md).

## Repository Scope

This repository is protocol-first and documentation-only.

It does not include an application, frontend framework, backend service, package manifest, hosted platform, expert model library, verified case database, or certification system.

# Creator Studio Lite Feature Spec

This is an early product specification for StyleOS Creator Studio Lite.

中文说明：
这是第一版功能规格草案，用于说明未来托管产品可能如何承接开源协议。它不是当前仓库中的 App 实现。

## MVP Features

### 1. Fan Intake Form

- Purpose: collect structured fan consultation inputs.
- User: creator or small-B operator.
- Input: fan questionnaire, scenario, goals, constraints, consent state.
- Output: structured fan intake profile.
- Open-source dependency: [Input Schema](../docs/input-schema.md), [Fan Intake Form](../creator-kit/fan-intake-form.md).
- Commercial dependency: hosted form storage, consent tracking, session management.

### 2. Fan Profile Tagging

- Purpose: convert intake signals into StyleOS tags.
- User: creator.
- Input: fan intake profile and creator notes.
- Output: profile tag set.
- Open-source dependency: [Style Tag Schema](../docs/style-tag-schema.md), [Modules](../modules/README.md).
- Commercial dependency: dashboard UI, saved profiles, assisted tagging.

### 3. Rule Card Selection

- Purpose: match profile tags and scenarios to rule cards.
- User: creator.
- Input: tag set, scenario, goals, constraints.
- Output: selected rule cards and avoid notes.
- Open-source dependency: [Rule Card Schema](../docs/rule-card-schema.md), [Rules](../rules/README.md).
- Commercial dependency: rule search, recommendation ranking, Pro library access.

### 4. Lite Report Generation

- Purpose: produce a draft report that creators can review.
- User: creator.
- Input: fan profile, tags, selected rules, creator notes.
- Output: lite report draft.
- Open-source dependency: [Report Schema](../docs/report-schema.md), [Report Lite Template](../creator-kit/report-lite-template.md).
- Commercial dependency: hosted report generator, report versioning, export engine.

### 5. Creator Manual Review

- Purpose: keep creator judgment in the loop.
- User: creator.
- Input: draft report and selected rules.
- Output: approved or edited report.
- Open-source dependency: [Evaluation Framework](../docs/evaluation-framework.md).
- Commercial dependency: review UI, edit history, quality checks.

### 6. PDF / Shareable Report Export

- Purpose: deliver a polished report to the fan.
- User: creator and fan.
- Input: approved lite report.
- Output: PDF or shareable report link.
- Open-source dependency: report schema and templates.
- Commercial dependency: export service, hosted file delivery, creator branding.

### 7. Feedback Collection

- Purpose: collect service usefulness feedback.
- User: creator and fan.
- Input: report outcome, clarity score, actionability score, fan feedback.
- Output: structured feedback.
- Open-source dependency: [Evaluation Framework](../docs/evaluation-framework.md).
- Commercial dependency: feedback forms, analytics, privacy controls.

### 8. Rule Abstraction Notes

- Purpose: turn repeated creator observations into reusable rule candidates.
- User: creator and reviewer.
- Input: anonymized feedback summary and creator notes.
- Output: rule abstraction note or schema suggestion.
- Open-source dependency: [Rule Card Schema](../docs/rule-card-schema.md), [Contributor Terms](../CONTRIBUTOR_TERMS.md).
- Commercial dependency: abstraction workflow, Pro review queue, partner review.

## Later Features

### 1. Creator Storefront

- Purpose: help creators package and sell services.
- User: creator and fan.
- Input: service menu, creator profile, report packages.
- Output: public service page.
- Open-source dependency: [Service Menu Template](../creator-kit/service-menu-template.md).
- Commercial dependency: storefront hosting, account system, payment support.

### 2. Payment Integration

- Purpose: support paid creator services.
- User: creator and fan.
- Input: service package and payment state.
- Output: paid order and service session.
- Open-source dependency: service menu structure.
- Commercial dependency: payment provider, billing, refunds, tax handling.

### 3. Creator-Branded Reports

- Purpose: let creators deliver reports under their own service identity.
- User: creator.
- Input: creator brand settings and approved report.
- Output: branded report.
- Open-source dependency: report template.
- Commercial dependency: brand settings, export renderer, asset management.

### 4. StyleOS Pro Rule Library

- Purpose: provide higher-confidence rules and patterns.
- User: creator, expert, small-B operator.
- Input: profile tags and scenario.
- Output: Pro rule suggestions.
- Open-source dependency: public rule schema and evidence levels.
- Commercial dependency: licensed Pro library, access control, review governance.

### 5. Expert Model Add-ons

- Purpose: support advanced expert-assisted workflows.
- User: creator and expert reviewer.
- Input: structured profile and service context.
- Output: expert-assisted suggestions or review notes.
- Open-source dependency: schemas.
- Commercial dependency: expert model service, quality control, separate authorization.

### 6. Certified Creator Badge

- Purpose: signal reviewed creator capability.
- User: creator and fan.
- Input: creator review status and certification records.
- Output: certification badge.
- Open-source dependency: validation vocabulary.
- Commercial dependency: certification process, trademark permission, governance.

### 7. Case Database

- Purpose: manage authorized, anonymized, and verified cases.
- User: creator, reviewer, expert.
- Input: consented case data and feedback.
- Output: searchable case references.
- Open-source dependency: data policy and case structure.
- Commercial dependency: authorization workflow, anonymization, secure storage.

### 8. Multi-Scenario Recommendation

- Purpose: support different image strategies for work, dating, content, and daily use.
- User: creator and fan.
- Input: multiple target scenarios.
- Output: scenario-specific reports.
- Open-source dependency: scenario taxonomy and rule cards.
- Commercial dependency: scenario planner, report variants, Pro rules.

### 9. Partner Salon / Studio Execution Cards

- Purpose: connect recommendations to execution partners.
- User: creator, fan, salon, photography studio.
- Input: approved report and execution needs.
- Output: partner-ready execution cards.
- Open-source dependency: [Execution Cards](../execution-cards/README.md).
- Commercial dependency: partner network, booking workflows, partner terms.

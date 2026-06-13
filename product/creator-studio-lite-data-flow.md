# Creator Studio Lite Data Flow

This document describes the data flow principles for future StyleOS Creator Studio Lite.

中文说明：
这是托管小 B 工具的数据流原则，不代表当前开源仓库已经运行数据系统。

## Data Flow Overview

```text
Raw service data
  -> authorized service use
  -> optional anonymization
  -> anonymized case data
  -> abstracted rule data
  -> review
  -> optional Pro model data under separate authorization
```

## 1. Raw Service Data

Raw service data may include:

- fan photos;
- fan questionnaire;
- creator notes;
- service session records;
- report drafts;
- private feedback.

Principles:

- only for this service session;
- not open-source;
- not automatically used for training;
- must be protected by hosted product privacy and consent rules;
- should not be submitted to GitHub.

## 2. Anonymized Case Data

Anonymized case data may include:

- de-identified tags;
- diagnosis result;
- report outcome;
- feedback summary;
- scenario and constraints after removing identifiers.

Principles:

- requires authorization;
- must remove names, contacts, photos, account handles, exact locations, and identifying combinations;
- may be used for synthetic or fully anonymized examples only when policy allows.

## 3. Abstracted Rule Data

Abstracted rule data includes generalized rule patterns with no personal data.

Examples:

- "low-to-medium contrast may be more stable for low-contrast near-face styling";
- "barber brief should describe goals and avoid notes, not only reference images";
- "camera scenarios should prioritize upper-body color and neckline."

Principles:

- no personal data;
- may be contributed to protocol;
- should include evidence level and limitations;
- should not expose raw service context.

## 4. Pro Model Data

Pro model data may include:

- verified cases;
- expert-reviewed rules;
- performance feedback;
- commercial rule patterns;
- model evaluation records.

Principles:

- requires separate authorization;
- belongs to StyleOS Pro / commercial layer unless explicitly released;
- should be governed by Pro terms, privacy rules, and review workflow.

## Required Boundary

Data generated from small-B tools must not automatically enter the public repository or Pro library unless proper consent, anonymization, and authorization are in place.

中文说明：
小 B 工具产生的数据不能默认自动进入开源库或高级库，必须经过授权、脱敏、分层处理。

## Public Repository Rule

The public repository accepts:

- synthetic examples;
- fully anonymized cases with proper authorization;
- abstracted rules with no personal data;
- schema suggestions;
- creator workflow suggestions.

The public repository does not accept raw photos, private fan records, private creator notes, or unauthorized cases.

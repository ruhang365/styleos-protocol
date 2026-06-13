# Data Policy

StyleOS Protocol is designed around responsible data handling for styling workflows.

This repository is a protocol and documentation repository. It does not claim to operate a current production data system.

中文说明：
本文件描述协议原则，不承诺当前仓库已经具备实际数据系统、案例库或模型训练系统。

## Core Rules

- Do not submit real user photos.
- Do not submit personally identifiable information.
- Do not submit unauthorized service cases.
- Real cases must be anonymized and authorized before they can be shared.
- This repository only accepts synthetic examples or fully anonymized cases.

## Four-Layer Data Principle

### 1. Raw Service Data

Raw service data means original intake materials from a real service interaction, such as photos, notes, preferences, body or face descriptions, conversation records, or delivery records.

Protocol principle:

- Raw service data must stay outside this open repository.
- Raw service data requires user authorization.
- Raw service data should be protected by the service provider's privacy, consent, and security processes.

### 2. Anonymized Case Data

Anonymized case data means a case that has removed direct and indirect identifiers.

Protocol principle:

- Remove names, contacts, faces, exact dates, account IDs, locations, and other identifiers.
- Remove rare combinations that could re-identify a person.
- Obtain authorization before using a real case, even if anonymized.
- Prefer synthetic examples for public contribution.

### 3. Abstracted Rule Data

Abstracted rule data means generalized styling logic extracted from repeated practice, such as condition-to-recommendation patterns.

Protocol principle:

- Rule data should be expressed as reusable `Rule Card` entries.
- Rule data should avoid private source details.
- Rule data should distinguish creator experience, expert review, community feedback, and synthetic demonstration.

### 4. Pro Model Training Data

Pro model training data means curated, licensed, evaluated, or commercially managed data used for advanced model development.

Protocol principle:

- Pro model training data is not part of this open repository.
- Only authorized, anonymized, and properly processed data may enter case libraries or model libraries.
- Commercial datasets, expert libraries, and model training pipelines belong to the commercial layer unless explicitly released under a separate license.

## Contribution Standard

Before submitting any example, rule card, workflow, or report:

- confirm it is synthetic or fully anonymized;
- confirm it contains no real photos;
- confirm it contains no names, contacts, account IDs, exact addresses, or private conversation logs;
- confirm you have the right to contribute the content;
- state whether the contribution is synthetic, anonymized, or abstracted from creator practice.

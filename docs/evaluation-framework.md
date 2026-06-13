# Evaluation Framework

The Evaluation Framework helps the community review rule cards, schemas, creator workflows, and lite reports.

中文说明：
评估框架用于判断规则是否清晰、可用、一致、对创作者有帮助、对用户可执行，并保留反馈与专家复核状态。

## Evaluation Object

```yaml
evaluation_id: "eval-synthetic-rule-001"
target_type: "rule_card"
target_id: "rule-synthetic-hairstyle-001"
clarity: 4
applicability: 4
consistency: 3
creator_usefulness: 4
user_actionability: 4
feedback_score: 0
expert_review_status: "not_reviewed"
seed_rule_evaluation:
  clarity: 4
  non_harmful_language: 5
  actionability: 4
  creator_usefulness: 4
  execution_feasibility: 4
  privacy_safety: 5
  review_readiness: 3
review_notes:
  - "Synthetic evaluation for protocol demonstration only."
```

## Criteria

### Clarity

Measures whether the contribution is easy to understand.

Score guide:

- `1`: vague or confusing.
- `3`: understandable but needs refinement.
- `5`: clear, specific, and easy to review.

### Applicability

Measures whether the rule or template can be applied to a real creator workflow.

Score guide:

- `1`: too broad or impractical.
- `3`: usable in some scenarios.
- `5`: clearly tied to conditions, scenario, and constraints.

### Consistency

Measures whether the contribution follows existing schemas and terminology.

Score guide:

- `1`: conflicts with protocol structure.
- `3`: mostly consistent with small gaps.
- `5`: fully aligned with current schema.

### Creator Usefulness

Measures whether the contribution helps creators package, deliver, or improve services.

Score guide:

- `1`: not useful for creator delivery.
- `3`: useful but needs more operational detail.
- `5`: directly useful in a creator workflow.

### User Actionability

Measures whether the end user can act on the advice.

Score guide:

- `1`: abstract or impossible to execute.
- `3`: partly actionable.
- `5`: concrete next steps are clear.

### Feedback Score

Community or creator feedback score.

Suggested scale:

- `-2`: harmful or misleading.
- `-1`: weak or confusing.
- `0`: no feedback yet.
- `1`: useful.
- `2`: highly useful and repeatable.

### Expert Review Status

Allowed values:

- `not_reviewed`
- `creator_reviewed`
- `expert_reviewed`
- `needs_revision`
- `deprecated`

## Seed Rule Evaluation

Seed Rule Evaluation is used for v0.1.2 starter / unverified rules.

中文说明：
Seed rule evaluation 用来判断 starter rules 是否适合公开展示、社区共创和小 B 工具调用。它不等于专家认证。

### Clarity

Is the rule understandable, specific, and easy to explain?

### Non-Harmful Language

Does the rule avoid appearance-shaming, body-shaming, gender stereotypes, deterministic claims, and identity labeling?

### Actionability

Can the creator or user take a clear next step from the rule?

### Creator Usefulness

Does the rule help creators package, explain, or deliver a service?

### Execution Feasibility

Can the recommendation be turned into a barber brief, shopping keyword card, makeup artist brief, outfit styling brief, or photo shoot brief?

### Privacy Safety

Does the rule avoid requiring real user photos, names, contacts, private service records, or identifying details in public examples?

### Review Readiness

Is the rule ready for community feedback or creator usage review?

Suggested score guide:

- `1`: not ready.
- `3`: usable as starter content with limitations.
- `5`: clear, safe, actionable, and ready for review.

## Review Principles

- Prefer narrow, testable rules over broad claims.
- Distinguish synthetic examples from real-world evidence.
- Do not overstate confidence.
- Preserve creator judgment and manual review.
- Keep privacy and commercial boundary rules visible.
- Mark v0.1.2 seed rules as starter / unverified unless they pass a later review process.

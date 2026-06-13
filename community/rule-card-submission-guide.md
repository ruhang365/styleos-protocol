# Rule Card Submission Guide

Rule Cards are reusable StyleOS logic units.

中文说明：
高质量 Rule Card 应该可解释、可复核、可执行，并且清楚标注证据等级和限制。

## Good Example

```yaml
rule_id: "HAIR-RULE-COMMUNITY-001"
rule_name: "Low-maintenance haircut should include daily styling limit"
module: "hairstyle"
status: "community-submitted"
evidence_level: "E1"
applicable_conditions:
  tags:
    - "maintenance_low"
  constraints:
    - "daily styling time under 5 minutes"
recommendation:
  summary: "Prefer stable length and forgiving layers when daily styling time is limited."
avoid:
  - "High-precision bangs without a maintenance note."
scenario:
  primary: "daily upgrade"
confidence_level: "low"
evidence_type:
  - "community starter"
source_type: "abstracted_creator_practice"
contributor: "community contributor"
limitations: "Needs broader creator feedback."
privacy_note: "No identifiable user data included."
```

## Bad Example

```yaml
rule_name: "Everyone with this face should choose one haircut"
recommendation:
  summary: "This haircut works for all users."
```

Why this is bad:

- too broad
- no conditions
- no limitations
- no scenario
- no evidence level
- no privacy note
- overclaims outcome

## Checklist

- [ ] Conditions are clear.
- [ ] Recommendation is concrete.
- [ ] Avoid list is specific.
- [ ] Scenario is included.
- [ ] Confidence level is `low` or `medium` unless reviewed.
- [ ] Evidence level is included.
- [ ] Status is included.
- [ ] Limitations are included.
- [ ] Privacy note is included.
- [ ] No private or identifiable data is included.
- [ ] No expert-certification claim is made without review.

## Privacy Safety

Do not include:

- real photos
- real names
- contacts
- accounts
- private notes
- unauthorized cases
- payment information
- precise private locations

## Evidence Level

Use [Evidence Levels](../validation/evidence-levels.md):

- E0: synthetic starter rule
- E1: community submitted rule
- E2: repeated creator observation
- E3: expert reviewed rule
- E4: data-supported rule
- E5: Pro model validated pattern

## Status

Use [Rule Status](../validation/rule-status.md):

- starter
- community-submitted
- under-review
- expert-reviewed
- data-supported
- deprecated
- pro-only

## Limitations

Every rule should say when it may not apply. Limitations protect users, creators, and the protocol.

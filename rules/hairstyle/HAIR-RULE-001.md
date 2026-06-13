# HAIR-RULE-001

```yaml
rule_id: "HAIR-RULE-001"
rule_name: "Avoid ending length at the widest jawline point"
module: "hairstyle"
status: "starter / unverified"
version: "0.1.1"
applicable_conditions:
  tags:
    - "face_shape_square"
    - "goal_balance_jawline"
  signals:
    - "jawline is a strong visual line"
  constraints:
    - "user wants softer or less angular outline"
recommendation:
  summary: "Let the haircut length or layers pass above or below the widest jawline point instead of ending exactly there."
  details:
    - "Use soft side layers or face-framing lines to move attention away from a hard stop at the jaw."
    - "Keep the advice framed as contour balance, not as correction of a flaw."
avoid:
  - "Blunt chin-length cut ending exactly at the widest jawline point."
  - "Heavy side volume that stacks at the jaw."
scenario:
  primary: "daily upgrade"
  secondary:
    - "client meeting"
    - "social profile"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
evidence_level: "E0 Synthetic starter rule"
review_status: "starter"
pro_candidate: false
privacy_risk: "low"
execution_card_type: "barber_brief"
explanation: "See Explanation section."
execution_notes: "See Execution Notes section."
limitations: "See Limitations section."
privacy_note: "See Privacy Note section."
```

## Explanation

当下颌线条本身存在感较强时，发尾正好停在最宽处可能让边界更明显。更稳妥的 starter 策略是让长度避开该位置，或用柔和层次过渡。

## Execution Notes

- Barber brief: "Please avoid a blunt end exactly at my widest jawline point."
- Keep the wording about balance and softness.

## Limitations

- Not applicable when the user wants to emphasize a strong structured jawline.
- Needs review with hair volume, texture, and maintenance willingness.

## Privacy Note

Use synthetic or private references only. Do not submit real user photos to this repository.

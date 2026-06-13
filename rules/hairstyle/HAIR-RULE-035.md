# HAIR-RULE-035

```yaml
rule_id: "HAIR-RULE-035"
rule_name: "Pre-shoot camera stability"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  scenarios:
    - "pre_shoot"
    - "profile_photo"
  constraints:
    - "short timeline before shoot"
recommendation:
  summary: "Prioritize camera stability and predictable shape before a shoot."
  details:
    - "Use conservative trimming, end cleanup, and controlled face-side shaping."
    - "Avoid large changes close to the shoot unless the user accepts visible risk."
avoid:
  - "Major haircut direction right before important photos."
  - "Unrehearsed bangs, color, or curl changes before camera work."
scenario:
  primary: "pre-shoot"
  secondary:
    - "creator service"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Camera work magnifies stability, shadow, and silhouette issues; last-minute high-change haircuts add risk."
execution_notes: "Add shoot date, lighting context, and no-major-change boundary to the brief."
limitations: "A professional stylist on set may support higher-risk changes."
privacy_note: "Do not publish private shoot schedules, locations, or identity details."
```

## Explanation

拍摄前发型优先看镜头稳定性。发尾、刘海、脸侧阴影和轮廓可控性比大幅变化更关键。

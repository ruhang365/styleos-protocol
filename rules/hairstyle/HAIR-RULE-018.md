# HAIR-RULE-018

```yaml
rule_id: "HAIR-RULE-018"
rule_name: "Glasses, bangs, and sideburn balance"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "accessory_glasses"
    - "bangs_present"
  goals:
    - "goal_look_cleaner"
recommendation:
  summary: "Consider glasses frame height, bangs weight, and sideburn shape together."
  details:
    - "Keep the eye area open enough for the frame and hair to avoid visual crowding."
    - "Use light bangs or side pieces when the frame is visually strong."
avoid:
  - "Heavy bangs pressing into the frame."
  - "Sideburn volume that competes with thick temples."
scenario:
  primary: "daily upgrade"
  secondary:
    - "client meeting"
    - "livestream"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Glasses already create structure around the eyes; bangs and sideburns should be planned around that structure."
execution_notes: "Ask for frame height, temple thickness, and whether the user wears glasses daily."
limitations: "Different frames change the result; validate with the user's current frame."
privacy_note: "Do not include identifiable eyewear photos or purchase records in public examples."
```

## Explanation

眼镜不是独立配饰，它会改变刘海厚度、鬓角和眼部阴影的判断。沟通卡需要写出镜框和发型的关系。

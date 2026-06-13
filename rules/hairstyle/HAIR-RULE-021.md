# HAIR-RULE-021

```yaml
rule_id: "HAIR-RULE-021"
rule_name: "Chin-length short hair and jawline sensitivity"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  tags:
    - "hair_length_chin"
    - "jawline_width_visible"
  goals:
    - "goal_balance_jawline"
recommendation:
  summary: "Review jawline position carefully before choosing chin-length short hair."
  details:
    - "Move the end point above or below the strongest jawline point when the goal is balance."
    - "Use soft edges or side layers if a chin-length cut is still preferred."
avoid:
  - "Blunt chin-length end at the jawline widest point."
  - "No layer or edge plan for strong lower-face structure."
scenario:
  primary: "barber communication"
  secondary:
    - "haircut risk review"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Chin-length cuts are sensitive because the end point can become a hard visual boundary beside the jaw."
execution_notes: "Ask the stylist to mark the intended end point before cutting."
limitations: "Some users may prefer a structured jawline emphasis."
privacy_note: "Do not publish haircut consultation photos or stylist records."
```

## Explanation

下巴长度短发需要明确发尾停点。若用户目标是下颌平衡，停点、发尾厚度和侧层次都要写进沟通卡。

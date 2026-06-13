# HAIR-RULE-036

```yaml
rule_id: "HAIR-RULE-036"
rule_name: "Livestream lighting and face shadow"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  scenarios:
    - "livestream"
    - "video_call"
  tags:
    - "bangs_present"
recommendation:
  summary: "Consider lighting, face shadow, and eye openness for livestream and video contexts."
  details:
    - "Keep bangs and side pieces from casting heavy shadows on the eyes."
    - "Use controlled face-side shape that stays stable on camera."
avoid:
  - "Heavy bangs covering the eye area under front light."
  - "Side hair that repeatedly falls into the face during video."
scenario:
  primary: "livestream"
  secondary:
    - "video call"
    - "creator profile"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "Video lighting changes how bangs and side hair read; shadows can reduce eye clarity and facial openness."
execution_notes: "Add camera angle, lighting position, and eye-area openness to the creator brief."
limitations: "Actual results depend on lighting setup, lens, and movement."
privacy_note: "Do not publish private livestream screenshots or account handles."
```

## Explanation

直播和视频场景要检查刘海、脸侧发和光线阴影。v0.2 将“镜头清晰度”纳入发型建议。

# HAIR-RULE-038

```yaml
rule_id: "HAIR-RULE-038"
rule_name: "Personal IP memory cue with credibility"
module: "hairstyle"
status: "starter / unverified"
evidence_level: "E0"
version: "0.2"
applicable_conditions:
  scenarios:
    - "personal_ip"
    - "creator_profile"
  goals:
    - "goal_creator_presence"
recommendation:
  summary: "Keep one controlled memory cue without sacrificing credibility or repeatability."
  details:
    - "Use one cue such as parting, soft curl, clean short outline, or color direction."
    - "Keep other elements quieter so the hairstyle remains usable across content formats."
avoid:
  - "Stacking multiple strong cues at once."
  - "Choosing a cue that the creator cannot reproduce consistently."
scenario:
  primary: "personal IP"
  secondary:
    - "content creator"
    - "profile photo"
confidence_level: "medium"
evidence_type:
  - "heuristic"
  - "synthetic example"
source_type: "StyleOS starter content"
contributor: "ruhang365 StyleOS seed"
explanation: "A personal IP hairstyle works better when it is memorable, stable, and credible in the creator's main scenario."
execution_notes: "Document the memory cue and the supporting quiet elements separately."
limitations: "Brand positioning and audience expectations need human review."
privacy_note: "Do not use real influencer names, handles, private audience data, or unauthorized images."
```

## Explanation

个人 IP 发型可以保留记忆点，但不应堆叠多个强元素。v0.2 建议一个可复现记忆点加稳定支撑。

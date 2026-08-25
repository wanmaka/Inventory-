---
kb_id: GOV-KB-001
title: AI-ready Knowledge Schema
domain: shared_governance
knowledge_type: schema
status: approved
effective_date: 2026-08-25
source_authority: boss_confirmed
sensitivity: internal
---

# AI-ready Knowledge Schema

## Required Metadata

ทุก Knowledge Item SHOULD ใช้ YAML Front Matter ตามรูปแบบนี้:

```yaml
---
kb_id: WK-OBK-EXAMPLE-001
title: Example Knowledge Item
domain: one_bangkok_soc
knowledge_type: operational_rule
status: approved
effective_date: 2026-08-25
last_reviewed: 2026-08-25
source_authority: boss_confirmed
sensitivity: internal
owner: SOC
applies_to:
  - SOC_Operator
  - SOC_Supervisor
related_kb_ids: []
supersedes: null
---
```

## Controlled Values

### Domain

- `one_bangkok_soc`
- `personal_business`
- `boss_profile`
- `shared_governance`
- `register`

### Knowledge Type

- `definition`
- `fact`
- `role_profile`
- `authority_rule`
- `operational_rule`
- `workflow`
- `decision_rule`
- `system_profile`
- `zone_profile`
- `template`
- `lesson_learned`
- `preference`
- `personal_context`
- `decision_record`
- `schema`

### Status

- `draft`
- `active_draft`
- `pending_validation`
- `approved`
- `superseded`
- `archived`

### Source Authority

- `law_or_regulation`
- `approved_policy`
- `approved_sop_wi`
- `approved_master_data`
- `boss_confirmed`
- `current_operational_practice`
- `working_draft`
- `example`
- `ai_inference`

### Sensitivity

- `public`
- `internal`
- `restricted`
- `general_personal`
- `sensitive_personal`

## Required Content Structure

Knowledge Item SHOULD contain only relevant sections from this list:

1. Purpose
2. Canonical Definition or Rule
3. Scope and Applicability
4. Roles and Authority
5. Trigger or Preconditions
6. Inputs
7. Workflow
8. Decision Logic
9. Exceptions and Limitations
10. Evidence and Records
11. Outputs
12. Escalation
13. Closure Criteria
14. AI Constraints
15. Sources
16. Change History

## Normative Language

- `MUST / ต้อง` = Mandatory requirement
- `MUST NOT / ห้าม` = Prohibited action
- `SHOULD / ควร` = Recommended practice
- `MAY / สามารถ` = Permitted action under stated conditions
- `IF–THEN` = Deterministic decision logic
- `UNKNOWN` = Information is unavailable and MUST NOT be guessed

## Atomic Knowledge Rule

แต่ละ Knowledge Item SHOULD มีหัวข้อหลักเดียวและสามารถอ้างอิงด้วย Stable ID ได้

AI MUST NOT treat examples, historical records or drafts as Approved operational rules.

## Naming Convention

`[DOMAIN]-[TOPIC]-[TYPE]-[SEQUENCE]`

ตัวอย่าง:

- `WK-OBK-CMD-001` — One Bangkok command rule
- `WK-OBK-ZONE-001` — One Bangkok zone master
- `WK-BIZ-GF-001` — Get Fruit business knowledge
- `BP-PRO-001` — Boss professional profile
- `GOV-AI-001` — AI governance
- `REG-DEC-001` — Decision register


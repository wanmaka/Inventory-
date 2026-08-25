---
kb_id: WK-OBK-CMD-001
title: Emergency Command and Immediate Response Governance
domain: one_bangkok_soc
knowledge_type: authority_rule
status: approved
effective_date: 2026-08-25
source_authority: boss_confirmed
sensitivity: internal
owner: DCC
applies_to:
  - DCC
  - SOC
  - Field_IC
  - EOT
  - Security
related_kb_ids:
  - WK-OBK-SOC-001
  - WK-OBK-MOZ-001
---

# Emergency Command and Immediate Response Governance

## Authority Model

- DCC MUST declare, escalate, de-escalate, stand down and terminate an emergency plan.
- Each emergency SOP MUST define the designated Field IC position in advance.
- Field IC MUST command operational response at the incident scene or Incident Command Post.
- SOC MUST communicate plan activation and relevant instructions to all stakeholders identified in the plan-specific Notification Matrix.
- SOC and DCC perform Rear Command functions.

## Field and Rear Command

### Field IC

- Exercises tactical command at the incident scene or ICP.
- Coordinates with SOC and DCC.
- Directs field resources according to the applicable SOP.

### DCC

- Holds formal authority for plan activation and status changes.
- Provides strategic direction, management escalation and decision support.

### SOC

- Provides CCTV and system intelligence.
- Maintains communications and coordination.
- Opens and updates Mozart Cases.
- Records activation time, instructions, status changes and response outcomes.
- Communicates with relevant stakeholders.

## IC Availability

Under the current staffing arrangement, the IC position specified by each SOP is staffed every day and is expected to be available and reachable.

## Immediate Life Safety Response

IF:

- `life_safety_threat = true`
- AND `formal_plan_activation = pending`

THEN SOC MAY:

1. Notify and dispatch EOT and Security.
2. Establish preliminary area control or cordoning.
3. Advise people to maintain distance or avoid the affected area.
4. Coordinate first aid.
5. Apply preliminary Access Control measures.
6. Open a Mozart Case and collect evidence.

## Mandatory Distinction

Immediate Life Safety Response is not formal plan activation.

AI MUST NOT state that SOC formally activated an emergency plan unless DCC declaration is confirmed.

## Minimum Plan Activation Message

SOC SHOULD communicate:

- Plan name and response level
- Incident time and location
- Designated IC position or identity
- ICP location when established
- Required responding stakeholders
- Primary communication channel
- Initial instruction or required action

## Closure

- DCC MUST declare de-escalation, stand down or plan termination.
- SOC MUST record the declaration time, authority and resulting status in Mozart or the applicable incident record.


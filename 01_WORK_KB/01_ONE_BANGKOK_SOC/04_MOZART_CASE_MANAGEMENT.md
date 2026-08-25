---
kb_id: WK-OBK-MOZ-001
title: Mozart Case Management Core Rules
domain: one_bangkok_soc
knowledge_type: workflow
status: active_draft
effective_date: 2026-08-25
source_authority: boss_confirmed
sensitivity: internal
owner: SOC
related_kb_ids:
  - WK-OBK-SOC-001
  - WK-OBK-CMD-001
---

# Mozart Case Management Core Rules

## Canonical Terminology

Use:

- `Case`
- `Case No.`
- `Event Type`
- `Task Template`
- `Findings / Resolution`
- `Resolve Case`

Mozart is a Case Management system. Do not replace `Case` with `Incident` when referring to the Mozart record.

## Normal Flow

`Receive → Verify → Assess → Open Case → Coordinate → Follow Up → Document → Resolve Case`

## Urgent Flow

`Receive → Open Case as Pending Verification → Notify/Dispatch → Verify → Assess/Classify → Coordinate → Follow Up → Document → Resolve Case`

## Urgent Case Criteria

Urgent handling applies to:

- CAT 1
- CAT 2
- Events with unknown CAT that may involve Life Safety
- Active Threat
- Maximum Security areas or events
- Events affecting multiple zones

Urgency is a response-handling condition and MUST NOT be treated as a replacement for CAT classification.

## Operator Requirements

Operator SHOULD:

- Select the correct Event Type.
- Record accurate time and location.
- Keep the Timeline chronological and factual.
- Identify responding and accountable parties.
- Follow up until findings, actions and resolution are known.
- Attach relevant evidence.
- Escalate according to authority and impact.

## Supervisor Requirements

Supervisor SHOULD verify:

- Event Type and CAT accuracy
- Timeline completeness
- Evidence relevance
- Correct stakeholder coordination
- Escalation status
- Active Case and SLA risk
- Findings / Resolution quality
- Handover completeness

## Security and Maintenance Cases

AI MUST distinguish Security Case from Maintenance Case.

When an event requires both, the Primary Owner, linked Case references, update responsibility and closure rule SHOULD be defined by the applicable workflow or Task Template.

## HOTO Rule

Security Case summaries MUST count actual cases and exclude False Alarm cases when the approved HOTO format requires that exclusion.

## AI Constraints

- AI MUST NOT invent a Case No., Event Type, CAT or status.
- AI MUST flag conflicting case totals or status data.
- AI MUST distinguish Case creation from formal emergency-plan activation.


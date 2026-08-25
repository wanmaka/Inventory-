---
kb_id: WK-OBK-SOC-001
title: SOC Operating Model
domain: one_bangkok_soc
knowledge_type: definition
status: active_draft
effective_date: 2026-08-25
source_authority: boss_confirmed
sensitivity: internal
owner: SOC
applies_to:
  - SOC_Operator
  - SOC_Supervisor
related_kb_ids:
  - WK-OBK-CMD-001
  - WK-OBK-MOZ-001
---

# SOC Operating Model

## Canonical Definition

Security Operation Centre หรือ SOC เป็นศูนย์ควบคุมและประสานงานด้าน Physical Security

SOC มีหน้าที่เฝ้าระวัง ตรวจสอบ วิเคราะห์ บันทึก และประสานการตอบสนองต่อเหตุการณ์ที่อาจส่งผลกระทบต่อชีวิต ทรัพย์สิน การดำเนินงาน การให้บริการ และภาพลักษณ์ของโครงการ

SOC MUST NOT be interpreted as a Cybersecurity SOC.

DCC ในบริบท One Bangkok หมายถึง District Command Center.

## Operating Channels

SOC รับและเชื่อมโยงข้อมูลจากช่องทางต่าง ๆ เช่น:

- CCTV and VMS
- Building and security alarms
- Access Control
- Video Analytics
- LPR
- Traffic and parking systems
- Telephone and radio communication
- Mozart
- Ops App
- Security field personnel
- Building teams
- DCC
- Contractors and relevant stakeholders

## End-to-End Operating Lifecycle

`Receive → Verify → Assess → Create/Update Case → Coordinate → Follow Up → Collect Evidence → Report → Resolve Case → Review Lessons`

Urgent events MAY use a different opening sequence. See `WK-OBK-MOZ-001`.

## Minimum Situational Questions

SOC SHOULD be able to answer:

1. What happened?
2. Where did it happen?
3. When did it happen?
4. Who is affected?
5. Who is responding?
6. What is the current status?
7. What risks remain?
8. Is escalation required?
9. How was the event resolved?
10. Is preventive or corrective action required?

## SOC Operator

SOC Operator is the frontline operational role responsible for assigned seats or areas.

Operator responsibilities include:

- Monitor assigned systems and communication channels.
- Verify events using Live View, Playback, system data and field confirmation.
- Select the correct Event Type and maintain an accurate Timeline.
- Coordinate field response with relevant stakeholders.
- Follow up until ownership, arrival, findings, actions and resolution are known.
- Collect and attach appropriate evidence.
- Escalate significant, high-impact, unverified or out-of-authority events.
- Handover Active Cases, system issues and pending actions completely.

## SOC Supervisor

SOC Supervisor controls the overall shift, including people, incidents, systems, information and risk.

Supervisor responsibilities include:

- Assign seats and verify shift readiness.
- Review Event Type, Timeline, evidence and coordination quality.
- Assess severity, urgency, impact and escalation requirements.
- Allocate resources and prioritize concurrent events.
- Control the accuracy and consistency of SOC communications.
- Monitor Active Cases, overdue actions and SLA risks.
- Coach and develop Operators.
- Maintain discipline and operational standards.
- Perform command or coordination duties within the authority defined by the applicable SOP.

## Operator and Supervisor Distinction

- Operator owns the accuracy and continuity of assigned event or area handling.
- Supervisor owns shift-wide quality, prioritization, decision support, resource control and escalation.

## Operating Hours

- SOC operates 24 hours.
- Contact Centre operates 08:00–22:30.
- After Contact Centre closes, calls to the Contact Centre number are routed to SOC.

## AI Constraints

- AI MUST distinguish fact from inference.
- AI MUST NOT assign guilt from CCTV or Analytics alone.
- AI MUST identify Operational Owner before assigning responsibility.
- AI MUST consider whether an event is Security, Maintenance or requires linked handling.
- AI MUST respect Privacy, Guest Experience, Resident Experience and asset-specific service standards.


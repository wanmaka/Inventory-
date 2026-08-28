---
kb_id: WK-OBK-IMP-001
title: "ทะเบียนควบคุมการนำเข้า _SENSES SOC (_SENSES SOC Import Control Register)"
description: "ทะเบียนควบคุมการนำข้อมูลทั้งหมดจาก Shared Drive _SENSES SOC เข้าสู่ One Bangkok SOC Master Knowledge Base โดยรักษา Revision, Source Authority, Sensitivity และ Source of Truth"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: boss_confirmed
sensitivity: internal
---

# ทะเบียนควบคุมการนำเข้า _SENSES SOC (_SENSES SOC Import Control Register)

| รายการ | ข้อมูล |
|---|---|
| Shared Drive | `_SENSES SOC` |
| Canonical Drive ID | `0AJpAwl9n5sLbUk9PVA` |
| Canonical Root | `SOC Management` + `SOC Team` |
| Authorization | `DEC-20260829-001` |
| Last Updated | 29 สิงหาคม 2026 |
| Status | Active |

## Authorization

Boss อนุญาตให้นำองค์ความรู้และ Source Material **ทั้งหมดที่เข้าถึงได้** จาก `_SENSES SOC` เข้าสู่ One Bangkok SOC Master Knowledge Base

## Source-of-Truth Model

- `_SENSES SOC` Google Drive = Raw Source / Current Source of Truth
- GitHub Inventory = Knowledge Structure / Register / Sanitized Extract / Cross-reference
- Approved/Current Revision = Operational Source ตามอำนาจของเอกสาร
- Draft/Historical/Example = เก็บเพื่อบริบทและประวัติ ห้ามใช้เป็น Approved Rule
- Legacy shared copies เช่น `SOC One Bangkok` / `SOC Management One Bangkok` ใช้เป็น Secondary Source เมื่อข้อมูลซ้ำกับ Canonical Shared Drive

## Public Repository Safety Control

เนื่องจาก Inventory Repository เป็น Public:

- ห้ามคัดลอก Credential, Password, Token หรือ Secret ลง Repository
- ห้ามคัดลอก Blacklist/Whitelist identity, PII, เบอร์โทรส่วนบุคคล, เลขบัตร, Passport, ทะเบียนรถรายบุคคล หรือข้อมูลบุคคลเฉพาะรายแบบ Raw
- ห้ามคัดลอก CCTV Evidence, ภาพบุคคล, Camera Credential, Sensitive Layout, Access Control secret หรือ Security configuration เชิงลึกที่ไม่ควรเผยแพร่
- ห้ามคัดลอก Individual Performance/HR Record หรือ Individual Work Schedule แบบ Raw
- ข้อมูลดังกล่าวให้เก็บเป็น Metadata/Reference/Sanitized Knowledge และชี้กลับไปยัง Raw Source ใน Drive

## Import Workstreams

| Workstream | KB / Register | Status |
|---|---|---|
| Canonical Source Map | `WK-OBK-SRC-001` | Active — exact Shared Drive root confirmed |
| Full Source Cross-reference | `REG-SRC-001` | Active — root/domain/current key sources indexed; recursive expansion continues |
| SOP/WI Register | `WK-OBK-SOP-001` | Active — document register imported; content/revision validation continues |
| Swimlane Library | `WK-OBK-SWL-001` | Active — PDF library imported; exact current Visio/PDF validation continues |
| Task Management Framework | `WK-OBK-TASK-001` | Active — definitions/category/type extracted from current native Sheet |
| Training & Assessment | `WK-OBK-TRN-001` | Active — structure and key source library imported; deep content extraction continues |
| SOC Operational Documents | `WK-OBK-DOC-001` | Active — domains and key sources indexed |
| Performance Evaluation | `WK-OBK-PE-001` | Active — source library imported; individual records restricted |
| Mozart Event/Task Source Master | `WK-OBK-MOZ-SRC-001` | Active — current source hierarchy and master candidate indexed |
| Mozart Canonical Rules | `WK-OBK-MOZ-001` | Pending Validation / extraction continues |
| CCTV Master | Planned Atomic KB | In Progress — source hierarchy indexed in `REG-SRC-001` |
| Guard Tour | Planned Atomic KB | In Progress — 2025/2026 records and monthly 2026 sources located |
| Virtual Patrol | Planned Atomic KB | In Progress — 2025/2026 record sources located |
| Security Awareness | Planned Library | In Progress — source discovery/validation required in canonical drive |
| Exercise Library | Planned Library | In Progress — TTX/GDX/AAR sources to be crawled from current drive |
| Reports & HOTO | Planned Library | In Progress — source discovery/validation required |
| Projects & Enhancement | Planned Portfolio | In Progress — Management Project domains indexed |
| Document Control | Planned Library | In Progress — canonical folder currently empty; SOP control sources exist elsewhere |
| Operator Task | Planned Library | In Progress — CI Traffic, Zone 1, Zone 2, Compound, Summary and CCTV Offline Checklist located |
| CCTV Record/Tracking | Planned Library | In Progress — Tracking/Request/Form/Record hierarchy indexed; raw evidence restricted |
| Activity Picture | Reference Index | In Progress — 2025/2026 folders located; raw images remain Drive-only |

## Import Procedure

1. Identify exact Canonical Source File/Folder and Drive ID.
2. Record Source Type, Revision, Signed/Approved indicator, Modified Date where available.
3. Classify `source_authority`, operational status and `sensitivity`.
4. Extract reusable operational knowledge only when content is readable and source status supports it.
5. Preserve `UNKNOWN` when content/status cannot be confirmed.
6. Cross-reference superseded/duplicate documents instead of silently replacing history.
7. Do not infer approval from filename alone when approval status is ambiguous.
8. For sensitive source, index metadata but do not reproduce raw restricted content in Public GitHub.

## Current Canonical Source Roots

### SOC Management — `1bbs9_mzwZkNiqW6QYGlDJNA_Tw08vviY`

- Task
- Work Schedule
- Report
- Project
- Procurement
- Document Control
- Performance Evaluation – SOC

### SOC Team — `1tTrpjlEBhNjD0KeGbPYjKk6QJ2mtg40f`

- SOC Documents
- SOP
- Training
- CCTV Document and Tracking
- Operator Task
- Activity Picture
- Weekly CCTV Operation Check

## Change Control

เมื่อพบ Source Revision ใหม่:

- เพิ่ม/อัปเดต Register
- เปลี่ยน Current Source pointer ไป Revision ล่าสุดที่ยืนยันได้
- เก็บ Revision เดิมเป็น Superseded/Historical Reference
- หาก Operational Rule เปลี่ยน ต้องอัปเดต Knowledge Item และ Decision/Terminology Register ที่เกี่ยวข้องตามผลกระทบ

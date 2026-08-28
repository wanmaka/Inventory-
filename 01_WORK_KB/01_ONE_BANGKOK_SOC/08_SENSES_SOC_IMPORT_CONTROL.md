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
| คำอธิบาย (Description) | ควบคุมการนำข้อมูลทั้งหมดจาก `_SENSES SOC` Drive เข้า KB ตามสิทธิ์ที่ Boss อนุมัติ |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 29 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## Authorization

อ้างอิง `DEC-20260829-001 — Full _SENSES SOC KB Import Authorization`

Boss อนุญาตให้นำองค์ความรู้และ Source Material ทั้งหมดที่เข้าถึงได้จาก Shared Drive `_SENSES SOC` เข้าสู่ One Bangkok SOC Master Knowledge Base

## Source-of-Truth Model

- `_SENSES SOC` Google Drive = Raw Source / Current Source of Truth
- GitHub Inventory = Knowledge Structure / Register / Sanitized Extract / Cross-reference
- Approved/Current Revision = Operational Source ตามอำนาจของเอกสาร
- Draft/Historical/Example = เก็บเพื่อบริบทและประวัติ ห้ามใช้เป็น Approved Rule

## Public Repository Safety Control

เนื่องจาก Inventory Repository เป็น Public:

- ห้ามคัดลอก Credential, Password, Token หรือ Secret ลง Repository
- ห้ามคัดลอก Blacklist/Whitelist identity, PII, เบอร์โทรส่วนบุคคล, เลขบัตร, Passport, ทะเบียนรถรายบุคคล หรือข้อมูลบุคคลเฉพาะรายแบบ Raw
- ห้ามคัดลอก CCTV Evidence, ภาพบุคคล, Camera Credential, Sensitive Layout, Access Control secret หรือ Security configuration เชิงลึกที่ไม่ควรเผยแพร่
- ข้อมูลดังกล่าวให้เก็บเป็น Metadata/Reference/Sanitized Knowledge เท่านั้น และชี้กลับไปยัง Raw Source ใน Drive

## Import Workstreams

| Workstream | Scope | Status |
|---|---|---|
| Source Map | โครงสร้าง `_SENSES SOC`, SOC One Bangkok, SOC Management One Bangkok | Completed |
| SOP/WI Register | SOP, WI, EP, SSHE, DCC, AD, LW, Forms/Records, Revision | Completed / Expanding |
| Swimlane Library | PDF Swimlane และ Operational Flow references | Completed / Expanding |
| Mozart Master | Event Type, Task Template, CAT, SLA, Responsible Role, SOP Reference | In Progress |
| CCTV Master | CCTV SOP, Request, Recording, Tracking, Qognify/Easy7 references | Authorized / Pending Import |
| Training & Assessment | OJT, General Training, FCC Training, Examination, Training Record, Weekly Training | Authorized / Pending Import |
| Security Awareness | Bulletin, Poster, Refresher, Communication material | Authorized / Pending Import |
| Exercise Library | TTX, GDX, AAR, Scenario, Corrective Actions | Authorized / Pending Import |
| Reports & HOTO | Reports, HOTO, Communication Templates, Daily/Weekly records | Authorized / Pending Import |
| Projects & Enhancement | Project, Procurement, Enhancement, Readiness, Improvement | Authorized / Pending Import |
| Document Control | Document register, Revision control, release/announcement records | Authorized / Pending Import |
| SOC Documents | Forms, Guidelines, Manuals, Operating documents | Authorized / Pending Import |
| Operator Task | Operator work instructions, task records, operational references | Authorized / Pending Import |
| CCTV Record/Tracking | Evidence/index records; Raw evidence remains in Drive | Authorized / Metadata Only where sensitive |
| Activity Picture | Training/operation activity images; Raw images remain in Drive | Authorized / Metadata Only |

## Import Rule

1. Identify Source File/Folder and Drive ID.
2. Record Source Type, Revision, Signed/Approved indicator, Modified Date where available.
3. Classify `source_authority` and `sensitivity`.
4. Extract reusable operational knowledge only when source content is readable and status supports it.
5. Preserve UNKNOWN when content/status cannot be confirmed.
6. Cross-reference superseded and duplicate documents rather than silently replacing history.
7. Do not infer approval from filename alone when approval status is ambiguous.

## Current Known Sources

- `SOC One Bangkok`
- `SOC Management One Bangkok`
- `02. Standard Operation Procedure (SOP)`
- `03. Training`
- `04. CCTV Record and Tracking`
- `05. Operator Task`
- `06. Activity Picture`
- `20260813_Mozart_Task_Template_Master_Data` (native Google Sheet; latest observed update 27 Aug 2026)
- `OB-SOP-DCC-0004 - Case & Task Template, CWO, PPM, SLA, and CAT Changes in Mozart Procedure Rev.01`

## Change Control

เมื่อพบ Source Revision ใหม่:
- เพิ่ม/อัปเดต Register
- เปลี่ยน Current Source pointer ไป Revision ล่าสุดที่ยืนยันได้
- เก็บ Revision เดิมเป็น Superseded/Historical Reference
- หาก Operational Rule เปลี่ยน ต้องอัปเดต Knowledge Item และ Decision/Terminology Register ที่เกี่ยวข้องตามผลกระทบ

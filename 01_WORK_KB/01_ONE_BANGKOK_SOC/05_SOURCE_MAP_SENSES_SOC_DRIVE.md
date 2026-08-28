---
kb_id: WK-OBK-SRC-001
title: "แผนที่แหล่งข้อมูล _SENSES SOC Google Drive (_SENSES SOC Drive Source Map)"
description: "กำหนด Shared Drive _SENSES SOC เป็น Source of Truth และบันทึกโครงสร้างหลักสำหรับการนำข้อมูลเข้าสู่ One Bangkok SOC Master Knowledge Base"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: boss_confirmed
sensitivity: internal
---

# แผนที่แหล่งข้อมูล _SENSES SOC Google Drive (_SENSES SOC Drive Source Map)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | Source Map ของ Shared Drive `_SENSES SOC` สำหรับค้นหา ตรวจสอบ และนำข้อมูลเข้าสู่ Master KB |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 29 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## Canonical Source

- Shared Drive: `_SENSES SOC`
- Google Shared Drive ID: `0AJpAwl9n5sLbUk9PVA`
- Root Structure ที่ยืนยันจาก Shared Drive โดยตรง:
  1. `SOC Management`
  2. `SOC Team`
- โฟลเดอร์ Shared/Transferred รุ่นก่อนที่มีชื่อ `SOC One Bangkok` หรือ `SOC Management One Bangkok` ให้ถือเป็น Secondary/Legacy Source เมื่อมีข้อมูลซ้ำกับ Canonical Shared Drive

## 1. SOC Management

โครงสร้างหลักที่ยืนยัน:

1. `01. Task`
2. `02. Work Schedule`
3. `03. Report`
4. `04. Project`
5. `05. Procurement`
6. `06. Document Control`
7. `x. Performance Evaluation - SOC`

### Source สำคัญที่พบ

- `Task Management ล่าสุด` — Native Google Sheet
- `OBK SOC Operator Work Schedule 2026`
- `OBK SOC-Management Work Schedule 2026`
- `OBK SOC Work Schedule 2026.xlsx`
- Project Domains: CCTV, Mozart, Virtual Patrol, Guard Tour, SOC Task, SOC KPI, Seating Plan, Video Analytics, ISO, Security Manning Post Check, Incident Command Station
- Performance Evaluation Library: Announcement, Blueprint, Rubric, Marking Guide/Key, Interview Guide, Score Card, Assessment Record, Exam Paper และ Scoring Spreadsheet

## 2. SOC Team

โครงสร้างหลักที่ยืนยัน:

1. `01. SOC Documents`
2. `02. Standard Operation Procedure (SOP)`
3. `03. Training`
4. `04. CCTV Document and Tracking`
5. `05. Operator Task`
6. `06. Activity Picture`
7. `ตรวจสอบ CCTV ประจำ Week ของ Operation.xlsx`

### 2.1 SOC Documents

พบ Domain หลัก:

- SOC Staff Information
- Announcement
- Mozart
- Guard Tour
- Virtual Patrol
- Blacklist / Whitelist / Watchlist
- Video Analytic
- OBK Layout
- CCTV
- Event
- Work Schedule
- Other / Supporting Information

### 2.2 Standard Operation Procedure (SOP)

โครงสร้าง:

- `01. Visio Swimlane`
- `02. PDF Swimlane`
- `03. SOP Document`
- `04. Support Document`
- `คำศัพท์ประจำแผนก.xlsx`
- `การส่ง Email ประกาศบังคับใช้ SOP.xlsx`

`03. SOP Document` แบ่งเป็น:

- `00. Draft`
- `01. Rev.00`
- `02. Rev.01`

Current Rev.01 ที่ยืนยันใน Drive:

- `OB_SOP_EP_0036 แผนการปฏิบัติการฉุกเฉินกรณีเหตุกราดยิง Rev.01 (Signed).pdf`
- `OB-SOP-DCC-0002 - BCP - Mozart Down - RV.01 - signed.pdf`

### 2.3 Training

- OJT Training
- General Training
- FCC Training
- Examination
- Training Record
- SOC Weekly Training

### 2.4 CCTV Document and Tracking

- Tracking
- CCTV Request Form
- Form
- CCTV Record

### 2.5 Operator Task

- CI Traffic
- Zone 1
- Zone 2
- Compound
- Summary
- CCTV Offline Checklist

### 2.6 Activity Picture

- 2025
- 2026

## Source Authority Rule

ลำดับการใช้แหล่งข้อมูล:

1. Signed/Approved + Current Revision
2. Approved Master Data / Current Controlled Record
3. Current Operational Practice
4. Previous Revision / Historical Record
5. Draft / Working File

ห้ามใช้ Draft, Historical Record หรือ Example เสมือนเป็น Approved Operational Rule

## Public Repository Data Handling

Inventory Repository เป็น Public จึงใช้หลักดังนี้:

- **นำเข้าเป็น Knowledge:** กฎ กระบวนการ Definition Workflow Template Structure Lessons Learned และข้อมูลที่เหมาะสมสำหรับเผยแพร่ใน KB
- **นำเข้าเป็น Reference Only:** ข้อมูลที่จำเป็นต่อการค้นคืนแต่ไม่ควรทำซ้ำใน Public Repository
- **ห้ามคัดลอก Raw Sensitive Data ลง Public Repository:** Credential, Password, Blacklist/Whitelist identity, ทะเบียนรถ, PII, CCTV Evidence, ภาพบุคคล/เหตุการณ์, รายละเอียดเชิงกายภาพหรือ Security Configuration ที่เพิ่มความเสี่ยง, Individual Performance/HR Record และข้อมูลจำกัดสิทธิ์อื่น
- ข้อมูลกลุ่ม Restricted ให้เก็บ `Source Title + Drive File/Folder ID + Classification + Purpose` เพื่อให้ AI กลับไปอ่าน Source ที่ได้รับอนุญาตเมื่อจำเป็น

## Import Scope

ตาม `DEC-20260829-001` ขอบเขตการนำเข้าครอบคลุม **ทุก Domain ที่เข้าถึงได้ใน `_SENSES SOC`** โดยไม่จำกัดเฉพาะ SOP ได้แก่ Operations, Systems, CCTV, Mozart, Guard Tour, Virtual Patrol, Training, Assessment, Security Awareness, Reports, HOTO, Projects, ISO, Events, Staff/Workforce Reference, Performance Evaluation, Forms, Records และ Supporting Documents

## Source Maintenance Rule

- Drive เป็น Source of Truth สำหรับ Raw Source และข้อมูลที่เปลี่ยนบ่อย
- KB เป็น Source of Truth สำหรับ Canonical Knowledge ที่ผ่านการ Validation
- เมื่อพบข้อมูลขัดกัน ต้องเปรียบเทียบ Revision/Approval/Modified Date/Document Control ก่อนอัปเดต KB
- AI ต้องระบุ `UNKNOWN` หาก Source ไม่เพียงพอ และห้ามเติมข้อมูลจากการเดา

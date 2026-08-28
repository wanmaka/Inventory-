---
kb_id: WK-OBK-SRC-001
title: "แผนที่แหล่งข้อมูล _SENSES SOC Google Drive (_SENSES SOC Drive Source Map)"
description: "ทะเบียนแหล่งข้อมูลและโครงสร้างโฟลเดอร์หลักของ Shared Drive _SENSES SOC ที่ใช้เป็น Source of Truth สำหรับการดึงและตรวจสอบข้อมูลของ One Bangkok SOC Knowledge Base"
owner: "SOC"
last_updated: 2026-08-28
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: current_operational_practice
sensitivity: internal
---

# แผนที่แหล่งข้อมูล _SENSES SOC Google Drive (_SENSES SOC Drive Source Map)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | แผนที่แหล่งข้อมูล Shared Drive `_SENSES SOC` สำหรับใช้ค้นหา ตรวจสอบ และนำข้อมูลเข้าสู่ Master Knowledge Base |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 28 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## หลักการใช้งาน

- Shared Drive `_SENSES SOC` เป็นแหล่งข้อมูลอ้างอิงหลักสำหรับเอกสารปฏิบัติงานของ SOC ที่สามารถเข้าถึงได้ผ่าน Google Drive connector
- เมื่อนำข้อมูลจาก Drive เข้า KB ต้องตรวจสอบ Revision, Status และประเภทเอกสารก่อนใช้งาน
- ลำดับความน่าเชื่อถือของเอกสาร SOP ใช้หลัก: Approved/Current Revision > Previous Revision > Draft
- Draft, Historical Record หรือ Example ห้ามถูกตีความเป็น Approved Operational Rule
- หากข้อมูลใน Drive ขัดกับ Existing KB ต้องทำ Gap/Conflict Review ก่อนแก้ไข Knowledge Item เดิม

## โครงสร้างหลัก: SOC One Bangkok

1. `01. SOC Documents`
2. `02. Standard Operation Procedure (SOP)`
3. `03. Training`
4. `04. CCTV Record and Tracking`
5. `05. Operator Task`
6. `06. Activity Picture`

## SOP Source Structure

ภายใต้ `02. Standard Operation Procedure (SOP)` พบโครงสร้างหลัก:

- `01. Visio Swimlane`
- `02. PDF Swimlane`
- `03. SOP Document`
- `04. Support Document`
- `คำศัพท์ประจำแผนก.xlsx`
- `การส่ง Email ประกาศบังคับใช้ SOP.xlsx`

ภายใต้ `03. SOP Document` พบการแบ่ง Revision:

- `00. Draft`
- `01. Rev.00`
- `02. Rev.01`

ภายใต้ `02. Rev.01` พบอย่างน้อย:

- `01.Emergency Plan (EP)`
- `05.DCC`

## Training Source Structure

ภายใต้ `03. Training` พบ:

1. `01. OJT Training`
2. `02. General Training`
3. `03. FCC Training`
4. `04. Examination`
5. `05. Training Record`
6. `06. SOC Weekly Training`

## CCTV Source Structure

ภายใต้ `04. CCTV Record and Tracking` พบ:

- `01. Tracking`
- `02. CCTV Record`

## โครงสร้างหลัก: SOC Management One Bangkok

1. `01. Task`
2. `02. Work Schedule`
3. `03. Report`
4. `04. Project`
5. `05. Procurement`
6. `06. Document Control`
7. `Project Sun`
8. `Calendar May - Jun`

## Import Priority

1. SOP / Emergency Plan / Swimlane / Definitions
2. SOC Documents / WI / Guideline / Forms
3. CCTV / Camera / Tracking / Qognify-related data
4. Training / Examination / OJT / Weekly Training
5. Mozart / Operator Task / Guard Tour / Operational Workflow
6. Project / Report / Document Control / Work Schedule
7. Activity Picture / Historical Record ใช้เป็น Supporting Reference

## ข้อจำกัดของ AI

- AI ต้องไม่เดาว่าไฟล์ใดเป็น Current/Approved หากชื่อไฟล์หรือ Revision ไม่เพียงพอที่จะยืนยัน
- AI ต้องตรวจสอบเอกสารฉบับล่าสุดและสถานะก่อนใช้เป็นข้อกำหนดปฏิบัติงาน
- ไฟล์ที่เปลี่ยนแปลงบ่อยควรอ้างอิงจาก Drive ล่าสุดแทนการบันทึกรายละเอียดคงที่ใน KB
- ข้อมูลที่มีความละเอียดอ่อนหรือจำกัดสิทธิ์ต้องคงระดับ `internal` หรือสูงกว่าตาม Source Document

## แหล่งข้อมูล

- Google Shared Drive: `_SENSES SOC`
- Folder: `SOC One Bangkok`
- Folder: `SOC Management One Bangkok`
- Verified via connected Google Drive access on 28 August 2026

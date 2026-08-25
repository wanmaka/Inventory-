---
kb_id: GOV-KB-001
title: "โครงสร้างองค์ความรู้สำหรับ AI (AI-ready Knowledge Schema)"
description: "กำหนด Metadata คำศัพท์ควบคุม สถานะ รูปแบบเนื้อหา และหลักการตั้งรหัสสำหรับทุก Knowledge Item"
owner: "Wanmaka Promchoto"
last_updated: 2026-08-25
status: active
domain: shared_governance
knowledge_type: schema
source_authority: boss_confirmed
sensitivity: internal
---

# โครงสร้างองค์ความรู้สำหรับ AI (AI-ready Knowledge Schema)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | กำหนด Metadata คำศัพท์ควบคุม สถานะ และรูปแบบมาตรฐานสำหรับทุก KB |
| เจ้าของข้อมูล (Owner) | Wanmaka Promchoto |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## Metadata บังคับ (Required Metadata)

ทุก Knowledge Item ต้องมีอย่างน้อย:

```yaml
---
kb_id: WK-OBK-EXAMPLE-001
title: "ชื่อภาษาไทย (English Title)"
description: "อธิบายว่า KB นี้เกี่ยวกับอะไรและใช้เพื่ออะไร"
owner: "Knowledge Owner"
last_updated: 2026-08-25
status: active
domain: one_bangkok_soc
knowledge_type: operational_rule
source_authority: boss_confirmed
sensitivity: internal
---
```

Metadata สี่รายการต่อไปนี้ต้องปรากฏใน YAML และตารางข้อมูลด้านบนของทุกไฟล์:

1. คำอธิบาย (Description)
2. เจ้าของข้อมูล (Owner)
3. อัปเดตล่าสุด (Last Updated)
4. สถานะ (Status)

## มาตรฐานภาษา (Language Standard)

- เนื้อหาหลักต้องใช้ภาษาไทย
- หัวข้อใช้รูปแบบ `ชื่อภาษาไทย (English Title)` เมื่อภาษาอังกฤษช่วยระบุความหมาย
- ใช้ภาษาอังกฤษกับคำเฉพาะ ชื่อระบบ ชื่อตำแหน่ง และ Controlled Value
- การกล่าวถึงคำสำคัญครั้งแรกควรระบุชื่อเต็มและตัวย่อ
- ห้ามแปลชื่อระบบหรือชื่อทางการจนความหมายเปลี่ยน
- คำศัพท์มาตรฐาน Alias และคำที่ห้ามใช้ต้องอ้างอิง `REG-TERM-001`

## สถานะการใช้คำ (Term Usage State)

| ค่า | วิธีใช้ |
|---|---|
| `CANONICAL` | คำมาตรฐานที่ต้องใช้เป็นค่าเริ่มต้น |
| `CONTEXT_ONLY` | ใช้เฉพาะบริบทที่กำหนด |
| `DO_NOT_USE` | ห้ามใช้ในบริบทที่ระบุ |
| `PENDING_VALIDATION` | ยังต้องตรวจสอบก่อนใช้เป็นข้อเท็จจริง |

`Term Usage State` ใช้ควบคุมคำศัพท์ภายใน `REG-TERM-001` และไม่ใช่ `Operational Status` ของ Knowledge Item

## ค่า Domain

- `one_bangkok_soc`
- `personal_business`
- `boss_profile`
- `shared_governance`
- `register`

## ประเภทองค์ความรู้ (Knowledge Type)

- `index`
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

## สถานะการใช้งาน (Operational Status)

| ค่าในระบบ | ชื่อแสดงผล | วิธีใช้ |
|---|---|---|
| `draft` | ร่าง (Draft) | กำลังจัดทำ ยังไม่ใช้เป็นข้อมูลอ้างอิงหลัก |
| `pending_validation` | รอตรวจสอบ (Pending Validation) | เนื้อหาพร้อมเบื้องต้น แต่รอผู้มีอำนาจหรือเอกสารยืนยัน |
| `active` | ใช้งานจริง (Active) | เป็นข้อมูลปัจจุบันและใช้เป็นข้อมูลอ้างอิงได้ |
| `active_update_required` | ใช้งานจริง—ต้องอัปเดต (Active—Update Required) | ยังใช้ได้ แต่ต้องแจ้งข้อจำกัดและเร่งทบทวน |
| `suspended` | ระงับการใช้งาน (Suspended) | ห้ามใช้จนกว่าจะตรวจสอบหรือแก้ไข |
| `superseded` | ถูกแทนที่ (Superseded) | มี Knowledge Item ฉบับใหม่มาแทน |
| `archived` | จัดเก็บถาวร (Archived) | เก็บเพื่อประวัติ ไม่ใช้ปฏิบัติงาน |

## อำนาจของแหล่งข้อมูล (Source Authority)

- `law_or_regulation`
- `approved_policy`
- `approved_sop_wi`
- `approved_master_data`
- `boss_confirmed`
- `current_operational_practice`
- `working_draft`
- `example`
- `ai_inference`

## ระดับความละเอียดอ่อน (Sensitivity)

- `public`
- `internal`
- `restricted`
- `general_personal`
- `sensitive_personal`

## โครงเนื้อหามาตรฐาน (Content Structure)

Knowledge Item ควรเลือกใช้หัวข้อที่เกี่ยวข้องจากรายการต่อไปนี้:

1. วัตถุประสงค์ (Purpose)
2. คำนิยามหรือกฎหลัก (Canonical Definition or Rule)
3. ขอบเขตการใช้งาน (Scope and Applicability)
4. บทบาทและอำนาจ (Roles and Authority)
5. Trigger หรือ Preconditions
6. Inputs
7. ขั้นตอนการปฏิบัติ (Workflow)
8. ตรรกะการตัดสินใจ (Decision Logic)
9. ข้อยกเว้นและข้อจำกัด
10. หลักฐานและบันทึก
11. Outputs
12. การยกระดับ
13. เกณฑ์ปิดงาน
14. ข้อจำกัดของ AI
15. แหล่งข้อมูล
16. ประวัติการเปลี่ยนแปลง

## ภาษาบังคับ (Normative Language)

- `MUST / ต้อง` = ข้อกำหนดบังคับ
- `MUST NOT / ห้าม` = การกระทำที่ไม่อนุญาต
- `SHOULD / ควร` = แนวทางที่แนะนำ
- `MAY / สามารถ` = ดำเนินการได้ตามเงื่อนไข
- `IF–THEN` = ตรรกะการตัดสินใจ
- `UNKNOWN` = ไม่มีข้อมูลและห้าม AI เดา

## หลัก Atomic Knowledge

แต่ละ Knowledge Item ควรมีหัวข้อหลักเดียวและอ้างอิงด้วย Stable ID ได้

AI ห้ามใช้ Example, Historical Record หรือ Draft เสมือนเป็น Approved Operational Rule

## รูปแบบรหัส (Naming Convention)

`[DOMAIN]-[TOPIC]-[TYPE]-[SEQUENCE]`

ตัวอย่าง:

- `WK-OBK-CMD-001` — กฎ Command ของ One Bangkok
- `WK-OBK-ZONE-001` — Zone Master ของ One Bangkok
- `WK-BIZ-GF-001` — องค์ความรู้ธุรกิจ Get Fruit
- `BP-PRO-001` — Professional Profile ของ Boss
- `GOV-AI-001` — AI Governance
- `REG-DEC-001` — Decision Register
- `REG-TERM-001` — Terminology Register

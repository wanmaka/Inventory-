---
kb_id: WK-OBK-MOZ-001
title: "กฎหลักการบริหาร Mozart Case (Mozart Case Management Core Rules)"
description: "กำหนดคำศัพท์ วงจร Normal และ Urgent Case บทบาท SOC Operator/SOC Supervisor และข้อจำกัดการใช้ข้อมูล Mozart"
owner: "SOC"
last_updated: 2026-08-25
status: pending_validation
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: boss_confirmed
sensitivity: internal
related_kb_ids:
  - WK-OBK-SOC-001
  - WK-OBK-CMD-001
  - REG-TERM-001
---

# กฎหลักการบริหาร Mozart Case (Mozart Case Management Core Rules)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | คำศัพท์ วงจร Normal/Urgent Case และบทบาทควบคุมคุณภาพ Mozart |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | รอตรวจสอบ (Pending Validation) |

## คำศัพท์หลัก (Canonical Terminology)

ให้ใช้คำต่อไปนี้:

- `Case`
- `Case No.`
- `Event Type`
- `Task Template`
- `Findings / Resolution`
- `Resolve Case`
- `Close Case`

Mozart เป็น Case Management System เมื่อกล่าวถึง Record ใน Mozart ห้ามแทนคำว่า `Case` ด้วย `Incident`

## วงจรปกติ (Normal Flow)

`รับข้อมูล → ตรวจสอบ → ประเมิน → เปิด Case → ประสานงาน → ติดตาม → บันทึก Findings / Resolution → SOC Supervisor ตรวจสอบ → SOC Operator Resolve Case → SOC Supervisor Close Case`

## วงจรเร่งด่วน (Urgent Flow)

`รับข้อมูล → เปิด Case ก่อน Verification → แจ้งหรือ Dispatch → ตรวจสอบ → ประเมินและจัดประเภท → ประสานงาน → ติดตาม → บันทึก Findings / Resolution → SOC Supervisor ตรวจสอบ → SOC Operator Resolve Case → SOC Supervisor Close Case`

`Pending Verification` เป็นคำอธิบายช่วงหนึ่งของ Workflow ไม่ใช่ Mozart Case Status

## เกณฑ์ Urgent Case

ให้ใช้ Urgent Handling กับ:

- CAT 1
- CAT 2
- เหตุที่ยังไม่ทราบ CAT แต่เกี่ยวข้องกับ Life Safety
- Active Threat
- พื้นที่หรือเหตุ Maximum Security
- เหตุที่กระทบหลาย Zone

Urgency เป็นเงื่อนไขการตอบสนอง ห้ามใช้แทน CAT Classification

## หน้าที่ SOC Operator

SOC Operator ควร:

- เลือก Event Type ให้ถูกต้อง
- บันทึกเวลาและสถานที่อย่างแม่นยำ
- บันทึก Timeline ตามลำดับเวลาและข้อเท็จจริง
- ระบุผู้ตอบสนองและผู้รับผิดชอบ
- ติดตามจนทราบ Findings การดำเนินการ และผลยุติ
- แนบหลักฐานที่เกี่ยวข้อง
- จัดทำ Findings / Resolution ให้ครบถ้วน
- ดำเนินการ Resolve Case หลัง SOC Supervisor ตรวจสอบ
- ยกระดับตามอำนาจและผลกระทบ

## หน้าที่ SOC Supervisor

SOC Supervisor ควรตรวจ:

- ความถูกต้องของ Event Type และ CAT
- ความครบถ้วนของ Timeline
- ความเหมาะสมของ Evidence
- การประสานหน่วยงานที่ถูกต้อง
- สถานะการยกระดับ
- Active Case และความเสี่ยงด้าน SLA
- คุณภาพ Findings / Resolution
- ความครบถ้วนของ Handover
- ความครบถ้วนของข้อมูลก่อนให้ Operator ดำเนินการ Resolve Case
- ดำเนินการ Close Case สำหรับ Security Case ทุกกรณีที่อยู่ภายใต้ SOC Workflow

## Security Case และ Maintenance Case

AI ต้องแยก Security Case ออกจาก Maintenance Case

Security Case อยู่ภายใต้ SOC Workflow เมื่อ Case ใช้ `Security Type` และถูกส่งให้ SOC รับผิดชอบ ไม่ว่าผู้เปิด Case จะเป็น SOC, BMO, Retail Operation หรือ Contact Centre

Security Case ดังกล่าวต้องให้ SOC Operator ดำเนินการ Resolve Case หลัง SOC Supervisor ตรวจสอบ และให้ SOC Supervisor เป็นผู้ Close Case ทุกกรณี

กฎนี้ไม่ให้อำนาจ SOC Supervisor ปิด Maintenance Case, Retail Case หรือ Case ของหน่วยงานอื่นที่ไม่ใช่ Security Case ภายใต้ SOC Workflow

หากเหตุเดียวต้องใช้ทั้งสอง Case ต้องกำหนด Primary Owner, Linked Case Reference, ผู้รับผิดชอบการอัปเดต และเกณฑ์ปิด Case ตาม Workflow หรือ Task Template ที่เกี่ยวข้อง

## กฎ HOTO

การสรุป Security Case สำหรับ HOTO ต้องนับเฉพาะ Case จริงและไม่รวม False Alarm ตามรูปแบบที่ Boss อนุมัติ

## ข้อจำกัดของ AI (AI Constraints)

- ห้ามสร้าง Case No., Event Type, CAT หรือ Status ขึ้นเอง
- ห้ามใช้ `Pending Verification` เป็น Mozart Case Status
- ต้องแจ้งเมื่อยอดรวม Case หรือ Status ขัดแย้งกัน
- ต้องแยกการเปิด Case ออกจากการประกาศใช้แผนฉุกเฉิน
- ห้ามให้ SOC Supervisor ปิด Case ที่ไม่ใช่ Security Case ภายใต้ SOC Workflow

## สิ่งที่ต้องตรวจสอบต่อ (Pending Validation)

ต้องตรวจเทียบกับ Mozart Master Data, Event Type Inventory, Task Template และ Classification/Escalation Matrix ฉบับล่าสุดก่อนเปลี่ยนสถานะเป็น `active`

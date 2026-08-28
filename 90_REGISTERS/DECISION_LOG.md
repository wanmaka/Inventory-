---
kb_id: REG-DEC-001
title: "ทะเบียนการตัดสินใจหลัก (Master Decision Log)"
description: "บันทึก Decision ที่ Boss ยืนยัน พร้อมวันที่ สถานะ และหลักการไม่แก้ไขประวัติย้อนหลังโดยไม่มีร่องรอย"
owner: "Wanmaka Promchoto"
last_updated: 2026-08-29
status: active
domain: register
knowledge_type: decision_record
source_authority: boss_confirmed
sensitivity: internal
---

# ทะเบียนการตัดสินใจหลัก (Master Decision Log)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | บันทึก Decision ที่ Boss ยืนยัน พร้อมวันที่และสถานะ |
| เจ้าของข้อมูล (Owner) | Wanmaka Promchoto |
| อัปเดตล่าสุด (Last Updated) | 29 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## Decision ที่ยืนยันเมื่อวันที่ 25 สิงหาคม 2026

### DEC-20260825-001 — โครงสร้าง KB สองเสาหลัก
- สถานะ: Approved
- Decision: KB Master มีสองเสาหลัก ได้แก่ Work Knowledge Base และ Boss Profile & Personal Context

### DEC-20260825-002 — การแยก Work Domain
- สถานะ: Approved
- Decision: One Bangkok/SOC Work KB และ Personal Business KB ต้องเป็นคนละ Domain

### DEC-20260825-003 — ขอบเขต Personal Context
- สถานะ: Approved
- Decision: Boss Profile ครอบคลุม Professional Identity, Working Style, สุขภาพ ประกัน วันเกิด ชีวิตส่วนตัว และ Personal Context ที่ Boss อนุญาต

### DEC-20260825-004 — วิธีใช้ Personal Context
- สถานะ: Approved
- Decision: General Personal Context ใช้ปรับคำตอบได้ตามปกติ ส่วน Sensitive Personal Context ใช้เฉพาะเมื่อเกี่ยวข้องโดยตรงหรือ Boss เป็นผู้ถาม และห้ามผสมใน Work Output

### DEC-20260825-005 — ขอบเขตอำนาจ AI
- สถานะ: Approved
- Decision: AI เป็น Knowledge Assistant และ Decision Support เท่านั้น ไม่มีอำนาจประกาศ อนุมัติ ตัดสินข้อเท็จจริง หรือสั่งการแทน DCC, IC, SOC Supervisor หรือผู้มีอำนาจของ One Bangkok

### DEC-20260825-006 — อำนาจประกาศแผนฉุกเฉิน
- สถานะ: Superseded
- แทนที่โดย: DEC-20260825-016
- Decision: DCC ประกาศใช้ ยกระดับ ลดระดับ Stand Down และยุติแผน แต่ละ SOP กำหนด Field IC ล่วงหน้า Field IC สั่งการหน้างาน และ SOC สื่อสารไปยังหน่วยงานที่เกี่ยวข้อง

### DEC-20260825-007 — Immediate SOC Protective Actions
- สถานะ: Approved
- Decision: ก่อนการประกาศใช้แผน SOC สามารถ Dispatch EOT/Security ควบคุมพื้นที่เบื้องต้น แนะนำให้หลีกเลี่ยงพื้นที่ ประสาน First Aid ควบคุม Access เบื้องต้น และเปิด Mozart Case พร้อมรวบรวม Evidence

### DEC-20260825-008 — ขอบเขต Urgent Case
- สถานะ: Approved
- Decision: Urgent Handling ครอบคลุม CAT 1, CAT 2 และเหตุที่ยังไม่ทราบ CAT แต่เกี่ยวข้องกับ Life Safety, Active Threat, Maximum Security หรือหลาย Zone และสามารถเปิด Case ก่อน Verification ได้

### DEC-20260825-009 — Zone 2 Master
- สถานะ: Approved
- Decision: Zone 2 ประกอบด้วย Tower 4, The Storeys, Andaz Hotel และ Pathom House Hotel ซึ่งมีสถานะ Operating ณ เดือนสิงหาคม 2026

### DEC-20260825-010 — One Power Classification
- สถานะ: Approved
- Decision: One Power เป็นพื้นที่ Maximum Security อย่างเป็นทางการ

### DEC-20260825-011 — Public Repository
- สถานะ: Approved by Repository Owner
- Decision: Owner รับทราบว่า Inventory Repository เป็น Public และสั่งให้ดำเนินการเผยแพร่ KB

### DEC-20260825-012 — มาตรฐานภาษา KB
- สถานะ: Approved
- Decision: เนื้อหา KB ใช้ภาษาไทยเป็นหลัก ภาษาอังกฤษใช้กับคำเฉพาะ ชื่อระบบ ชื่อตำแหน่ง และหัวข้อรูปแบบไทย–อังกฤษ

### DEC-20260825-013 — Metadata บังคับ
- สถานะ: Approved
- Decision: ทุก KB ต้องมี Description, Owner, Last Updated และ Status

### DEC-20260825-014 — Operational Status
- สถานะ: Approved
- Decision: Status ต้องบอกสถานะการใช้งานจริง โดยใช้ Draft, Pending Validation, Active, Active—Update Required, Suspended, Superseded และ Archived

### DEC-20260825-015 — การแทนที่ KB Baseline
- สถานะ: Approved
- Decision: ลบ Working Tree เดิมและแทนที่ด้วย KB ชุดใหม่ที่เป็นภาษาไทยเป็นหลักและใช้ Metadata/Status มาตรฐาน โดยคง Git History เพื่อการตรวจสอบย้อนหลัง

### DEC-20260825-016 — คำมาตรฐานด้านการสั่งการเหตุฉุกเฉิน
- สถานะ: Approved
- Decision: ใช้ชื่อทางการ `Security Operation Centre: SOC` และ `District Command Centre: DCC` ใช้ `IC` เป็นคำมาตรฐานแทน `Field IC` โดย IC สั่งการ ณ จุดเกิดเหตุหรือ ICP และใช้ `Stand Down (ยุติแผน)` เป็นความหมายเดียวกับการยุติแผน

### DEC-20260825-017 — การ Resolve และ Close Security Case
- สถานะ: Approved
- Decision: ใช้ `Case No.` เป็นคำมาตรฐาน และ `Pending Verification` เป็นคำอธิบาย Workflow ไม่ใช่ System Status โดย SOC Operator ดำเนินการ Resolve Case หลัง SOC Supervisor ตรวจสอบ และ SOC Supervisor เป็นผู้ Close Security Case ทุกกรณีที่อยู่ภายใต้ SOC Workflow รวมถึง Case ที่ BMO, Retail Operation หรือ Contact Centre เปิดด้วย `Security Type` และส่งให้ SOC รับผิดชอบ

### DEC-20260825-018 — บทบาท Security และ Common Infrastructure
- สถานะ: Approved
- Decision: SMT หมายถึง Security Management Team ซึ่งบริหารและควบคุม Security ครอบคลุม In-Building, Traffic และ Common Infrastructure; Security Officer ครอบคลุมเจ้าหน้าที่ PCS และ G4S; Security Supervisor หมายถึงหัวหน้าชุดรักษาความปลอดภัย และ CI มีชื่อเต็มทางการว่า Common Infrastructure

### DEC-20260825-019 — Terminology Register
- สถานะ: Approved
- Decision: กำหนด `REG-TERM-001` เป็นแหล่งอ้างอิงกลางสำหรับ Canonical Term, Alias, คำที่ห้ามใช้ และคำที่รอตรวจสอบ โดย AI และเอกสารใหม่ต้องใช้ Canonical Term ตามทะเบียน

## Decision ที่ยืนยันเมื่อวันที่ 29 สิงหาคม 2026

### DEC-20260829-001 — Full _SENSES SOC KB Import Authorization
- สถานะ: Approved
- Decision: Boss อนุญาตให้นำองค์ความรู้และแหล่งข้อมูลทั้งหมดที่เข้าถึงได้จาก Shared Drive `_SENSES SOC` เข้าสู่ One Bangkok SOC Master Knowledge Base โดยให้ Google Drive เป็น Source of Truth สำหรับ Source Material และให้ Inventory/KB ทำหน้าที่เป็นโครงสร้างความรู้ ทะเบียนอ้างอิง และข้อมูลที่ผ่านการสกัดตามสถานะเอกสาร
- Control: เอกสาร Approved/Current Revision สามารถใช้เป็น Operational Source ได้ตามอำนาจของเอกสาร; Draft/Historical/Example ต้องรักษาสถานะเดิมและห้ามใช้เสมือน Approved Rule
- Data Handling: เนื่องจาก Inventory Repository เป็น Public ข้อมูล Restricted, PII, Blacklist/Whitelist identity, ทะเบียนรถ, CCTV Evidence, Credential, รายละเอียดเชิงกายภาพหรือความปลอดภัยที่ไม่ควรเผยแพร่ และข้อมูลบุคคลรายคน ให้บันทึกเฉพาะ Metadata/Reference/Sanitized Knowledge ใน Repository โดยเก็บ Raw Source ไว้ใน `_SENSES SOC` Drive

## กฎการจัดการ Decision (Decision Handling Rule)

AI ต้องรักษา Approved Decision จนกว่า Boss จะเปลี่ยนหรือ Supersede

เมื่อ Decision เปลี่ยน ต้องสร้าง Decision ID ใหม่และกำหนด Decision เดิมเป็น `Superseded` ห้ามแก้ประวัติย้อนหลังโดยไม่มีร่องรอย

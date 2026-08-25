---
kb_id: ROOT-README-001
title: "คลังองค์ความรู้หลัก (KB Master Inventory)"
description: "สารบัญกลางและจุดเริ่มต้นสำหรับเข้าถึงองค์ความรู้ด้านงาน ตัวตน วิธีทำงาน และบริบทส่วนบุคคลของ Wanmaka Promchoto"
owner: "Wanmaka Promchoto"
last_updated: 2026-08-25
status: active
domain: shared_governance
knowledge_type: index
sensitivity: internal
language: th-TH
---

# คลังองค์ความรู้หลัก (KB Master Inventory)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | สารบัญกลางสำหรับเข้าถึงองค์ความรู้ด้านงาน ตัวตน วิธีทำงาน และบริบทส่วนบุคคลของ Boss |
| เจ้าของข้อมูล (Owner) | Wanmaka Promchoto |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## วัตถุประสงค์ (Purpose)

Repository นี้เป็นแหล่งข้อมูลกลางที่จัดทำในรูปแบบ AI-ready เพื่อให้ AI และผู้ใช้งานสามารถ:

- ค้นหาและอ้างอิงข้อมูลตามสถานะที่กำหนด
- แยกข้อเท็จจริง กฎ กระบวนการ ความชอบ และข้อเสนอแนะออกจากกัน
- ตรวจสอบเจ้าของข้อมูล วันที่อัปเดต แหล่งอำนาจ และสถานะการใช้งาน
- ตรวจจับข้อมูลซ้ำ ข้อมูลขัดแย้ง และข้อมูลที่ถูกแทนที่
- เชื่อมโยง SOP, WI, Swimlane, Mozart, Systems, Training, Exercise และ Decisions

## บทบาทของ AI (AI Role)

AI เป็น Knowledge Assistant และ Decision Support เท่านั้น

AI สามารถวิเคราะห์ Challenge และเสนอแนวทางได้ แต่ไม่มีอำนาจประกาศแผน อนุมัติ ตัดสินข้อเท็จจริง หรือสั่งการแทน DCC, IC, SOC Supervisor และผู้มีอำนาจของ One Bangkok

อ่านกฎฉบับเต็มที่ [ธรรมาภิบาล AI (AI Governance)](00_AI_GOVERNANCE.md)

## โครงสร้างองค์ความรู้ (Knowledge Architecture)

Repository มีสองเสาหลัก:

1. [องค์ความรู้ด้านงาน (Work Knowledge Base)](01_WORK_KB/README.md)
   - One Bangkok / SOC Work KB
   - Personal Business KB ซึ่งแยกจาก One Bangkok/SOC อย่างชัดเจน
2. [ประวัติและระบบการทำงานของ Boss (Boss Profile & Personal Context)](02_BOSS_PROFILE/README.md)
   - Professional Identity and Personal Operating System
   - General Personal Context
   - Sensitive Personal Context

ไฟล์ Governance และ Registers ที่ Root เป็นกลไกควบคุม ไม่ใช่เสาหลักเพิ่มเติม

- [ธรรมาภิบาล AI (AI Governance)](00_AI_GOVERNANCE.md)
- [โครงสร้างองค์ความรู้สำหรับ AI (AI-ready Knowledge Schema)](00_KB_SCHEMA.md)
- [ทะเบียนคำศัพท์และคำควบคุม (Terminology Register)](90_REGISTERS/TERMINOLOGY_REGISTER.md)
- [ทะเบียนองค์ความรู้ (Knowledge Inventory)](90_REGISTERS/KNOWLEDGE_INVENTORY.md)
- [ทะเบียนการตัดสินใจ (Decision Log)](90_REGISTERS/DECISION_LOG.md)

## ลำดับการอ่านสำหรับ AI (AI Reading Order)

1. `README.md`
2. `00_AI_GOVERNANCE.md`
3. `00_KB_SCHEMA.md`
4. `90_REGISTERS/TERMINOLOGY_REGISTER.md`
5. `90_REGISTERS/KNOWLEDGE_INVENTORY.md`
6. อ่านเฉพาะ Domain และ Knowledge Item ที่เกี่ยวข้องกับคำถาม
7. ตรวจ `90_REGISTERS/DECISION_LOG.md` เมื่อพบข้อมูลหลายเวอร์ชัน

## ลำดับอำนาจของแหล่งข้อมูล (Source Authority Order)

เมื่อข้อมูลขัดแย้งกัน ให้ใช้ลำดับดังนี้:

1. กฎหมาย ข้อกำหนด หรือเอกสารองค์กรที่ Approved และยังมีผล
2. SOP, WI, Policy, Master Data หรือ Authority Matrix ฉบับ Approved ล่าสุด
3. Decision ที่ Boss ยืนยันอย่างชัดเจน
4. Current Operational Practice ที่ระบุวันที่และผู้ยืนยัน
5. Draft, Workshop Note หรือ Working Document
6. Example
7. AI Inference

AI ห้ามรวมข้อมูลที่ขัดแย้งกันโดยไม่แจ้งผู้ใช้

## การเปิดเผย Repository (Repository Visibility)

Repository นี้เป็น Public ตามการตัดสินใจของ Owner เมื่อวันที่ 25 สิงหาคม 2026

ห้ามจัดเก็บ Password, API Token, Secret Key, Access Credential หรือข้อมูลที่สามารถใช้เข้าสู่ระบบได้

## สถานะชุดข้อมูลตั้งต้น (Baseline Status)

ข้อมูลที่ยังไม่ได้ตรวจเทียบกับเอกสาร Approved ต้องใช้สถานะ `draft`, `pending_validation` หรือ `active_update_required` ตามระดับความพร้อม ห้าม AI ยกระดับเป็น `active` เอง

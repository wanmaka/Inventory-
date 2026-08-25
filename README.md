---
kb_id: ROOT-README-001
title: KB Master Inventory
status: active
effective_date: 2026-08-25
owner: Wanmaka Promchoto
repository_visibility: public
language: th-TH
---

# KB Master Inventory

คลังองค์ความรู้แบบ AI-ready สำหรับรวบรวมความรู้การทำงาน ตัวตน วิธีทำงาน และบริบทส่วนบุคคลของ Wanmaka Promchoto

## Purpose

Repository นี้ทำหน้าที่เป็นแหล่งข้อมูลกลางที่ AI และผู้ใช้งานสามารถ:

- ค้นหาและอ้างอิงข้อมูลที่ได้รับการยืนยันแล้ว
- แยกข้อเท็จจริง กฎ กระบวนการ ความชอบ และข้อเสนอแนะออกจากกัน
- ตรวจสอบ Source Authority, Effective Date และสถานะของข้อมูล
- ตรวจจับข้อมูลซ้ำ ข้อมูลขัดแย้ง และข้อมูลที่ถูกแทนที่
- เชื่อมโยง SOP, Workflow, Roles, Systems, Training, Exercise และ Decisions

## AI Role

AI เป็น Knowledge Assistant และ Decision Support เท่านั้น

AI สามารถวิเคราะห์ Challenge และเสนอแนวทางได้ แต่ไม่มีอำนาจประกาศแผน อนุมัติ ตัดสินข้อเท็จจริง หรือสั่งการแทน DCC, IC, SOC Supervisor และผู้มีอำนาจของ One Bangkok

อ่านกฎฉบับเต็มที่ [00_AI_GOVERNANCE.md](00_AI_GOVERNANCE.md)

## Knowledge Architecture

Repository มีสองเสาหลัก:

1. [Work Knowledge Base](01_WORK_KB/README.md)
   - One Bangkok / SOC Work KB
   - Personal Business KB ซึ่งแยกจาก One Bangkok/SOC อย่างชัดเจน
2. [Boss Profile & Personal Context](02_BOSS_PROFILE/README.md)
   - Professional Identity and Personal Operating System
   - General Personal Context
   - Sensitive Personal Context

ไฟล์ Governance และ Registers ที่ Root เป็นกลไกควบคุม ไม่ใช่เสาหลักเพิ่มเติม

## Recommended Reading Order for AI

1. `README.md`
2. `00_AI_GOVERNANCE.md`
3. `00_KB_SCHEMA.md`
4. `90_REGISTERS/KNOWLEDGE_INVENTORY.md`
5. อ่านเฉพาะ Domain และ Knowledge Item ที่เกี่ยวข้องกับคำถาม
6. ตรวจ `90_REGISTERS/DECISION_LOG.md` เมื่อพบข้อมูลหลายเวอร์ชัน

## Source Authority Order

เมื่อข้อมูลขัดแย้งกัน ให้ใช้ลำดับอำนาจดังนี้:

1. กฎหมาย ข้อกำหนด หรือเอกสารองค์กรที่ Approved และยังมีผล
2. SOP, WI, Policy, Master Data หรือ Authority Matrix ฉบับ Approved ล่าสุด
3. Decision ที่ Boss ยืนยันอย่างชัดเจน
4. Current Operational Practice ที่ระบุวันที่และผู้ยืนยัน
5. Draft, Workshop Note หรือ Working Document
6. Example
7. AI Inference

AI MUST NOT รวมข้อมูลที่ขัดแย้งกันเองโดยไม่แจ้งผู้ใช้

## Repository Visibility

Repository นี้เป็น Public ตามการตัดสินใจของ Owner เมื่อวันที่ 2026-08-25

MUST NOT จัดเก็บ Password, API Token, Secret Key, Access Credential หรือข้อมูลที่สามารถใช้เข้าสู่ระบบได้ แม้ Owner จะอนุญาตให้เก็บ Personal Context

## Baseline Status

นี่คือ Initial AI-ready KB Baseline ข้อมูลที่ยังไม่ได้ตรวจเทียบกับเอกสาร Approved จะถูกระบุเป็น `active_draft`, `pending_validation` หรือ `unknown`


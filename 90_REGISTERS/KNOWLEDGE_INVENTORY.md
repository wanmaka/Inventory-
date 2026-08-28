---
kb_id: REG-INV-001
title: "ทะเบียนองค์ความรู้ (Knowledge Inventory Register)"
description: "ทะเบียนกลางสำหรับตรวจสอบ KB ID, Domain, Owner, Last Updated, Status และ Sensitivity ของทุก Knowledge Item"
owner: "Wanmaka Promchoto"
last_updated: 2026-08-29
status: active
domain: register
knowledge_type: index
source_authority: boss_confirmed
sensitivity: internal
---

# ทะเบียนองค์ความรู้ (Knowledge Inventory Register)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | ทะเบียนกลางสำหรับตรวจสอบ Metadata และสถานะของทุก Knowledge Item |
| เจ้าของข้อมูล (Owner) | Wanmaka Promchoto |
| อัปเดตล่าสุด (Last Updated) | 29 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## รายการ Knowledge Item

| KB ID | ชื่อ | Owner | Last Updated | Status | Sensitivity |
|---|---|---|---|---|---|
| ROOT-README-001 | คลังองค์ความรู้หลัก | Wanmaka Promchoto | 2026-08-25 | Active | Internal |
| GOV-AI-001 | ธรรมาภิบาลและกฎการทำงานของ AI | Wanmaka Promchoto | 2026-08-25 | Active | Internal |
| GOV-KB-001 | โครงสร้างองค์ความรู้สำหรับ AI | Wanmaka Promchoto | 2026-08-25 | Active | Internal |
| WK-INDEX-001 | สารบัญองค์ความรู้ด้านงาน | Wanmaka Promchoto | 2026-08-25 | Active | Internal |
| WK-OBK-SOC-001 | รูปแบบการดำเนินงานของ SOC | SOC | 2026-08-25 | Pending Validation | Internal |
| WK-OBK-CMD-001 | ธรรมาภิบาลการสั่งการและการตอบสนองเหตุฉุกเฉิน | DCC | 2026-08-25 | Active | Internal |
| WK-OBK-ZONE-001 | ทะเบียน Seat, Zone และ Asset ของ SOC | SOC | 2026-08-25 | Active—Update Required | Internal |
| WK-OBK-MOZ-001 | กฎหลักการบริหาร Mozart Case | SOC | 2026-08-25 | Pending Validation | Internal |
| WK-OBK-SRC-001 | แผนที่แหล่งข้อมูล _SENSES SOC Google Drive | SOC | 2026-08-28 | Active | Internal |
| WK-OBK-SOP-001 | ทะเบียนเอกสาร SOP/WI ของ One Bangkok SOC | SOC | 2026-08-28 | Active | Internal |
| WK-OBK-SWL-001 | คลัง Swimlane ของ One Bangkok SOC | SOC | 2026-08-28 | Active | Internal |
| WK-OBK-IMP-001 | ทะเบียนควบคุมการนำเข้า _SENSES SOC | SOC | 2026-08-29 | Active | Internal |
| WK-BIZ-GF-001 | องค์ความรู้ธุรกิจส่วนตัว | Wanmaka Promchoto | 2026-08-25 | Draft | General Personal |
| BP-INDEX-001 | ประวัติและบริบทส่วนบุคคลของ Boss | Wanmaka Promchoto | 2026-08-25 | Active | General Personal |
| BP-PRO-001 | ตัวตนและระบบการทำงานระดับมืออาชีพ | Wanmaka Promchoto | 2026-08-25 | Active | General Personal |
| BP-CTX-001 | บริบทส่วนบุคคลและกฎการใช้งาน | Wanmaka Promchoto | 2026-08-25 | Active | Sensitive Personal |
| REG-TERM-001 | ทะเบียนคำศัพท์และคำควบคุม | Wanmaka Promchoto | 2026-08-25 | Active | Internal |
| REG-INV-001 | ทะเบียนองค์ความรู้ | Wanmaka Promchoto | 2026-08-29 | Active | Internal |
| REG-DEC-001 | ทะเบียนการตัดสินใจ | Wanmaka Promchoto | 2026-08-29 | Active | Internal |

## สถานะการนำเข้าเพิ่มเติม (Import Status)

**Authorization:** Full import from `_SENSES SOC` approved by Boss under `DEC-20260829-001`.

- [x] Source Map / Shared Drive Structure — imported
- [x] Full SOP and WI Document Register — initial source register imported; content extraction and revision validation continue
- [x] Swimlane Library — PDF source library imported; Visio/version validation continue
- [~] Complete Mozart Event Type and Task Template Master — In Progress
- [~] CCTV Master Knowledge Base and Qognify User Guidelines — Authorized / Import Queue
- [~] Training and Assessment Library — Authorized / Import Queue
- [~] Security Awareness Library — Authorized / Import Queue
- [~] TTX, GDX and AAR Library — Authorized / Import Queue
- [~] Reports, HOTO and Communication Templates — Authorized / Import Queue
- [~] Projects and Enhancement Portfolio — Authorized / Import Queue
- [~] Full Source and Document Cross-reference Register — Authorized / Import Queue
- [~] SOC Documents / Forms / Guidelines / Manuals — Authorized / Import Queue
- [~] Operator Task Library — Authorized / Import Queue
- [~] CCTV Record and Tracking — Authorized; sensitive evidence remains in Drive and Repository stores metadata/sanitized knowledge only
- [~] Activity Picture Library — Authorized; raw images remain in Drive and Repository stores metadata/reference only
- [~] SOC Management One Bangkok — Task, Work Schedule, Report, Project, Procurement, Document Control, Project Sun — Authorized / Import Queue

> หมายเหตุ: `_SENSES SOC` Google Drive เป็น Raw Source/Source of Truth ส่วน GitHub Inventory เป็น Knowledge Structure, Register, Cross-reference และ Sanitized Extract. เอกสาร Draft/Historical/Example ต้องรักษาสถานะเดิมและห้ามใช้เสมือน Approved Operational Rule.

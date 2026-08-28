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
| WK-OBK-SRC-001 | แผนที่แหล่งข้อมูล _SENSES SOC Google Drive | SOC | 2026-08-29 | Active | Internal |
| WK-OBK-SOP-001 | ทะเบียนเอกสาร SOP/WI ของ One Bangkok SOC | SOC | 2026-08-28 | Active | Internal |
| WK-OBK-SWL-001 | คลัง Swimlane ของ One Bangkok SOC | SOC | 2026-08-28 | Active | Internal |
| WK-OBK-IMP-001 | ทะเบียนควบคุมการนำเข้า _SENSES SOC | SOC | 2026-08-29 | Active | Internal |
| WK-OBK-SRCINV-001 | ทะเบียน Source Inventory _SENSES SOC | SOC | 2026-08-29 | Active | Internal |
| WK-OBK-TASK-001 | กรอบการบริหาร Task ของ SOC | SOC | 2026-08-29 | Active | Internal |
| WK-OBK-TRN-001 | คลังการฝึกอบรมและการประเมิน SOC | SOC | 2026-08-29 | Active | Internal |
| WK-OBK-DOC-001 | ทะเบียนเอกสารปฏิบัติงาน SOC | SOC | 2026-08-29 | Active | Internal |
| WK-OBK-PE-001 | คลังการประเมินผลการปฏิบัติงาน SOC | SOC Management | 2026-08-29 | Active | Internal |
| WK-OBK-MOZ-SRC-001 | ทะเบียน Source ของ Mozart Event Type และ Task Template | SOC | 2026-08-29 | Active | Internal |
| WK-BIZ-GF-001 | องค์ความรู้ธุรกิจส่วนตัว | Wanmaka Promchoto | 2026-08-25 | Draft | General Personal |
| BP-INDEX-001 | ประวัติและบริบทส่วนบุคคลของ Boss | Wanmaka Promchoto | 2026-08-25 | Active | General Personal |
| BP-PRO-001 | ตัวตนและระบบการทำงานระดับมืออาชีพ | Wanmaka Promchoto | 2026-08-25 | Active | General Personal |
| BP-CTX-001 | บริบทส่วนบุคคลและกฎการใช้งาน | Wanmaka Promchoto | 2026-08-25 | Active | Sensitive Personal |
| REG-TERM-001 | ทะเบียนคำศัพท์และคำควบคุม | Wanmaka Promchoto | 2026-08-25 | Active | Internal |
| REG-INV-001 | ทะเบียนองค์ความรู้ | Wanmaka Promchoto | 2026-08-29 | Active | Internal |
| REG-DEC-001 | ทะเบียนการตัดสินใจ | Wanmaka Promchoto | 2026-08-29 | Active | Internal |
| REG-SRC-001 | ทะเบียนแหล่งข้อมูล _SENSES SOC | SOC | 2026-08-29 | Active | Internal |

## สถานะการนำเข้า (Import Status)

**Authorization:** Full import from `_SENSES SOC` approved by Boss under `DEC-20260829-001`.

- [x] Canonical `_SENSES SOC` Shared Drive identified — Drive ID `0AJpAwl9n5sLbUk9PVA`; root = `SOC Management` + `SOC Team`
- [x] Source Map / Shared Drive Structure — `WK-OBK-SRC-001`
- [x] Source Inventory Register — `WK-OBK-SRCINV-001`; canonical workstream/folder IDs indexed
- [x] Import Control / Safety Boundary — `WK-OBK-IMP-001`
- [x] Full Source & Document Cross-reference Register — `REG-SRC-001` established; recursive expansion remains a living process
- [x] SOP/WI Document Register — `WK-OBK-SOP-001`; content extraction/revision validation continues
- [x] Swimlane Library — `WK-OBK-SWL-001`; current Visio/PDF revision validation continues
- [x] Task Management Framework — `WK-OBK-TASK-001` extracted from current native `Task Management ล่าสุด`
- [x] Training & Assessment Library — `WK-OBK-TRN-001` source structure/key files imported; deeper content extraction continues
- [x] SOC Operational Documents Register — `WK-OBK-DOC-001`
- [x] SOC Performance Evaluation Library — `WK-OBK-PE-001`; individual HR/performance records remain restricted references
- [x] Mozart Event/Task Source Register — `WK-OBK-MOZ-SRC-001`
- [~] Complete Mozart Event Type and Task Template Canonical Master — deep row-level extraction/validation in progress
- [~] CCTV Master Knowledge Base and Qognify/User Guidelines — source hierarchy indexed; deep extraction in progress
- [~] Guard Tour Library — current 2025/2026 and monthly 2026 sources located; canonical process extraction pending
- [~] Virtual Patrol Library — 2025/2026 record sources located; canonical process extraction pending
- [~] Operator Task Library — CI Traffic, Zone 1, Zone 2, Compound, Summary and CCTV Offline Checklist located
- [~] Security Awareness Library — authorized; canonical current-drive source discovery/validation continues
- [~] TTX, GDX and AAR Library — authorized; current-drive source discovery/validation continues
- [~] Reports, HOTO and Communication Templates — authorized; source discovery/validation continues
- [~] Projects and Enhancement Portfolio — Management Project domains indexed; deep extraction continues
- [~] ISO / Audit Library — source domain identified under Management Project; deep extraction pending
- [~] CCTV Record and Tracking — Tracking/Request/Form/Record hierarchy indexed; sensitive evidence stays in Drive
- [~] Event Library — 2025/2026 source folders located; content extraction pending
- [~] Work Schedule / Workforce Reference — authorized as restricted reference; staffing-model knowledge only in Public Repository
- [~] Blacklist / Whitelist / Watchlist — authorized as restricted reference; identity-level raw data stays in Drive
- [~] Activity Picture Library — authorized; raw images remain in Drive and KB stores metadata/reference only

## Data Handling Principle

`_SENSES SOC` Google Drive เป็น Raw Source/Source of Truth ส่วน GitHub Inventory เป็น Knowledge Structure, Register, Cross-reference และ Sanitized Extract.

ข้อมูล Draft/Historical/Example ต้องรักษาสถานะเดิมและห้ามใช้เสมือน Approved Operational Rule. ข้อมูล Restricted เช่น Credential, PII, Blacklist identity, ทะเบียนรถ, CCTV Evidence, Sensitive Layout และ Individual HR/Performance Record จะไม่ถูกทำสำเนา Raw Content ลง Public Repository แต่ยังถือว่าอยู่ในขอบเขต KB ผ่าน Metadata/Reference และการสกัดองค์ความรู้ที่ปลอดภัย.

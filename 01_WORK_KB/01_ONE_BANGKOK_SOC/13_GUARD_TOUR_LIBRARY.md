---
kb_id: WK-OBK-GT-001
title: "คลัง Guard Tour ของ SOC (SOC Guard Tour Library)"
description: "ทะเบียน Source และองค์ความรู้แบบ Sanitized สำหรับ Guard Tour master/records รายปีและรายเดือนจาก _SENSES SOC เพื่อรองรับ Workflow, Monitoring, Compliance และ Reporting"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: current_operational_practice
sensitivity: internal
---

# คลัง Guard Tour ของ SOC (SOC Guard Tour Library)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | ทะเบียน Source และองค์ความรู้แบบ Sanitized สำหรับ Guard Tour ของ SOC |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 29 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## Canonical Source

`_SENSES SOC` → `SOC Team` → `01. SOC Documents` → `04. Guard Tour`

- Root: `1qTcJQjx5XsJYNTLWEy0m0QNLyMJ0ZloU`
- `01. Guard Tour`: `18aKNTkrInfLiSYVPUyaQrPbl0n-Uz_Ea`
- `02. บันทึกข้อมูล Guard Tour`: `1d3frQ3cqyze5Z0GHm3sjEMi74GUDsd_s`

## Guard Patrol Master / Annual Records

- `Guard Patrol Record 2025.xlsx` — `1lFA2CMFAefWIvuwEn6hGpPaUYxpUCDIK`
- `Guard Patrol Record 2026.xlsx` — `1RIbLLnxI_fNDi102cI2hkgm2AkDoJI9Q`

`Guard Patrol Record 2026.xlsx` ถูกตรวจอ่านจาก Canonical Shared Drive แล้ว และใช้เป็น Current Operational Record Source สำหรับโครงสร้างการติดตาม Guard Tour โดยไม่คัดลอก Raw Patrol Detail ลง Repository

## โครงสร้างการติดตามที่ยืนยันจาก Source (Verified Record Structure)

จาก `Guard Patrol Record 2026.xlsx` ยืนยันได้ว่า Guard Tour ถูกติดตามในรูปแบบ Route/Check ต่อวัน และสรุปผลอย่างน้อยด้วยค่าต่อไปนี้:

- `Plan` — จำนวนรอบ/งานที่วางแผนไว้ตาม Route หรือ Check
- `Actual` — จำนวนรอบ/งานที่ดำเนินการจริงตามข้อมูลบันทึก
- `Percentage (%)` — อัตราผลสำเร็จเทียบ Plan กับ Actual
- มีทั้งมุมมองราย Route/Check และ Summary ตามกลุ่มงาน

กฎการใช้ข้อมูล:

- ค่า Plan/Actual/Percentage ใช้เป็น **Operational Record / Performance Evidence** ไม่ใช่ Policy หรือ Authority Rule
- ผลรายวัน/รายบุคคล/รายละเอียดตำแหน่งแบบ Raw ให้คงอยู่ใน Drive
- Repository ใช้เฉพาะโครงสร้าง Metric, ประเภทงาน และ Metadata ที่ Sanitized แล้ว
- Historical month/year ใช้เพื่อ Trend/Audit Evidence และห้าม Override Current Guideline หรือ Approved Procedure

## ประเภท Route / Check ที่พบใน Current Record

เพื่อหลีกเลี่ยงการเปิดเผยรายละเอียดพื้นที่เชิงลึก Repository เก็บเป็นหมวด Sanitized ดังนี้:

1. Component / Building Guard Tour
2. Security Readiness Check ของทีมภาคสนาม/FCC
3. Common Infrastructure / Perimeter / Public-area Guard Tour
4. Parking / Basement Guard Tour
5. EOT Safety Asset Check
6. SOC Pre-Work Checklist

ประเภทเหล่านี้ยืนยันว่า Guard Tour ใน One Bangkok ไม่ได้จำกัดเฉพาะการเดินตรวจพื้นที่ แต่ครอบคลุมทั้ง Patrol Route, Readiness Check, Safety Asset Check และ SOC Operational Checklist ตาม Source ที่ใช้งานจริง

## Monthly Guard Tour 2026 Sources

- January — `1-MLhuawxOM1Z8Xmkqes62yXjqevlacCv`
- March — `1KXH_PeLktEzni-XugZzm20NHaM1aKjF3`
- April — `1bb1qNWr8-g13R0TEF416Z_1IF-geEaiR`
- May — `1sXCBUhQ2KvYPxiuJmjHj1JnDb92irZ9f`
- June — `1yD2p5hRATq9piHS1deybNJN2QUEDVfAB`
- July — `1_RORvH2A3KpcQ23cH95oKNdOuIuZ6GTt`
- August — `1xAoDXt-YB7yo-pQs2dAqqAaiypcNdZWX`
- September — `1HiLtdZruFURgSDXFd-8JLWnE87LvEHz8`
- October — `1SecNjdUhawAzLzrhwlQeQY9ESUV9LiK2`
- November — `10a-TOOUKEK1NsspABHP2di1NafB5wUf3`
- December — `1rordvb30U3Dtgoh-nFDhK99AFWpDEF7Z`

February 2026 was not present in the direct folder listing at the scan time; state = `UNKNOWN` until located or confirmed absent.

## Target Knowledge Extraction

Source-verified/imported:

- Route / check structure
- Plan / Actual / Percentage reporting model
- Sanitized work categories
- Annual/monthly source hierarchy

Pending deeper controlled-source validation:

- Schedule and frequency authority logic
- Assigned / In Progress / Completed / Skip Task / Cancelled / Overdue semantics
- Reason/remark requirements
- Follow-up and verification responsibilities
- Exception handling and rework logic
- Account/user naming guideline authority

Until a controlled guideline/system source confirms these items, state = `PENDING_VALIDATION`; do not infer them from the attendance/performance record alone.

## Data Handling

Raw monthly attendance/patrol detail may include person/time/location records. Public GitHub stores normalized operational rules and aggregate/reference metadata only; raw detailed logs remain in Drive.

## Version Rule

Use current-year/current-month source for operational status checking. Historical month files support trend and audit evidence but do not override a current policy/guideline.

## Source Cross-reference

- `_SENSES SOC` Source Register: `REG-SRC-001`
- Source Inventory: `WK-OBK-SRCINV-001`
- Import Control: `WK-OBK-IMP-001`

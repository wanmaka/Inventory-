---
kb_id: WK-OBK-ZONE-001
title: "ทะเบียน Seat, Zone และ Asset ของ SOC (SOC Seat, Zone and Asset Master)"
description: "รวบรวมขอบเขต Seat, Zone, Asset, Operational Status และหลักการประเมินความเสี่ยงตามพื้นที่ของ SOC"
owner: "SOC"
last_updated: 2026-08-25
status: active_update_required
domain: one_bangkok_soc
knowledge_type: zone_profile
source_authority: boss_confirmed
sensitivity: internal
related_kb_ids:
  - REG-TERM-001
---

# ทะเบียน Seat, Zone และ Asset ของ SOC (SOC Seat, Zone and Asset Master)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | ขอบเขต Seat, Zone, Asset, Operational Status และความเสี่ยงเฉพาะพื้นที่ของ SOC |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง—ต้องอัปเดต (Active—Update Required) |

## ขอบเขตที่มีผล (Effective Scope)

Zone Mapping นี้เป็นโครงล่าสุด ณ เดือนสิงหาคม 2026

Seat Assignment และ Operational Status สามารถเปลี่ยนแปลงได้ ข้อมูลที่อ่อนไหวต่อเวลาต้องระบุวันที่มีผล

## Common Infrastructure: CI

CI เป็นตัวย่อทางการของ Common Infrastructure หมายถึงโครงสร้างพื้นฐานและพื้นที่ส่วนกลางที่สนับสนุนการดำเนินงานระดับโครงการ

ในบริบทการจัด Seat หรือ Function ของ SOC ให้แยก `CI Security` และ `CI Traffic` ตามภารกิจด้านล่าง

## CI Security

CI Security เฝ้าระวังภาพรวมด้าน Physical Security รวมถึงเหตุสำคัญและเหตุที่กระทบหลาย Zone

ประเด็นหลัก:

- การเฝ้าระวัง Security แบบ Cross-zone
- บุคคลหรือพฤติกรรมต้องสงสัย
- ทรัพย์สินสูญหายและการสนับสนุนการตรวจสอบ
- ข้อพิพาทหรือการทะเลาะวิวาท
- ผลกระทบต่อภาพลักษณ์
- การประสาน DCC และหน่วยงานส่วนกลาง
- การสนับสนุน Zone Operator เมื่อเกิดเหตุใหญ่

## CI Traffic

CI Traffic เฝ้าระวังการเคลื่อนตัวของรถ ทางเข้าออก Drop-off และสภาพพื้นที่จอดรถ

ประเด็นหลัก:

- Traffic Congestion และ Trigger Point
- จุดสะสมรถและคอขวด
- อุบัติเหตุ รถเสีย และสิ่งกีดขวาง
- การประสานเส้นทางสำรอง
- การใช้ CCTV, LPR, Car Park System และ GPS
- การประสานเจ้าหน้าที่จราจรภาคสนาม

ช่องทาง GPS ที่ยืนยันแล้ว:

- One Bangkok Mobile Application
- เว็บไซต์หรือระบบ GPS Tracking ของบริษัทมนตรี

## Zone 1

Asset:

- Tower 2
- Tower 3
- Fraser Suites
- พื้นที่ส่วนกลางและพื้นที่เชื่อมต่อ

ลักษณะงานหลัก:

- Office Security
- Hotel Security และ Guest Privacy
- Construction, Commissioning และ Tenant Fit-out
- Contractor และ Material Movement
- Access Control
- Mixed-use Incident Coordination

## Zone 2

Asset และสถานะที่ยืนยัน ณ เดือนสิงหาคม 2026:

| Asset | Operational Status |
|---|---|
| Tower 4 | Operating |
| The Storeys | Operating |
| Andaz Hotel | Operating |
| Pathom House Hotel | Operating |

ลักษณะงานหลัก:

- Office, Retail และ Hotel Security
- มาตรฐานบริการระดับสูง
- Access Control
- การประสานลูกค้า แขก ผู้เช่า และทีมอาคาร
- พื้นที่อ่อนไหวด้าน Privacy
- Lost Property และ Suspicious Behavior
- การแยก Security, Customer Service และ Maintenance

กฎ Privacy:

CCTV หรือ Video Analytics ใกล้ห้องน้ำหรือห้องเปลี่ยนเสื้อผ้าต้องตรวจเฉพาะทางเข้า ทางเดิน และพื้นที่ส่วนกลาง ห้ามครอบคลุมพื้นที่ส่วนบุคคล

## Zone 3

Asset:

- The Ritz-Carlton
- POST 1928
- One89 Wireless
- Eighteen Seven
- Tower 5
- Shared Area และ Shared Infrastructure

ลักษณะงานหลัก:

- Luxury Hotel, Retail, Residential และ Office Security
- การกำหนด Owner ของ Shared Area
- การตรวจสอบข้าม Asset และการติดตาม CCTV
- Privacy และผลกระทบต่อภาพลักษณ์
- Contractor และ Fit-out Management
- การรวบรวมหลักฐานจากหลายระบบ

## Zone 4

Asset:

- One Bangkok Forum
- One Power
- P5 Parking ซึ่งเป็น Future Asset
- พื้นที่ Prelude เดิมและแผนพัฒนา C5 Residence

ลักษณะงานหลัก:

- Event and Crowd Monitoring
- Critical Infrastructure Protection
- Parking and Traffic Operations
- Contractor, Demolition และ Construction Control
- Future Asset Integration

## One Power

One Power ได้รับการยืนยันว่าเป็นพื้นที่ Maximum Security

หลักการทำงาน:

`Verify Early → Escalate Early → Maintain Full Traceability`

SOC และ AI ควรประเมิน:

- สาเหตุของ Alarm
- ตัวตนและสิทธิ์ของบุคคลในพื้นที่
- งานซ่อมบำรุงหรือกิจกรรมผู้รับเหมาที่ได้รับอนุญาต
- ผลกระทบต่อ Utility หรือหลาย Asset
- ความจำเป็นในการส่งเจ้าหน้าที่ตรวจสอบ
- ความสัมพันธ์ระหว่าง Security Case และ Maintenance Case
- ความจำเป็นในการแจ้ง DCC หรือผู้บริหาร

## กฎพื้นที่ใช้ร่วมกัน (Shared Area Rule)

SOC ห้ามสรุปเจ้าของเหตุจากตำแหน่งกล้องเพียงอย่างเดียว

SOC ต้องตรวจสอบ:

- สถานที่เกิดเหตุจริง
- ขอบเขตพื้นที่
- Asset ที่ได้รับผลกระทบ
- Operational Owner
- Supporting Owner
- ระบบ CCTV และช่องทางสื่อสารที่ต้องใช้

## ข้อจำกัดของ AI (AI Constraints)

- ต้องแยก Asset Profile ที่คงที่ออกจาก Operational Status ที่อ่อนไหวต่อเวลา
- ห้ามสรุปสถานะก่อสร้างหรือ Operating ปัจจุบันโดยไม่มีแหล่งข้อมูลระบุวันที่
- ต้องคำนึงถึงมาตรฐาน Privacy และ Service ที่แตกต่างกันของ Hotel, Residential, Retail และ Office

## เหตุผลที่ต้องอัปเดต (Update Requirement)

ต้องตรวจสอบ Operational Status และ Operational Owner ของ Asset นอก Zone 2 รวมถึงการเปลี่ยนแปลง Future Asset ก่อนเปลี่ยนสถานะเป็น `active`

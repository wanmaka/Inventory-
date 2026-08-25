---
kb_id: WK-OBK-SOC-001
title: "รูปแบบการดำเนินงานของ SOC (SOC Operating Model)"
description: "อธิบายคำนิยาม ภารกิจ ช่องทางรับข้อมูล วงจรการทำงาน และบทบาทพื้นฐานของ SOC Operator และ SOC Supervisor"
owner: "SOC"
last_updated: 2026-08-25
status: pending_validation
domain: one_bangkok_soc
knowledge_type: definition
source_authority: boss_confirmed
sensitivity: internal
applies_to:
  - SOC_Operator
  - SOC_Supervisor
related_kb_ids:
  - WK-OBK-CMD-001
  - WK-OBK-MOZ-001
  - REG-TERM-001
---

# รูปแบบการดำเนินงานของ SOC (SOC Operating Model)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | คำนิยาม ภารกิจ ช่องทางรับข้อมูล วงจรการทำงาน และบทบาทพื้นฐานของ SOC |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | รอตรวจสอบ (Pending Validation) |

## คำนิยามหลัก (Canonical Definition)

ศูนย์ปฏิบัติการรักษาความปลอดภัย (Security Operation Centre: SOC) เป็นศูนย์ควบคุมและประสานงานด้าน Physical Security

SOC มีหน้าที่เฝ้าระวัง ตรวจสอบ วิเคราะห์ บันทึก และประสานการตอบสนองต่อเหตุการณ์ที่อาจส่งผลกระทบต่อชีวิต ทรัพย์สิน การดำเนินงาน การให้บริการ และภาพลักษณ์ของโครงการ

ห้ามตีความ SOC ใน KB นี้ว่าเป็น Cybersecurity SOC

DCC ในบริบท One Bangkok หมายถึง District Command Centre

## ช่องทางข้อมูลของ SOC (Operating Channels)

SOC รับและเชื่อมโยงข้อมูลจาก:

- CCTV และ Video Management System: VMS
- Alarm จากระบบอาคารและระบบรักษาความปลอดภัย
- Access Control
- Video Analytics
- License Plate Recognition: LPR
- ระบบจราจรและลานจอดรถ
- โทรศัพท์และวิทยุสื่อสาร
- Mozart
- Ops App
- เจ้าหน้าที่รักษาความปลอดภัยภาคสนาม
- ทีมอาคาร
- DCC
- ผู้รับเหมาและหน่วยงานที่เกี่ยวข้อง

## วงจรการทำงานหลัก (Operating Lifecycle)

`รับข้อมูล → ตรวจสอบ → ประเมิน → เปิดหรืออัปเดต Case → ประสานงาน → ติดตาม → รวบรวมหลักฐาน → บันทึก Findings / Resolution → SOC Supervisor ตรวจสอบ → SOC Operator Resolve Case → SOC Supervisor Close Case → ถอดบทเรียน`

เหตุเร่งด่วนสามารถใช้ลำดับการเปิด Case ที่แตกต่างออกไป โปรดดู `WK-OBK-MOZ-001`

## คำถามสถานการณ์ขั้นต่ำ (Minimum Situational Questions)

SOC ควรตอบได้ว่า:

1. เกิดอะไรขึ้น
2. เกิดที่ไหน
3. เกิดเมื่อใด
4. ใครได้รับผลกระทบ
5. ใครกำลังดำเนินการ
6. สถานการณ์ปัจจุบันเป็นอย่างไร
7. ยังมีความเสี่ยงอะไร
8. ต้องยกระดับหรือไม่
9. เหตุการณ์ยุติอย่างไร
10. ต้องมี Preventive Action หรือ Corrective Action หรือไม่

## ผู้ปฏิบัติงาน SOC (SOC Operator)

SOC Operator เป็นผู้ปฏิบัติงานแนวหน้าที่รับผิดชอบ Seat หรือพื้นที่ที่ได้รับมอบหมาย

หน้าที่หลัก:

- เฝ้าระวังระบบและช่องทางสื่อสารที่ได้รับมอบหมาย
- ตรวจสอบเหตุด้วย Live View, Playback, ข้อมูลระบบ และการยืนยันจากหน้างาน
- เลือก Event Type ให้ถูกต้องและบันทึก Timeline ตามลำดับเวลา
- ประสานหน่วยงานตอบสนองที่เกี่ยวข้อง
- ติดตามจนทราบผู้รับงาน เวลาเข้าพื้นที่ Findings การดำเนินการ และผลยุติ
- รวบรวมและแนบหลักฐานที่เหมาะสม
- จัดทำ Findings / Resolution และดำเนินการ Resolve Case หลัง SOC Supervisor ตรวจสอบ
- ยกระดับเหตุสำคัญ เหตุผลกระทบสูง เหตุที่ยังไม่ยืนยัน หรือเหตุเกินอำนาจ
- ส่งมอบ Active Case ปัญหาระบบ และงานคงค้างให้ผลัดถัดไปครบถ้วน

## หัวหน้าผลัด SOC (SOC Supervisor)

SOC Supervisor ควบคุมภาพรวมของผลัดทั้งด้านบุคลากร เหตุการณ์ ระบบ ข้อมูล และความเสี่ยง

หน้าที่หลัก:

- จัด Seat Assignment และตรวจความพร้อมก่อนเริ่มผลัด
- ตรวจ Event Type, Timeline, Evidence และคุณภาพการประสานงาน
- ประเมินความรุนแรง ความเร่งด่วน ผลกระทบ และความจำเป็นในการยกระดับ
- จัดสรรกำลังและจัดลำดับความสำคัญเมื่อเกิดหลายเหตุพร้อมกัน
- ควบคุมความถูกต้องและความสอดคล้องของข้อมูลที่ออกจาก SOC
- ติดตาม Active Case งานเกินกำหนด และความเสี่ยงด้าน SLA
- ตรวจสอบความครบถ้วนก่อน Operator ดำเนินการ Resolve Case
- ดำเนินการ Close Case สำหรับ Security Case ทุกกรณีที่อยู่ภายใต้ SOC Workflow
- สอนงานและพัฒนา Operator
- ควบคุมวินัยและมาตรฐานการปฏิบัติงาน
- ทำหน้าที่ด้าน Command หรือ Coordination ตามอำนาจที่กำหนดใน SOP ที่เกี่ยวข้อง

## ความแตกต่างของบทบาท (Role Distinction)

- Operator รับผิดชอบความถูกต้องและความต่อเนื่องของเหตุหรือพื้นที่ที่ได้รับมอบหมาย
- Supervisor รับผิดชอบคุณภาพภาพรวมของผลัด การจัดลำดับ การสนับสนุนการตัดสินใจ การจัดทรัพยากร และการยกระดับ

## บทบาท Security ภาคสนาม (Field Security Roles)

- Security Management Team: SMT บริหาร ควบคุม และประสานงานด้าน Security ครอบคลุม In-Building, Traffic และ Common Infrastructure
- Security Officer ครอบคลุมเจ้าหน้าที่รักษาความปลอดภัยภาคสนามของ PCS และ G4S
- Security Supervisor หมายถึงหัวหน้าชุดรักษาความปลอดภัย และต้องแยกจาก SOC Supervisor
- ห้ามใช้คำว่า `Security` หรือ `Supervisor` เป็นผู้รับผิดชอบโดยไม่ระบุตำแหน่ง เมื่อความหมายมีผลต่อการสั่งการหรือ Workflow

## เวลาปฏิบัติงาน (Operating Hours)

- SOC ปฏิบัติงาน 24 ชั่วโมง
- Contact Centre ปฏิบัติงานเวลา 08:00–22:30
- หลัง Contact Centre ปิด สายที่โทรเข้าหมายเลข Contact Centre จะถูกส่งต่อมายัง SOC

## ข้อจำกัดของ AI (AI Constraints)

- ต้องแยกข้อเท็จจริงออกจากข้อสันนิษฐาน
- ห้ามตัดสินความผิดจาก CCTV หรือ Analytics เพียงอย่างเดียว
- ต้องระบุ Operational Owner ก่อนสรุปความรับผิดชอบ
- ต้องพิจารณาว่าเป็น Security Case, Maintenance Case หรือจำเป็นต้องเชื่อมโยงทั้งสองประเภท
- ต้องคำนึงถึง Privacy, Guest Experience, Resident Experience และมาตรฐานเฉพาะของแต่ละ Asset

## สิ่งที่ต้องตรวจสอบต่อ (Pending Validation)

เนื้อหานี้ต้องตรวจเทียบกับ Core SOC Master Framework, Authority Matrix และ SOP/WI ฉบับ Approved ก่อนเปลี่ยนสถานะเป็น `active`

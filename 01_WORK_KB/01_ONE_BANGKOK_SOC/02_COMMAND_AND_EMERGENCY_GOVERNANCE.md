---
kb_id: WK-OBK-CMD-001
title: "ธรรมาภิบาลการสั่งการและการตอบสนองเหตุฉุกเฉิน (Emergency Command and Immediate Response Governance)"
description: "กำหนดอำนาจของ DCC, Field IC และ SOC รวมถึง Immediate Life Safety Response ก่อนการประกาศใช้แผนอย่างเป็นทางการ"
owner: "DCC"
last_updated: 2026-08-25
status: active
domain: one_bangkok_soc
knowledge_type: authority_rule
source_authority: boss_confirmed
sensitivity: internal
applies_to:
  - DCC
  - SOC
  - Field_IC
  - EOT
  - Security
related_kb_ids:
  - WK-OBK-SOC-001
  - WK-OBK-MOZ-001
---

# ธรรมาภิบาลการสั่งการและการตอบสนองเหตุฉุกเฉิน (Emergency Command and Immediate Response Governance)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | อำนาจของ DCC, Field IC และ SOC รวมถึงการตอบสนองเพื่อความปลอดภัยก่อนประกาศใช้แผน |
| เจ้าของข้อมูล (Owner) | DCC |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## รูปแบบอำนาจ (Authority Model)

- DCC ต้องเป็นผู้ประกาศใช้ ยกระดับ ลดระดับ Stand Down และยุติแผนฉุกเฉิน
- SOP ของแต่ละแผนต้องกำหนดตำแหน่ง Field IC ไว้ล่วงหน้า
- Field IC ต้องควบคุมและสั่งการการตอบสนอง ณ จุดเกิดเหตุหรือ Incident Command Post: ICP
- SOC ต้องสื่อสารการประกาศใช้แผนและคำสั่งที่เกี่ยวข้องไปยังหน่วยงานตาม Notification Matrix ของแต่ละแผน
- SOC และ DCC ทำหน้าที่เป็น Rear Command

## การสั่งการส่วนหน้าและส่วนหลัง (Field and Rear Command)

### ผู้บัญชาการเหตุการณ์ภาคสนาม (Field IC)

- สั่งการเชิง Tactical ณ จุดเกิดเหตุหรือ ICP
- ประสานงานกับ SOC และ DCC
- ควบคุมทรัพยากรภาคสนามตาม SOP ที่เกี่ยวข้อง

### District Command Center: DCC

- มีอำนาจทางการในการประกาศใช้และเปลี่ยนสถานะแผน
- ให้ Strategic Direction สนับสนุนการยกระดับต่อผู้บริหาร และสนับสนุนการตัดสินใจ

### Security Operation Centre: SOC

- สนับสนุนข้อมูลจาก CCTV และระบบที่เกี่ยวข้อง
- รักษาการสื่อสารและการประสานงาน
- เปิดและอัปเดต Mozart Case
- บันทึกเวลาประกาศ คำสั่ง การเปลี่ยนสถานะ และผลการตอบสนอง
- สื่อสารข้อมูลไปยังหน่วยงานที่เกี่ยวข้อง

## ความพร้อมของ IC (IC Availability)

ภายใต้การจัดกำลังปัจจุบัน ตำแหน่ง IC ที่กำหนดในแต่ละ SOP มีผู้ปฏิบัติงานครบทุกวันและสามารถติดต่อได้

## การตอบสนองเพื่อความปลอดภัยทันที (Immediate Life Safety Response)

หาก:

- `life_safety_threat = true`
- และ `formal_plan_activation = pending`

SOC สามารถ:

1. แจ้งและ Dispatch EOT/Security
2. สั่งกั้นหรือควบคุมพื้นที่เบื้องต้น
3. แนะนำให้บุคคลรักษาระยะห่างหรือหลีกเลี่ยงพื้นที่
4. ประสานการปฐมพยาบาล
5. ควบคุม Access เบื้องต้น
6. เปิด Mozart Case และรวบรวมหลักฐาน

## ข้อแตกต่างบังคับ (Mandatory Distinction)

Immediate Life Safety Response ไม่ใช่การประกาศใช้แผนอย่างเป็นทางการ

AI ห้ามระบุว่า SOC ประกาศใช้แผนฉุกเฉิน เว้นแต่มีการยืนยันคำประกาศจาก DCC

## ข้อมูลขั้นต่ำในการประกาศแผน (Minimum Activation Message)

SOC ควรสื่อสาร:

- ชื่อแผนและระดับการตอบสนอง
- เวลาและพื้นที่เกิดเหตุ
- ตำแหน่งหรือชื่อของ Field IC
- ตำแหน่ง ICP เมื่อจัดตั้งแล้ว
- หน่วยงานที่ต้องตอบสนอง
- ช่องทางสื่อสารหลัก
- คำสั่งหรือการดำเนินการเบื้องต้น

## การลดระดับและยุติแผน (Closure)

- DCC ต้องเป็นผู้ประกาศ De-escalation, Stand Down หรือยุติแผน
- SOC ต้องบันทึกเวลา ผู้มีอำนาจประกาศ และสถานะผลลัพธ์ใน Mozart หรือ Incident Record ที่เกี่ยวข้อง


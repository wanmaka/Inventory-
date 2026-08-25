---
kb_id: REG-TERM-001
title: "ทะเบียนคำศัพท์และคำควบคุม (Terminology and Controlled Vocabulary Register)"
description: "กำหนดคำศัพท์มาตรฐาน ตัวย่อ คำนิยาม ขอบเขตการใช้ คำที่ห้ามใช้ และสถานะการตรวจสอบ เพื่อให้มนุษย์และ AI ตีความองค์ความรู้ตรงกัน"
owner: "Wanmaka Promchoto"
last_updated: 2026-08-25
status: active
domain: register
knowledge_type: definition
source_authority: boss_confirmed
sensitivity: internal
related_kb_ids:
  - GOV-KB-001
  - GOV-AI-001
  - WK-OBK-SOC-001
  - WK-OBK-CMD-001
  - WK-OBK-ZONE-001
  - WK-OBK-MOZ-001
---

# ทะเบียนคำศัพท์และคำควบคุม (Terminology and Controlled Vocabulary Register)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | คำศัพท์มาตรฐานและขอบเขตการใช้คำสำหรับ KB ทั้งหมด |
| เจ้าของข้อมูล (Owner) | Wanmaka Promchoto |
| อัปเดตล่าสุด (Last Updated) | 25 สิงหาคม 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## วัตถุประสงค์ (Purpose)

ทะเบียนนี้เป็นแหล่งอ้างอิงคำศัพท์กลางสำหรับ Knowledge Base โดยมีวัตถุประสงค์เพื่อ:

1. ให้ทุก KB ใช้คำศัพท์และตัวย่อในความหมายเดียวกัน
2. ป้องกันการใช้คำที่ทำให้บทบาท อำนาจ หรือ Workflow คลาดเคลื่อน
3. แยกคำทางการ คำเรียกทั่วไป Alias และคำที่ห้ามใช้แทนกัน
4. ระบุคำที่ยังต้องตรวจสอบกับ SOP, Master Data หรือผู้มีอำนาจ
5. ช่วยให้ AI วิเคราะห์และสร้างคำตอบโดยไม่เปลี่ยนความหมายของข้อมูลต้นทาง

ทะเบียนนี้ไม่ใช้แทน Approved Policy, SOP, WI, Authority Matrix, Notification Matrix หรือ Master Data

## สถานะการใช้คำ (Term Usage State)

| ค่า | ความหมาย |
|---|---|
| `CANONICAL` | คำมาตรฐานที่ต้องใช้เป็นค่าเริ่มต้น |
| `CONTEXT_ONLY` | ใช้ได้เฉพาะบริบทที่กำหนด |
| `DO_NOT_USE` | ห้ามใช้ในบริบทที่ระบุ เพราะอาจทำให้ความหมายหรืออำนาจคลาดเคลื่อน |
| `PENDING_VALIDATION` | คำหรือคำนิยามยังต้องได้รับการยืนยันก่อนใช้เป็นข้อเท็จจริง |

`Term Usage State` ไม่ใช่ `KB Status` และห้ามใช้แทนกัน

## กฎการใช้คำ (Terminology Rules)

- เนื้อหาหลักใช้ภาษาไทย โดยคงคำอังกฤษสำหรับชื่อทางการ ชื่อระบบ ชื่อตำแหน่ง และ Controlled Value
- เมื่อกล่าวถึงคำสำคัญครั้งแรก ให้ใช้ชื่อเต็มตามด้วยตัวย่อ
- AI ต้องใช้คำ `CANONICAL` ในคำตอบและเอกสารใหม่
- Alias ใช้เพื่อค้นหาเอกสารเดิมหรืออธิบายความสัมพันธ์เท่านั้น
- คำที่เป็น `PENDING_VALIDATION` ห้ามใช้เสมือนเป็นข้อเท็จจริงที่ยืนยันแล้ว
- หากคำในทะเบียนขัดกับ Approved SOP หรือ Master Data ฉบับใหม่กว่า ต้องแจ้ง Conflict และเสนอให้ Knowledge Owner ทบทวนทะเบียน

## หน่วยงานและบทบาท (Organizations and Roles)

| Term ID | คำมาตรฐาน | คำนิยามและกฎการใช้ | Owner | Term Usage |
|---|---|---|---|---|
| TERM-ORG-001 | **Security Operation Centre: SOC** | ศูนย์ควบคุมและประสานงานด้าน Physical Security ของ One Bangkok ทำหน้าที่เฝ้าระวัง ตรวจสอบ ประเมิน บันทึก ประสานงาน ติดตาม และสนับสนุนการตอบสนองต่อเหตุการณ์ | SOC | `CANONICAL` |
| TERM-ORG-002 | **Physical Security** | การรักษาความปลอดภัยที่เกี่ยวข้องกับบุคคล ทรัพย์สิน อาคาร พื้นที่ ระบบกายภาพ และการปฏิบัติงานหน้างาน ไม่รวม Cybersecurity เว้นแต่เหตุทาง Cyber ส่งผลต่อ Physical Security | SOC | `CANONICAL` |
| TERM-ORG-003 | **Cybersecurity SOC** | ใช้เพื่อแยกความหมายจาก One Bangkok SOC เท่านั้น ห้ามตีความ One Bangkok SOC ใน KB นี้ว่าเป็น Cybersecurity SOC | — | `CONTEXT_ONLY` |
| TERM-ORG-004 | **District Command Centre: DCC** | หน่วย Command ส่วนหลังของ One Bangkok มีอำนาจประกาศใช้ ยกระดับ ลดระดับ และ Stand Down แผนฉุกเฉินอย่างเป็นทางการ รวมถึงให้ Strategic Direction ตามอำนาจที่กำหนด | DCC | `CANONICAL` |
| TERM-ORG-005 | **SOC Operator** | ผู้ปฏิบัติงานแนวหน้าประจำ SOC รับผิดชอบ Seat หรือพื้นที่ที่ได้รับมอบหมาย ทำหน้าที่เฝ้าระวัง ตรวจสอบ บันทึก เปิดหรืออัปเดต Case ประสานงาน ติดตามผล รวบรวม Evidence และส่งมอบงาน | SOC | `CANONICAL` |
| TERM-ORG-006 | **SOC Supervisor** | ผู้ควบคุมภาพรวมของผลัด ครอบคลุมบุคลากร เหตุการณ์ ระบบ ข้อมูล คุณภาพงาน ความเสี่ยง การจัดลำดับความสำคัญ และการยกระดับ ไม่ถือเป็น IC โดยอัตโนมัติ เว้นแต่ Approved SOP กำหนดไว้ | SOC | `CANONICAL` |
| TERM-ORG-007 | **Incident Commander: IC** | ตำแหน่งผู้บัญชาการเหตุการณ์ที่ Approved SOP ของแต่ละแผนกำหนดไว้ล่วงหน้า มีอำนาจสั่งการการตอบสนอง ณ หน้างานหรือ Incident Command Post และประสานกับ SOC และ DCC | DCC | `CANONICAL` |
| TERM-ORG-008 | **Field IC** | คำที่อาจพบในเอกสารเดิม ใช้เพื่อค้นหาหรืออ้างข้อความต้นทางเท่านั้น เอกสารใหม่ต้องใช้ `IC` | DCC | `DO_NOT_USE` |
| TERM-ORG-009 | **Incident Command Post: ICP** | จุดบัญชาการเหตุการณ์ส่วนหน้า ซึ่ง IC และหน่วยตอบสนองใช้ควบคุม ประสาน และติดตามสถานการณ์หน้างาน | IC | `CANONICAL` |
| TERM-ORG-010 | **Rear Command** | การสนับสนุนการสั่งการจากส่วนหลังโดย SOC และ DCC ครอบคลุมข้อมูล การสื่อสาร การประสานงาน การบันทึก และ Strategic Direction คำนี้ไม่ทำให้ SOC มีอำนาจประกาศแผน | DCC | `CONTEXT_ONLY` |
| TERM-ORG-011 | **Emergency Operation Team: EOT** | ทีมตอบสนองเหตุฉุกเฉินที่ได้รับการแจ้งหรือ Dispatch ให้ดำเนินการตามประเภทเหตุและ Approved SOP ไม่ถือเป็น IC โดยอัตโนมัติ | EOT | `CANONICAL` |
| TERM-ORG-012 | **Security Management Team: SMT** | ทีมบริหาร ควบคุม และประสานงานด้าน Security ครอบคลุม In-Building, Traffic และ Common Infrastructure การปฏิบัติภายใต้แผนฉุกเฉินยังต้องเป็นไปตาม IC, DCC และ Approved SOP | SMT | `CANONICAL` |
| TERM-ORG-013 | **Security Officer** | เจ้าหน้าที่รักษาความปลอดภัยภาคสนาม ครอบคลุมเจ้าหน้าที่ของ PCS และ G4S เมื่อความรับผิดชอบแตกต่างกันต้องระบุบริษัท พื้นที่ หรือผลัด | SMT | `CANONICAL` |
| TERM-ORG-014 | **Security Supervisor** | หัวหน้าชุดรักษาความปลอดภัยที่ควบคุมและประสานการปฏิบัติงานของ Security Officer ในพื้นที่หรือผลัดที่ได้รับมอบหมาย ต้องใช้ชื่อเต็มเพื่อไม่ให้สับสนกับ SOC Supervisor | SMT | `CANONICAL` |
| TERM-ORG-015 | **Security** | คำเรียกรวมของหน่วยงานและบุคลากรด้านการรักษาความปลอดภัย ห้ามใช้เป็นผู้รับผิดชอบแบบไม่ระบุตำแหน่งใน SOP, Swimlane, Task Template หรือ Authority Matrix | SMT / SOC | `CONTEXT_ONLY` |
| TERM-ORG-016 | **Operational Owner** | หน่วยงานหลักที่รับผิดชอบการดำเนินการ ติดตาม และควบคุมงานหรือเหตุการณ์จนถึงเกณฑ์ที่กำหนด ไม่จำเป็นต้องเป็น Asset Owner, System Owner, Commercial Owner หรือผู้เปิด Case | ตามบริบท | `CANONICAL` |
| TERM-ORG-017 | **Supporting Owner** | หน่วยงานที่สนับสนุน Operational Owner ด้วยข้อมูล ทรัพยากร ระบบ หรือการดำเนินการเฉพาะด้าน แต่ไม่ใช่ผู้รับผิดชอบหลัก | ตามบริบท | `CANONICAL` |
| TERM-ORG-018 | **Knowledge Owner** | บุคคลหรือตำแหน่งที่รับผิดชอบความถูกต้อง ความเป็นปัจจุบัน และการอนุมัติเนื้อหาของ Knowledge Item ไม่หมายถึงผู้เขียน ผู้รับมอบหมายงาน หรือ Operational Owner โดยอัตโนมัติ | ตาม Metadata | `CANONICAL` |
| TERM-ORG-019 | **Notification Matrix** | เอกสารหรือข้อมูลควบคุมที่กำหนดว่าต้องแจ้งใคร ภายใต้เหตุ ระดับ หรือแผนใด การได้รับแจ้งไม่เท่ากับได้รับอำนาจสั่งการ | DCC | `PENDING_VALIDATION` |
| TERM-ORG-020 | **Authority Matrix** | เอกสารควบคุมที่กำหนดขอบเขตอำนาจในการตัดสินใจ อนุมัติ สั่งการ และยกระดับ ห้าม AI สร้างอำนาจจาก Job Title หรือ RACI โดยไม่มีเอกสารรองรับ | DCC | `PENDING_VALIDATION` |

ห้ามใช้คำว่า `Supervisor` เพียงคำเดียวเมื่ออาจหมายถึงทั้ง SOC Supervisor และ Security Supervisor

## การสั่งการและการตอบสนองฉุกเฉิน (Command and Emergency Response)

| Term ID | คำมาตรฐาน | คำนิยามและกฎการใช้ | Owner | Term Usage |
|---|---|---|---|---|
| TERM-CMD-001 | **Formal Plan Activation** | การประกาศใช้แผนฉุกเฉินอย่างเป็นทางการโดย DCC การ Dispatch หรือการดำเนินการป้องกันเบื้องต้นของ SOC ไม่ถือเป็น Formal Plan Activation | DCC | `CANONICAL` |
| TERM-CMD-002 | **Immediate Life Safety Response** | การดำเนินการป้องกันเบื้องต้นเพื่อคุ้มครองชีวิตและลดความเสี่ยง ระหว่างที่การประกาศใช้แผนอย่างเป็นทางการยังอยู่ระหว่างดำเนินการ ไม่ใช่การประกาศใช้แผน | SOC | `CANONICAL` |
| TERM-CMD-003 | **Dispatch** | การแจ้งและมอบหมาย EOT หรือ Security Role ที่ระบุให้เข้าตรวจสอบหรือดำเนินการ ไม่เท่ากับ Plan Activation และไม่ใช่การโอนอำนาจ Command | SOC | `CANONICAL` |
| TERM-CMD-004 | **Preliminary Area Control** | การกั้น จำกัด หรือควบคุมการเข้าถึงพื้นที่เบื้องต้นเพื่อรักษาระยะห่าง ลดการสัมผัสอันตราย และสนับสนุนความปลอดภัย | SOC / Security Role | `CANONICAL` |
| TERM-CMD-005 | **Safety Guidance** | คำแนะนำให้บุคคลรักษาระยะห่าง หลีกเลี่ยงพื้นที่ หรือเคลื่อนออกจากจุดเสี่ยง ไม่ควรเรียกว่า Evacuation Order เว้นแต่ผู้มีอำนาจสั่งอพยพ | SOC / Security Role | `CANONICAL` |
| TERM-CMD-006 | **First Aid Coordination** | การประสานผู้มีหน้าที่ด้านการปฐมพยาบาลให้เข้าช่วยเหลือ ไม่หมายถึงการวินิจฉัยทางการแพทย์โดย SOC | EOT / หน่วยแพทย์ | `CANONICAL` |
| TERM-CMD-007 | **Preliminary Access Control** | การจำกัดสิทธิ์หรือควบคุมการเข้าออกพื้นที่ชั่วคราวเพื่อป้องกันความเสี่ยง ต้องแยกจากชื่อระบบ Access Control System | SOC / Security Role | `CANONICAL` |
| TERM-CMD-008 | **Operational Escalation** | การยกระดับข้อมูล การแจ้งเตือน การประสานทรัพยากร หรือการรายงานต่อผู้มีอำนาจสูงขึ้น โดยยังไม่ถือว่าแผนหรือระดับแผนถูกเปลี่ยน | SOC | `CANONICAL` |
| TERM-CMD-009 | **Plan Escalation** | การเปลี่ยนแผนหรือระดับการตอบสนองอย่างเป็นทางการโดย DCC ตาม Approved SOP ห้ามใช้แทนการรายงานเหตุขึ้นตามสายงาน | DCC | `CANONICAL` |
| TERM-CMD-010 | **De-escalation** | การประกาศลดระดับการตอบสนองหรือระดับแผนโดย DCC การที่สถานการณ์ดีขึ้นไม่ถือเป็น De-escalation จนกว่าจะมีคำประกาศ | DCC | `CANONICAL` |
| TERM-CMD-011 | **Stand Down (ยุติแผน)** | คำประกาศอย่างเป็นทางการจาก DCC เพื่อยุติการใช้แผนและการตอบสนองภายใต้แผน Mozart Case, Recovery, AAR หรือ Corrective Action อาจยังดำเนินต่อ | DCC | `CANONICAL` |
| TERM-CMD-012 | **Plan Termination** | Alias ที่มีความหมายเดียวกับ Stand Down ไม่ใช่อีกสถานะหนึ่ง เอกสารใหม่ให้ใช้ `Stand Down (ยุติแผน)` | DCC | `DO_NOT_USE` |
| TERM-CMD-013 | **Strategic Direction** | ทิศทางหรือกรอบการตัดสินใจระดับภาพรวมที่ DCC ให้แก่ IC, SOC หรือหน่วยงานที่เกี่ยวข้อง ไม่ใช่คำสั่ง Tactical รายจุดโดยอัตโนมัติ | DCC | `CANONICAL` |
| TERM-CMD-014 | **Tactical Command** | การสั่งการเชิงปฏิบัติ ณ จุดเกิดเหตุเกี่ยวกับกำลัง ทรัพยากร พื้นที่ และขั้นตอนตอบสนอง ภายใต้อำนาจของ IC และ Approved SOP | IC | `CANONICAL` |
| TERM-CMD-015 | **Life Safety** | สภาวะที่มีหรืออาจมีผลโดยตรงต่อชีวิต การบาดเจ็บรุนแรง หรือความปลอดภัยทางกายภาพ สามารถเป็น Trigger สำหรับ Immediate Life Safety Response ได้โดยไม่ต้องรอการยืนยัน CAT | DCC / SOC | `CANONICAL` |
| TERM-CMD-016 | **Active Threat** | ภัยคุกคามที่กำลังเกิดขึ้น ดำเนินต่อเนื่อง หรือสามารถก่ออันตรายได้ทันที เกณฑ์ Trigger รายเหตุต้องอ้างอิง Approved SOP | DCC | `PENDING_VALIDATION` |
| TERM-CMD-017 | **Maximum Security** | การจัดประเภทพื้นที่ที่กำหนดให้ใช้การตรวจสอบ การยกระดับ และการรักษาร่องรอยข้อมูลสูงกว่าพื้นที่ทั่วไป ปัจจุบัน One Power เป็นพื้นที่ Maximum Security คำนี้ไม่กำหนด CAT หรือ Plan Activation โดยอัตโนมัติ | DCC / One Power | `CANONICAL` |

## Mozart Case Management

| Term ID | คำมาตรฐาน | คำนิยามและกฎการใช้ | Owner | Term Usage |
|---|---|---|---|---|
| TERM-MOZ-001 | **Mozart** | ระบบ Case Management ที่ใช้เปิด บันทึก มอบหมาย ประสาน ติดตาม และจัดเก็บผลการดำเนินการของ Case ห้ามเรียกว่า Incident Management System | SOC | `CANONICAL` |
| TERM-MOZ-002 | **Case** | Record ใน Mozart ที่ใช้ติดตามเหตุ ปัญหา คำขอ หรือกิจกรรมตาม Event Type การเปิด Case ไม่ได้ยืนยันว่าเหตุเกิดขึ้นจริงหรือมีผู้กระทำผิด | SOC | `CANONICAL` |
| TERM-MOZ-003 | **Incident** | เหตุการณ์ในโลกจริงหรือคำที่ใช้ใน Approved SOP/Report ตามบริบท ไม่ใช่ชื่อ Record มาตรฐานของ Mozart และห้ามใช้แทน `Case` ใน HOTO หรือ Mozart Documentation | SOC | `CONTEXT_ONLY` |
| TERM-MOZ-004 | **Inquiry** | การสอบถามข้อมูลทั่วไปที่ไม่จำเป็นต้องเปิด Mozart Case และไม่มี Case No. หากภายหลังเข้าเกณฑ์ต้องสร้าง Case ตาม Workflow | SOC / Contact Centre | `CANONICAL` |
| TERM-MOZ-005 | **Case No.** | หมายเลขอ้างอิงเฉพาะของ Case ใช้สำหรับค้นหา เชื่อมโยง รายงาน และส่งมอบงาน ห้ามสร้างหรือคาดเดาหมายเลข | SOC | `CANONICAL` |
| TERM-MOZ-006 | **Mozart ID** | Alias ที่อาจพบในข้อมูลเดิม เอกสารและรายงานใหม่ต้องใช้ `Case No.` | SOC | `DO_NOT_USE` |
| TERM-MOZ-007 | **Event Type** | ประเภทเหตุหรือประเภทงานที่กำหนดโครงสร้างของ Case และ Task Template ไม่ใช่ CAT, Case Status หรือชื่อ Owner | SOC | `CANONICAL` |
| TERM-MOZ-008 | **Task Template** | ชุดขั้นตอน งานย่อย หรือข้อมูลที่ต้องดำเนินการภายใต้ Event Type ไม่สามารถให้อำนาจเกิน Approved SOP หรือ Authority Matrix | SOC | `CANONICAL` |
| TERM-MOZ-009 | **Verification** | กระบวนการตรวจข้อมูลด้วย CCTV ระบบ Evidence การสอบถามหน้างาน หรือแหล่งข้อมูลที่เหมาะสม เพื่อแยกข้อเท็จจริงจากข้อมูลที่ยังไม่ยืนยัน | SOC | `CANONICAL` |
| TERM-MOZ-010 | **Pending Verification** | คำอธิบาย Workflow สำหรับ Case ที่เปิดก่อนยืนยันข้อเท็จจริง ไม่ใช่ Mozart Case Status | SOC | `CONTEXT_ONLY` |
| TERM-MOZ-011 | **Urgent Handling** | วิธีดำเนินการเร่งด่วนที่อนุญาตให้เปิด Case ก่อน Verification เมื่อเข้าเกณฑ์ที่กำหนด เป็น Response Condition ไม่ใช่ CAT Classification | SOC | `CANONICAL` |
| TERM-MOZ-012 | **Urgent Case** | Case ที่ใช้ Urgent Handling ครอบคลุม CAT 1, CAT 2 หรือเหตุที่ยังไม่ทราบ CAT แต่เกี่ยวข้องกับ Life Safety, Active Threat, Maximum Security หรือหลาย Zone | SOC | `CANONICAL` |
| TERM-MOZ-013 | **CAT Classification** | การจัดระดับของ Case ตาม Classification/Escalation Matrix ห้าม AI เดาความหมาย Threshold, SLA หรือ Authority ของ CAT | SOC / DCC | `PENDING_VALIDATION` |
| TERM-MOZ-014 | **CAT 1 / CAT 2 / CAT 3** | Controlled Values ที่ใช้ใน Mozart และ HOTO คำนิยามและเกณฑ์ต้องตรวจสอบกับ Master Data และ Classification/Escalation Matrix ล่าสุด | SOC / DCC | `PENDING_VALIDATION` |
| TERM-MOZ-015 | **False Alarm** | Alert ที่หลัง Verification พบว่าไม่ตรงกับเหตุหรือเงื่อนไขที่ระบบตั้งใจตรวจจับ การสรุป HOTO ด้าน Security ต้องไม่รวม False Alarm เป็น Actual Security Case | SOC | `PENDING_VALIDATION` |
| TERM-MOZ-016 | **Active Case** | Case ที่ยังต้องติดตาม อัปเดต ประสาน หรือส่งมอบ การจับคู่กับ System Status ต้องอ้างอิง Mozart Master Data | SOC | `PENDING_VALIDATION` |
| TERM-MOZ-017 | **Timeline** | บันทึกลำดับเหตุการณ์และการดำเนินการตามเวลา โดยระบุข้อเท็จจริง ผู้ดำเนินการ การประสานงาน และผลที่ได้รับ | SOC | `CANONICAL` |
| TERM-MOZ-018 | **Evidence** | ข้อมูลที่สนับสนุนการตรวจสอบและติดตาม Case เช่น CCTV ภาพถ่าย คลิป Alarm Log, Access Log ทะเบียนรถ เวลา และข้อมูลหน้างาน การมี Evidence ไม่ให้อำนาจ AI ตัดสินความผิด | SOC | `CANONICAL` |
| TERM-MOZ-019 | **Findings** | ข้อค้นพบจากการตรวจสอบ Evidence หรือการยืนยัน ต้องแยกจาก Assumption, Opinion และ Recommendation | SOC | `CANONICAL` |
| TERM-MOZ-020 | **Resolution** | ผลการดำเนินการหรือสภาพที่ทำให้ Case ถูกควบคุม แก้ไข ส่งมอบ หรือถึงเกณฑ์ยุติ การแจ้งหน่วยงานเพียงอย่างเดียวไม่ถือเป็น Resolution หากยังไม่มีผล | SOC / Operational Owner | `CANONICAL` |
| TERM-MOZ-021 | **Resolve Case** | ขั้นตอนที่ SOC Operator ดำเนินการหลังบันทึกข้อมูล Findings/Resolution ครบถ้วนและผ่านการตรวจสอบจาก SOC Supervisor แล้ว | SOC | `CANONICAL` |
| TERM-MOZ-022 | **Close Case** | ขั้นตอนสุดท้ายของ Security Case ภายใต้ SOC Workflow ดำเนินการโดย SOC Supervisor ทุกกรณี หลัง Case ผ่าน Resolve Case และตรวจความครบถ้วนแล้ว | SOC Supervisor | `CANONICAL` |
| TERM-MOZ-023 | **Security Case** | Case ที่ใช้ Security Type และอยู่ภายใต้ SOC Workflow รวมถึง Case ที่ BMO, Retail Operation หรือ Contact Centre เปิดและส่งให้ SOC รับผิดชอบ | SOC | `CANONICAL` |
| TERM-MOZ-024 | **Maintenance Case** | Case ด้านความขัดข้อง การซ่อมบำรุง หรือการคืนสภาพระบบ ไม่อยู่ในอำนาจ Close Case ของ SOC Supervisor เว้นแต่มี Security Case แยกที่อยู่ภายใต้ SOC Workflow | System / Maintenance Owner | `CANONICAL` |
| TERM-MOZ-025 | **Linked Case Reference** | การเชื่อมโยง Case ที่เกิดจากเหตุเดียวกันหรือสัมพันธ์กัน เพื่อรักษาความต่อเนื่องของ Timeline, Owner และผลดำเนินการ | SOC / Operational Owner | `CANONICAL` |
| TERM-MOZ-026 | **Primary Case Owner** | หน่วยงานหลักที่รับผิดชอบอัปเดตและติดตาม Case จนถึงเกณฑ์ปิด ไม่จำเป็นต้องเป็นผู้เปิด Case หรือเจ้าของ Asset | ตาม Workflow | `CANONICAL` |
| TERM-MOZ-027 | **Service Level Agreement: SLA** | ระยะเวลา เป้าหมาย หรือข้อกำหนดที่ได้รับอนุมัติสำหรับการรับงาน ตอบสนอง อัปเดต หรือปิด Case ห้าม AI สร้าง SLA หรือ Threshold | Process Owner | `PENDING_VALIDATION` |
| TERM-MOZ-028 | **Handover/Takeover: HOTO** | การส่งมอบและรับมอบข้อมูลระหว่างผลัด ครอบคลุม Active Case ปัญหาระบบ งานคงค้าง ความเสี่ยง และสิ่งที่ต้องติดตาม ใช้ `Case` และ `Inquiry` ตามประเภทข้อมูล | SOC | `CANONICAL` |
| TERM-MOZ-029 | **Security Type** | ตัวเลือกที่ระบุว่า Case เป็นงานด้าน Security เมื่อเลือกค่านี้และส่ง Case ให้ SOC รับผิดชอบ Case จะเข้าสู่ SOC Workflow ไม่ว่าหน่วยงานใดเป็นผู้เปิด Case | SOC | `CANONICAL` |
| TERM-MOZ-030 | **SOC Workflow** | Workflow ด้าน Security ที่ SOC รับผิดชอบตั้งแต่รับมอบ Case การตรวจสอบ ประสาน ติดตาม บันทึก Findings/Resolution ผ่าน Resolve Case จนถึง Close Case | SOC | `CANONICAL` |

### Workflow การปิด Security Case

`SOC Operator จัดทำข้อมูล → SOC Supervisor ตรวจสอบ → SOC Operator Resolve Case → SOC Supervisor Close Case`

กฎนี้ใช้กับ Security Case ภายใต้ SOC Workflow แม้ BMO, Retail Operation หรือ Contact Centre จะเป็นผู้เปิด Case หาก Case ใช้ Security Type และถูกส่งให้ SOC รับผิดชอบ

DCC สามารถตรวจติดตามให้แน่ใจว่า Case ที่เกี่ยวข้องถูกปิด แต่ไม่ใช่ผู้ Resolve Case หรือ Close Case ภายใต้กฎนี้

## พื้นที่และการปฏิบัติงาน (Area and Operations)

| Term ID | คำมาตรฐาน | คำนิยามและกฎการใช้ | Owner | Term Usage |
|---|---|---|---|---|
| TERM-AREA-001 | **Common Infrastructure: CI** | โครงสร้างพื้นฐานและพื้นที่ส่วนกลางที่สนับสนุนการดำเนินงานระดับโครงการ ใช้เป็นชื่อเต็มทางการของ `CI` | SOC / BMO Estate | `CANONICAL` |
| TERM-AREA-002 | **CI Security** | Seat หรือ Function ที่เฝ้าระวังภาพรวมด้าน Physical Security ของ Common Infrastructure รวมถึงเหตุสำคัญและเหตุที่กระทบหลาย Zone | SOC | `CANONICAL` |
| TERM-AREA-003 | **CI Traffic** | Seat หรือ Function ที่เฝ้าระวังการจราจร การเคลื่อนตัวของรถ ทางเข้าออก Drop-off และพื้นที่จอดรถในขอบเขต Common Infrastructure | SOC | `CANONICAL` |
| TERM-AREA-004 | **Seat** | Function หรือจุดรับผิดชอบในการปฏิบัติงานของ SOC ไม่ได้หมายถึงเก้าอี้หรือสถานที่นั่งทางกายภาพเพียงอย่างเดียว | SOC | `CANONICAL` |
| TERM-AREA-005 | **Seat Assignment** | การมอบหมาย Operator ให้รับผิดชอบ Seat, Zone หรือ Function ตามช่วงเวลาและแผนกำลัง | SOC Supervisor | `CANONICAL` |
| TERM-AREA-006 | **Zone** | การแบ่งขอบเขตพื้นที่ปฏิบัติการของ SOC เพื่อจัดความรับผิดชอบและติดตามสถานการณ์ ไม่ใช้แทน Asset | SOC | `CANONICAL` |
| TERM-AREA-007 | **Asset** | อาคาร พื้นที่ หรือองค์ประกอบของโครงการที่มีขอบเขต การดำเนินงาน และผู้เกี่ยวข้องเฉพาะ | Asset Owner | `CANONICAL` |
| TERM-AREA-008 | **Shared Area** | พื้นที่ที่เกี่ยวข้องกับหลาย Asset หรือหลาย Owner ต้องตรวจสถานที่จริง ขอบเขตพื้นที่ Operational Owner และ Supporting Owner ก่อนสรุป | ตามพื้นที่ | `CANONICAL` |
| TERM-AREA-009 | **Multi-zone** | เหตุการณ์หรือผลกระทบที่เกี่ยวข้องกับมากกว่าหนึ่ง Zone และอาจต้องใช้การประสานงานระดับภาพรวม | SOC / DCC | `CANONICAL` |
| TERM-AREA-010 | **Operating** | Operational Status ที่ระบุว่า Asset เปิดดำเนินงานแล้ว ณ วันที่มีผล ไม่ได้หมายความว่าไม่มีงาน Fit-out, Defect หรือข้อจำกัดอื่น | Asset Owner | `CANONICAL` |

## ความแตกต่างบังคับ (Mandatory Distinctions)

| คำที่มักสับสน | กฎบังคับ |
|---|---|
| SOC กับ Cybersecurity SOC | One Bangkok SOC ใน KB นี้หมายถึง Physical Security |
| SOC Supervisor กับ Security Supervisor | ต้องใช้ชื่อเต็ม ห้ามใช้ `Supervisor` เดี่ยว ๆ เมื่อความหมายไม่ชัด |
| SOC Supervisor กับ IC | SOC Supervisor ไม่เป็น IC โดยอัตโนมัติ ต้องตรวจ Approved SOP |
| DCC กับ IC | DCC ควบคุมสถานะแผนและ Strategic Direction; IC สั่งการ Tactical ณ หน้างาน |
| Dispatch กับ Formal Plan Activation | Dispatch เริ่มการตอบสนองได้ แต่ไม่ใช่การประกาศใช้แผน |
| Operational Escalation กับ Plan Escalation | การรายงานขึ้นสายงานไม่เท่ากับการเปลี่ยนระดับแผน |
| Immediate Life Safety Response กับ Formal Plan Activation | SOC เริ่มป้องกันเบื้องต้นได้ แต่อำนาจประกาศแผนเป็นของ DCC |
| Stand Down กับ Close Case | การยุติแผนไม่ทำให้ Mozart Case ปิดโดยอัตโนมัติ |
| Case กับ Incident | Case คือ Record ใน Mozart; Incident คือเหตุการณ์จริงหรือคำตามบริบทเอกสาร |
| Inquiry กับ Case | Inquiry ไม่มี Case No. เว้นแต่ภายหลังเข้าเกณฑ์เปิด Case |
| Event Type กับ CAT | Event Type บอกประเภทเหตุ; CAT บอกระดับตาม Classification Matrix |
| Urgent Handling กับ CAT | Urgency เป็นวิธีตอบสนอง ไม่ใช่ระดับ CAT |
| Resolve Case กับ Close Case | Operator Resolve หลัง Supervisor ตรวจ; Supervisor Close Security Case |
| Security Case กับ Maintenance Case | ต้องแยก Workflow และ Owner แต่สามารถเชื่อมโยงกันได้ |
| Evidence กับข้อสรุปความผิด | Evidence สนับสนุนการตรวจสอบ แต่ไม่ใช่คำตัดสินความผิด |
| Findings กับ Assumption | Findings มาจากการตรวจสอบหรือหลักฐาน; Assumption ต้องติด Label |

## ข้อจำกัดของ AI (AI Constraints)

- ต้องใช้ Canonical Term ตามทะเบียนนี้
- ห้ามสร้างคำนิยาม CAT, SLA, Authority, Threshold หรือ System Status ขึ้นเอง
- ห้ามใช้คำที่เป็น `PENDING_VALIDATION` เสมือนเป็นข้อมูลยืนยันแล้ว
- ห้ามตีความ Job Title ว่ามี Command Authority โดยไม่มี Approved SOP หรือ Authority Matrix
- ห้ามตีความการเปิด Case ว่าเป็นการยืนยันเหตุหรือความผิด
- ห้ามให้ SOC Supervisor ปิด Maintenance, Retail หรือ Case ของหน่วยงานอื่นที่ไม่ใช่ Security Case ภายใต้ SOC Workflow
- ต้องแจ้ง Conflict เมื่อแหล่งข้อมูลใช้คำเดียวกันในคนละความหมาย

---
kb_id: WK-OBK-TASK-001
title: "กรอบการบริหาร Task ของ SOC (SOC Task Management Framework)"
description: "นิยามและ Controlled Structure สำหรับการบริหาร Project/Task จากไฟล์ Task Management ล่าสุดใน _SENSES SOC"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: operational_rule
source_authority: current_operational_practice
sensitivity: internal
---

# กรอบการบริหาร Task ของ SOC (SOC Task Management Framework)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | กำหนด Field, Task Category, Task Type และหลักการเลือกใช้สำหรับการติดตามงานของ SOC |
| Owner | SOC |
| Last Updated | 29 สิงหาคม 2026 |
| Status | Active |
| Source | `Task Management ล่าสุด` — Google Sheet ID `1hKbSJKD2LKq4y9Q1X55aLAG3JED2FbN4Q8CgCfQ1gtc` |

## 1. โครงสร้าง Field

| Field | Definition | หลักการใช้ |
|---|---|---|
| Project | ชื่อโครงการหรือหัวข้องานหลักที่ต้องดำเนินการ | ตั้งชื่อให้สื่อความหมายชัดเจน เช่น Additional CCTV – Tower 2 หรือ Dispatcher Essential Training |
| Task | รายละเอียดงานภายใต้ Project | ระบุสิ่งที่ต้องทำให้ชัดและติดตามความคืบหน้าได้ |
| Module | ระบบ กระบวนการ หรือ Functional Area ที่งานเกี่ยวข้อง | เลือกตามระบบหรือผู้รับผิดชอบหลัก เช่น CCTV, LPR, Mozart, Dispatcher, SOP/WI |
| Task Category | ประเภทของ Deliverable | เลือกตามผลลัพธ์ของงาน เช่น Report, Training, Document, Configuration, Implementation |
| Task Type | ลักษณะงานตามรูปแบบการดำเนินงาน | ใช้แยก Project, Routine และ Ad-Hoc |
| Frequency | ความถี่ในการดำเนินงาน | เช่น Daily, Weekly, Monthly, Quarterly, Yearly, One-time, On Demand |
| Owner | Task Owner ผู้รับผิดชอบหลัก | ระบุ Supervisor หรือผู้รับผิดชอบหลักหนึ่งคน แม้มีผู้ช่วยหลายคน |
| Due Date | วันที่ต้องดำเนินการหรือกำหนดแล้วเสร็จ | ใช้ติดตาม Deadline โดยเฉพาะ Project และ Ad-Hoc |
| Status | สถานะปัจจุบัน | ใช้มาตรฐานเดียวกันทั้งทีม เช่น Not Started, In Progress, Pending, Completed, Cancelled |

## 2. Task Category

| Category | Definition | ตัวอย่าง |
|---|---|---|
| Report | รวบรวม วิเคราะห์ และสรุปข้อมูลเพื่อรายงานหรือเสนอแนะ | Monthly Report, Incident Report, TTX Report, Site Survey Report, CCTV Assessment, LPR Blacklist Review |
| Training | จัดทำหลักสูตร ฝึกอบรม ถ่ายทอดความรู้ หรือประเมินการเรียนรู้ | CCTV Essential Training, Dispatcher Training, LPR Training, Refresher Training |
| Policy / Rule / Regulations | กำหนดหรือปรับปรุงนโยบาย ระเบียบ ข้อบังคับ และประกาศ | Attendance Policy, Security Policy, Management Memo, Rules & Regulations |
| Document | จัดทำหรือปรับปรุงเอกสารปฏิบัติงานที่ไม่ใช่ Policy หรือ Report | Manual, Guideline, Checklist, Template, Form, Infographic, Awareness Material |
| TTX | วางแผน ดำเนินการ และสรุปผล Tabletop Exercise | Lost Person TTX, Active Shooter TTX, Evacuation TTX |
| GDX | วางแผน ดำเนินการ และสรุปผล Ground Exercise / Drill | Protester Management Drill, Fire Drill, Evacuation Drill |
| Account | จัดการบัญชีผู้ใช้ สิทธิ์ และการลงทะเบียนระบบ | Create User, Delete User, Reset Password, Permission Change, Face Registration |
| Configuration | ตั้งค่า แก้ไข หรือปรับแต่งระบบโดยไม่มีการติดตั้งระบบ/อุปกรณ์ใหม่ | Configure LPR, Create Virtual Patrol Route, Camera Mapping, Dispatcher Setting, Access Control Configuration |
| Implementation | ติดตั้ง นำระบบ/อุปกรณ์ใหม่มาใช้ Upgrade หรือ Rollout | Additional CCTV Installation, New System Deployment, Device Replacement, Software Rollout |
| Meeting | ประชุม ติดตามความคืบหน้า Workshop และบันทึกผล | Weekly Meeting, Project Meeting, Management Review, Workshop |
| Audit | ตรวจประเมิน ติดตาม Corrective Action และเตรียม Audit | Internal Audit, ISO Audit, NCR, Corrective Action, Compliance Review |

## 3. Task Type

| Task Type | Definition | หลักการเลือกใช้ |
|---|---|---|
| Project | งานมีวัตถุประสงค์ จุดเริ่มต้น จุดสิ้นสุด และ Due Date; เมื่อเสร็จให้ปิดงาน | ใช้กับงานครั้งเดียวหรือโครงการพิเศษ เช่น Additional CCTV Installation, New SOP Development |
| Routine | งานประจำตามรอบเวลาเพื่อสนับสนุนการปฏิบัติงานและรักษามาตรฐาน | ใช้กับ Daily/Weekly/Monthly/Yearly เช่น Monthly Report, CCTV Monitoring Review, Annual TTX |
| Ad-Hoc | งานเฉพาะกิจจากสถานการณ์ คำร้องขอ หรือเหตุการณ์ที่กำหนดรอบล่วงหน้าไม่ได้ | เช่น Incident Investigation, CCTV Footage Request, Emergency Meeting, User Permission Request |

## 4. Status Standard

Current source กำหนดตัวอย่างมาตรฐานสถานะร่วมกัน ได้แก่:

- `Not Started`
- `In Progress`
- `Pending`
- `Completed`
- `Cancelled`

หากมีการเพิ่มหรือเปลี่ยน Controlled Status ใน Master Sheet ให้ Source ล่าสุดใน `_SENSES SOC` มีลำดับเหนือรายการนี้จนกว่าจะ Sync KB

## 5. AI Usage Rule

- AI ควรใช้ Field และ Category ตาม Master นี้เมื่อช่วยสร้างหรือจัดหมวด Task ใหม่
- Owner ต้องหมายถึงผู้รับผิดชอบหลัก ไม่ใช่รายชื่อผู้ช่วยทั้งหมด
- Project/Ad-Hoc ที่มี Deadline ควรมี Due Date ชัดเจน
- AI ห้ามสร้าง Task Category ใหม่เป็นมาตรฐานโดยไม่มี Source หรือ Boss Confirmed Decision

## Source

- `_SENSES SOC` → `SOC Management` → `01. Task` → `Task Management ล่าสุด`
- Sheet tabs reviewed: `Title Definition`, `Task Category Definition`, `Task Type Definition`

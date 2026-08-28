---
kb_id: WK-OBK-MOZ-SRC-001
title: "ทะเบียน Source ของ Mozart Event Type และ Task Template (Mozart Event & Task Source Register)"
description: "กำหนด Source ชุดปัจจุบันสำหรับ Event Type, Task Template, Case Manual Log และ Mozart Down/BCP เพื่อใช้สร้าง Mozart Master Knowledge"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: current_operational_practice
sensitivity: internal
---

# ทะเบียน Source ของ Mozart Event Type และ Task Template (Mozart Event & Task Source Register)

## Canonical Current Source Folder

`_SENSES SOC` → `SOC Management` → `04. Project` → `03. Mozart`  
Folder ID: `1P5Vkhvk5DYggUWwiLQGgHdZqz0T9TmsH`

## Source Priority

| Priority | Source | Drive ID | State |
|---|---|---|---|
| 1 | `20260813_Mozart_Task_Template_Master_Data.xlsx` | `1aHfBY_02tbCcO_B97ypWiwZSpJilt2QI` | Current master candidate; modified 26 Aug 2026 |
| 2 | `Implementation of Event Type Task Template - OBK (1).docx` | `16Nnq0z7NxiwHrT04b6PbwdQo2Ey-PkJE` | Implementation reference |
| 3 | `Security Event type - Description.xlsx` | `1A4etJ6zOMIsI2nNd8AbGXx1_k-ks1fB-` | Event Type definition source |
| 4 | `20260813_Mozart_Task_Template_Master_Data(1).xlsx` | `1yeJHBCy3SHhL9ADO3ZrHU6eCePI0fSyv` | Historical/older copy |
| 5 | `20260812_Mozart_Task_Template_Master_Data.xlsx` | `10pmmKr3QkR-PME45sI0Otxmg7NXPicpO` | Previous dated version |
| 6 | `Mozart Task Template - Master Data (1).xlsx` | `1t6TB1V7OJteMpu0QVYMkxuaejTd0_OxV` | Earlier source |

## Supporting Mozart Sources

### Case Manual Log

`_SENSES SOC` → `SOC Team` → `01. SOC Documents` → `03. Mozart`

- `20260811 OB-SOP-FR-DCC-0201 - Case Manual Log Template.xlsx` — `19FjOybLEm3UXIVGcZzukn5ypXdRSETy0`

### Mozart Down / Business Continuity

- Project folder `Mozart Down` — `17avGwSgoEROmFyBVyfY7IPlVcW2JMJBU`
- Approved Rev.01 Source: `OB-SOP-DCC-0002 - BCP - Mozart Down - RV.01 - signed.pdf` — `1Sm0kSOMHaOCwL6_Cu0hhs1o3gZS_w04W`

## Target Canonical Data Model

เมื่อ Extract Master Data ให้ Normalize อย่างน้อย:

- Security Event Type
- Description / Usage Criteria
- CAT / Severity classification where available
- Default Task sequence
- Task Description
- Responsible Role (`SOC Operator`, `SOC Supervisor`, or other stakeholder when source supports it)
- Trigger / Decision Point
- Evidence / Information required
- Escalation requirement
- Findings / Resolution requirement
- SLA or timing requirement where explicitly defined
- SOP/Swimlane reference
- False Alarm applicability where defined
- Source file/version/date

## Source Control Rule

- ห้ามใช้วันที่ในชื่อไฟล์เพียงอย่างเดียวตัดสิน Current Master; ต้องพิจารณา Modified Date, location และ content conflict ด้วย
- Source `1aHfBY_02tbCcO_B97ypWiwZSpJilt2QI` เป็น Current Master Candidate ณ 29 Aug 2026 เพราะอยู่ใน Canonical Shared Drive folder และมี modified timestamp ล่าสุดในชุดที่พบ
- หาก Master Data ขัดกับ Approved SOP/WI ให้ Approved SOP/WI มี Source Authority สูงกว่า จนกว่าจะมี Approved change document หรือ Boss Confirmed Decision

## Relationship to Existing KB

- `WK-OBK-MOZ-001` = Canonical Mozart Case Management rules
- `WK-OBK-MOZ-SRC-001` = Source Register สำหรับ Event Type/Task Master และ supporting files
- หลัง Extract ครบควรสร้าง Atomic Knowledge ตาม Event Type/Task Family หรือ Master Table โดยไม่ทำให้ `WK-OBK-MOZ-001` กลายเป็นไฟล์รวมขนาดใหญ่เกินไป

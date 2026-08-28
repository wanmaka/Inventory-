---
kb_id: WK-OBK-OPTASK-001
title: "คลังงานประจำ SOC Operator (SOC Operator Task Library)"
description: "ทะเบียน Source สำหรับงานประจำ Operator แยกตาม CI Traffic, Zone 1, Zone 2, Compound และ Checklist/summary จาก _SENSES SOC"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: current_operational_practice
sensitivity: internal
---

# คลังงานประจำ SOC Operator (SOC Operator Task Library)

Source Root: `_SENSES SOC` → `SOC Team` → `05. Operator Task`  
Folder ID: `1FbaBUGC0hXKmZNVhEPisIym9A4sXqbmu`

## Domain Structure

| Domain | Drive ID | Target Knowledge |
|---|---|---|
| 01. CI Traffic | `1qJhLWlxV1FL8pUz30kVUnsOYBrrp3Vbw` | CI Traffic monitoring, GPS/transport operational tasks |
| 03. Zone 1 | `1CnTSC0q_-ztNPhut1RimuAEpfQFXI7S9` | Zone 1 Operator routines |
| 04. Zone 2 | `10vP2LiHVrpkO-lyy8XkYmbknpu0JrzOB` | Zone 2 Operator routines |
| 07. Compound | `16GnHFozewJDE1BZ69fzzKLfE4foPfdeL` | Compound/common-area routines |

## Current Files at Root

- `Summary.xlsx` — `1H7HX2CGhta5M23a3CR-5EwoCMxM78XFK`
- `CCTV Offline Checklist.xlsx` — `1m0WkQUwV2I6ibJdboyXWyFfLUOKI1O5e`

## CI Traffic Current Source

- `Limobus One Bangkok 20260717.xlsx` — `1bCiRxoNzSitNhgkQ_HeCazV9vFggD9D0`

## Target Canonical Task Model

เมื่อ Extract แต่ละ Operator Task ให้ Normalize อย่างน้อย:

- Task Name
- Purpose
- Frequency / Shift applicability
- System / Module
- Area / Zone
- Input / Source to monitor
- Required action
- Abnormal condition / trigger
- Mozart Case trigger
- Escalation / notification
- Record / evidence requirement
- Completion criteria
- Supervisor verification where required
- Source reference/version

## Data Handling

Detailed sensitive map, camera position, access point or personal/vehicle data must remain a restricted reference. The KB should preserve the operational rule and decision logic necessary for execution without exposing unnecessary security-sensitive detail.

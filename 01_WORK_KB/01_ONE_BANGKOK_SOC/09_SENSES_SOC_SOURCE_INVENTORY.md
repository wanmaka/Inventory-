---
kb_id: WK-OBK-SRCINV-001
title: "ทะเบียน Source Inventory _SENSES SOC (_SENSES SOC Source Inventory Register)"
description: "ทะเบียนแหล่งข้อมูลระดับ Workstream และ Source Folder/File ที่ตรวจพบใน Shared Drive _SENSES SOC สำหรับควบคุม Full Import เข้าสู่ One Bangkok SOC Master Knowledge Base"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: one_bangkok_soc
knowledge_type: source_register
source_authority: current_operational_practice
sensitivity: internal
---

# ทะเบียน Source Inventory _SENSES SOC

## Source of Truth

- Shared Drive: `_SENSES SOC`
- Drive ID: `0AJpAwl9n5sLbUk9PVA`
- Raw Source / Current Source of Truth: Google Drive
- Repository role: Register, sanitized extract, cross-reference and reusable knowledge only

## Top-level structure confirmed

| Source | Drive ID | Scope | Import status |
|---|---|---|---|
| SOC Management | `1bbs9_mzwZkNiqW6QYGlDJNA_Tw08vviY` | Management task, schedule, report, project, procurement, document control, performance evaluation | Indexed / extraction pending |
| SOC Team | `1tTrpjlEBhNjD0KeGbPYjKk6QJ2mtg40f` | SOC documents, SOP, training, CCTV records, operator task, activity picture | Indexed / extraction pending |

## SOC Team workstreams

| Workstream | Drive ID | Scope | Import status |
|---|---|---|---|
| 01. SOC Documents | `13nYhcjxzVUXFGCrKSl3g39fMDxcG2Pr2` | Announcement, Mozart, Guard Tour, Virtual Patrol, Blacklist/Whitelist/Watchlist, Video Analytic, OBK Layout, CCTV, Event, Work Schedule, Other | Indexed / extraction pending |
| 02. Standard Operation Procedure (SOP) | `1EJtxbkFTKHNyN5QMNmRmf41cmKSvOult` | Visio Swimlane, PDF Swimlane, SOP Document, Support Document, terminology, release records | Register active / content extraction continues |
| 03. Training | `1Kgt089IJTJQbCS3WoHqb9rixfm7WYWdy` | OJT, General Training, FCC Training, Examination, Training Record, Weekly Training | Indexed / extraction pending |
| 04. CCTV Document and Tracking | `1XOEyaDfxEgfkfyRDwdrsb1vYdiu17FT_` | Tracking, CCTV Request Form, Forms, CCTV Record | Indexed / metadata/sanitized extraction pending |
| 05. Operator Task | `1FbaBUGC0hXKmZNVhEPisIym9A4sXqbmu` | CI Traffic, Zone 1, Zone 2, Compound and operational task references | Indexed / extraction pending |
| 06. Activity Picture | `18oyFGXdkJIEiWJbZGQnLJnRMl7e_pXlW` | Operational/training activity images | Metadata/reference only |

## SOC Documents sub-workstreams

| Workstream | Drive ID | Import handling |
|---|---|---|
| Announcement | `1LlNQI32YW_VzypFpu3gKaCgdxuP2WoFi` | Extract approved operating announcements; preserve dates/version |
| Mozart | `1cd0pUA3XxEi-eNoDwkV6OQiWnTjUxlsJ` | Build Mozart master and cross-reference SOP/DCC procedure |
| Guard Tour | `1qTcJQjx5XsJYNTLWEy0m0QNLyMJ0ZloU` | Build Guard Tour operational library and record-source index |
| Virtual Patrol | `1QXuxn3Iwpk0cD1zb-T6Fy3Alcn3swg_k` | Build Virtual Patrol operational library and record-source index |
| Blacklist / Whitelist / Watchlist | `1nZIYqFwcTHaRwVKxdnlEX4Dn4IFFeYvm` | Metadata/sanitized rules only; no identity/PII/raw plate lists |
| Video Analytic | `1VxaF67v2KSy3ccA0Grrl0DWzh0zbwO5n` | Extract policy/use-case knowledge; preserve system limits |
| OBK Layout | `1sPkcrIvv_pqDo-htsHswEXEgBN8c1Exd` | Store sanitized zone/layout knowledge only; no sensitive security detail |
| CCTV | `1ui0zVrvLkDE3D8nCzNJjQSzmcQqmt1gW` | Build CCTV operational reference and current issue/source index |
| Event | `1aVLhAmeQU9_vlovB-wTBDicFfdZCxV-v` | Build event/readiness reference library |
| Work Schedule | `1d9t5RcDbL4ysE7dfAiRI_g-H4XVEB-UW` | Operational scheduling reference; avoid unnecessary staff PII |
| Other | `1hetxLAjzoHMOKphbhlVERlU9R7RVCwER` | Triage supporting references individually |

## SOP structure confirmed

- `01. Visio Swimlane` — `1IAL5BCv8NoghgWvf_H4Os-o0wyzJuu48`
- `02. PDF Swimlane` — `1AxWx-HjL-BAQRGyLUAdvqEPL_OWpkYFj`
- `03. SOP Document` — `1ZYw3zBRyovp25irgsS_fMbhELyARr0B4`
- `04. Support Document` — `1rCfivZt1CWO8LWh9a6GmmNNTYWQfgjyR`
- Revision folders confirmed: Draft, Rev.00, Rev.01
- Rev.01 confirmed categories include Emergency Plan and DCC

## Training structure confirmed

- OJT Training — `1l5gcvA4ZvyHpBMFVQGG8I36Rgsfm_rrK`
- General Training — `1b0WsiXvMY-DX13_fmR8Uo3-4a-nw7_TZ`
- FCC Training — `1lADX2ZFp5ttUNhGuUPNqrdBxJqLWMaGu`
- Examination — `1i8axEM_OKD5_2xR_EoW39ayoOOD3QUeD`
- Training Record — `1vxdoF4eu4CdSlt1eSU5zOBm3xO2TlGMA`
- SOC Weekly Training — `1kHtWqRey7YSy1uHiKSBs6w_ws2hhSARZ`

## CCTV Document and Tracking structure confirmed

- Tracking — `1Mln20htf0XISOLPMGGO1fbsT_1OnaF7I`
- CCTV Request Form — `1WbC8rU6cin5Q3oqZyTcYqqkTcdcScbQw`
- Forms — `1NL2pZCj_kLgXWOe9hFZRxJykFuVS00SN`
- CCTV Record — `1ngvLaI2aW6UytSqfOAMc1REkf6HkEBj3`

## SOC Management workstreams

| Workstream | Drive ID | Import status |
|---|---|---|
| 01. Task | `1Zt8OxOtrZsuLacSKX7wFDDBSyCmr7ZZI` | Indexed / extraction pending |
| 02. Work Schedule | `1SXA-3Lkt4OsLr3THUv51-2FdJH9MCM5D` | Indexed / extraction pending |
| 03. Report | `1uSW8b_hz9IabDlOXtlzfGs83u-uRwBmV` | Indexed / extraction pending |
| 04. Project | `1kea9afyHK_XVkYrCmBqLGmTa5PNYV_0R` | Indexed / extraction pending |
| 05. Procurement | `1dnyQIHUJv2pEuJ6b2lg3pTJSn0y3NwwW` | Indexed / extraction pending |
| 06. Document Control | `1nrB9YJv3-C6R_Q8dOXbsPlA52lbXxS1W` | Indexed / extraction pending |
| Performance Evaluation - SOC | `1DZE1uJF7n-Lj-6x8Qg_vg7osBCsJdBnh` | Indexed / extraction pending |

## Additional management/project sources confirmed

Current source discovery also identified operational/project categories including CCTV, Incident Command Station, Mozart, Virtual Patrol, Guard Tour, SOC Task, Security Manning Post Check, SOC KPI, Seating Plan, Video Analytics and ISO. These remain import workstreams and must be normalized into reusable KB items or metadata-only references based on sensitivity.

## Sensitive-source handling

The following remain in Drive as raw source and are not copied verbatim into the public repository:

- Blacklist/Whitelist identities and biometric/identity data
- staff PII and personal phone/contact details
- individual vehicle registration details
- CCTV evidence/images and sensitive investigation records
- credentials, passwords, tokens and access secrets
- sensitive security layouts/configuration details

Repository records only sanitized operational rules, source metadata, non-sensitive summaries and source pointers.

## Completion rule

This register is complete only when every listed workstream is either:

1. converted into an active Knowledge Item with cross-reference to source; or
2. explicitly marked metadata/reference-only because the raw content is sensitive, evidentiary, historical or unsuitable for repository storage; and
3. no `Pending Import`, `In Progress`, `Pending Validation`, unresolved revision conflict or uncategorized source remains in the Import Control Register.

---
kb_id: REG-SRC-001
title: "ทะเบียนแหล่งข้อมูล _SENSES SOC (_SENSES SOC Source Register)"
description: "ทะเบียนกลางของ Source Domain, Folder และไฟล์สำคัญใน Shared Drive _SENSES SOC สำหรับ Cross-reference และควบคุมการนำเข้าสู่ KB"
owner: "SOC"
last_updated: 2026-08-29
status: active
domain: register
knowledge_type: index
source_authority: boss_confirmed
sensitivity: internal
---

# ทะเบียนแหล่งข้อมูล _SENSES SOC (_SENSES SOC Source Register)

| รายการ | ข้อมูล |
|---|---|
| Shared Drive | `_SENSES SOC` |
| Drive ID | `0AJpAwl9n5sLbUk9PVA` |
| Owner | SOC |
| Last Updated | 29 สิงหาคม 2026 |
| Import Authorization | `DEC-20260829-001` |

## Classification

- `KNOWLEDGE` — สามารถสกัดเป็น Canonical Knowledge ใน KB ได้เมื่อ Source Status รองรับ
- `REFERENCE` — เก็บ Metadata/Reference และกลับไปอ่าน Source เมื่อต้องใช้รายละเอียด
- `RESTRICTED_REFERENCE` — ห้ามทำซ้ำ Raw Content ใน Public Repository; เก็บเฉพาะ Metadata/Sanitized Knowledge
- `HISTORICAL` — ใช้เพื่อประวัติ/แนวโน้ม ไม่ใช้เป็น Current Rule
- `DRAFT_SOURCE` — รอ Validation; ห้ามใช้เป็น Approved Rule

## A. SOC Management

| Domain / Source | Drive ID | Class | KB Target / Note |
|---|---|---|---|
| SOC Management | `1bbs9_mzwZkNiqW6QYGlDJNA_Tw08vviY` | KNOWLEDGE | Management Source Root |
| 01. Task | `1Zt8OxOtrZsuLacSKX7wFDDBSyCmr7ZZI` | KNOWLEDGE | Task Management Framework |
| Task Management ล่าสุด | `1hKbSJKD2LKq4y9Q1X55aLAG3JED2FbN4Q8CgCfQ1gtc` | KNOWLEDGE | Current Task Master |
| 02. Work Schedule | `1SXA-3Lkt4OsLr3THUv51-2FdJH9MCM5D` | RESTRICTED_REFERENCE | Workforce schedule; summarize staffing model only |
| OBK SOC Operator Work Schedule 2026 | `1M6t67Sf2lh7sNhe29zqd87SbVRNZBCBIpZbcogO_pHI` | RESTRICTED_REFERENCE | Individual roster source |
| OBK SOC-Management Work Schedule 2026 | `1UVPEMbCR9HiAnSJwpY9JJMYfV0UuLQavOMwvf6AB8es` | RESTRICTED_REFERENCE | Individual roster source |
| 03. Report | `1uSW8b_hz9IabDlOXtlzfGs83u-uRwBmV` | REFERENCE | Current folder empty at scan date |
| 04. Project | `1kea9afyHK_XVkYrCmBqLGmTa5PNYV_0R` | KNOWLEDGE | Project/Enhancement Portfolio |
| 05. Procurement | `1dnyQIHUJv2pEuJ6b2lg3pTJSn0y3NwwW` | REFERENCE | Current folder empty at scan date |
| 06. Document Control | `1nrB9YJv3-C6R_Q8dOXbsPlA52lbXxS1W` | REFERENCE | Current folder empty at scan date |
| Performance Evaluation - SOC | `1DZE1uJF7n-Lj-6x8Qg_vg7osBCsJdBnh` | KNOWLEDGE / RESTRICTED_REFERENCE | Framework can enter KB; individual results remain restricted |

### Management Project Domains

| Domain | Drive ID | Class |
|---|---|---|
| 01. CCTV | `13pOQc8JZ_UVlOmGErKK1tqKpXPGnuHH2` | KNOWLEDGE / RESTRICTED_REFERENCE |
| 02. Incident Command Station (May 2025) | `1l94U-hlCcYthyBWs-up9Vpn7lBxNxnDy` | HISTORICAL / KNOWLEDGE |
| 03. Mozart | `1P5Vkhvk5DYggUWwiLQGgHdZqz0T9TmsH` | KNOWLEDGE |
| 04. Virtual Patrol | `1w6XkkD8LtuUlh8Np8S9zqKJXex6wcK8W` | KNOWLEDGE |
| 05. Guard Tour | `1IntMedKrPwcA4GvgdDl5Q8dlWcmbgkQF` | KNOWLEDGE |
| 06. SOC Task | `1T6oxouUGRFVnlCVdfM8ve8XBuyo0wgs-` | KNOWLEDGE |
| 07. Security Manning Post Check | `1E_05o8-OZUPyPp0L6sg3ZqEIv6NoDtyK` | RESTRICTED_REFERENCE |
| 08. SOC KPI | `1qNQU9sGiS6Xpm0y-vNQP0SaFKDit0E_x` | KNOWLEDGE / RESTRICTED_REFERENCE |
| 09. Seating Plan | `1tdEZPad14oqs2GUXFB0GBBwLRDuulXrS` | RESTRICTED_REFERENCE |
| 10. Video Analytics | `1Nr_bJfSCsgt37mG_xXHMPkz6PjV8B2hP` | KNOWLEDGE |
| 11. ISO | `1MR95B4Fc2FP3vv7g0_yEhpN84khKfhgi` | KNOWLEDGE |
| MRT Countdown.zip | `1EIpnj8t19dusqnne14Nrtb6aUMSfhWeN` | REFERENCE | Large raw archive; index only |

### Mozart Current Source Set

| Source | Drive ID | Class | Note |
|---|---|---|---|
| 20260813_Mozart_Task_Template_Master_Data.xlsx | `1aHfBY_02tbCcO_B97ypWiwZSpJilt2QI` | KNOWLEDGE | Most recently modified master found in current project folder |
| 20260813_Mozart_Task_Template_Master_Data(1).xlsx | `1yeJHBCy3SHhL9ADO3ZrHU6eCePI0fSyv` | HISTORICAL | Older copy |
| 20260812_Mozart_Task_Template_Master_Data.xlsx | `10pmmKr3QkR-PME45sI0Otxmg7NXPicpO` | HISTORICAL | Previous dated version |
| Mozart Task Template - Master Data (1).xlsx | `1t6TB1V7OJteMpu0QVYMkxuaejTd0_OxV` | HISTORICAL | Earlier master |
| Implementation of Event Type Task Template - OBK (1).docx | `16Nnq0z7NxiwHrT04b6PbwdQo2Ey-PkJE` | KNOWLEDGE | Implementation reference |
| Security Event type - Description.xlsx | `1A4etJ6zOMIsI2nNd8AbGXx1_k-ks1fB-` | KNOWLEDGE | Event Type description reference |
| Mozart Down | `17avGwSgoEROmFyBVyfY7IPlVcW2JMJBU` | KNOWLEDGE | BCP/support domain |

## B. SOC Team

| Domain / Source | Drive ID | Class | KB Target / Note |
|---|---|---|---|
| SOC Team | `1tTrpjlEBhNjD0KeGbPYjKk6QJ2mtg40f` | KNOWLEDGE | SOC Team Source Root |
| 01. SOC Documents | `13nYhcjxzVUXFGCrKSl3g39fMDxcG2Pr2` | KNOWLEDGE | Operational Documents Library |
| 02. Standard Operation Procedure (SOP) | `1EJtxbkFTKHNyN5QMNmRmf41cmKSvOult` | KNOWLEDGE | SOP/WI/Swimlane Source Root |
| 03. Training | `1Kgt089IJTJQbCS3WoHqb9rixfm7WYWdy` | KNOWLEDGE | Training & Assessment Library |
| 04. CCTV Document and Tracking | `1XOEyaDfxEgfkfyRDwdrsb1vYdiu17FT_` | KNOWLEDGE / RESTRICTED_REFERENCE | CCTV operations/evidence references |
| 05. Operator Task | `1FbaBUGC0hXKmZNVhEPisIym9A4sXqbmu` | KNOWLEDGE | Zone/CI operational tasks |
| 06. Activity Picture | `18oyFGXdkJIEiWJbZGQnLJnRMl7e_pXlW` | RESTRICTED_REFERENCE / HISTORICAL | Images stay in Drive |
| ตรวจสอบ CCTV ประจำ Week ของ Operation.xlsx | `18lPSelsBMq6XdSeEsxM-VrGt85KBocVm` | RESTRICTED_REFERENCE | Large operational CCTV file |

### SOC Documents Domains

| Domain | Drive ID | Class |
|---|---|---|
| 01. SOC Staff Information | `1OcU3Ryv5nH1WMkx13-4ShUGaIRLs3lDg` | RESTRICTED_REFERENCE |
| 02. Announcement | `1LlNQI32YW_VzypFpu3gKaCgdxuP2WoFi` | KNOWLEDGE |
| 03. Mozart | `1cd0pUA3XxEi-eNoDwkV6OQiWnTjUxlsJ` | KNOWLEDGE |
| 04. Guard Tour | `1qTcJQjx5XsJYNTLWEy0m0QNLyMJ0ZloU` | KNOWLEDGE |
| 05. Virtual Patrol | `1QXuxn3Iwpk0cD1zb-T6Fy3Alcn3swg_k` | KNOWLEDGE |
| 06. Blacklist - Whitelist - Watchlist | `1nZIYqFwcTHaRwVKxdnlEX4Dn4IFFeYvm` | RESTRICTED_REFERENCE |
| 07. Video Analytic | `1VxaF67v2KSy3ccA0Grrl0DWzh0zbwO5n` | KNOWLEDGE |
| 08. OBK Layout | `1sPkcrIvv_pqDo-htsHswEXEgBN8c1Exd` | RESTRICTED_REFERENCE | Empty at scan date |
| 09. CCTV | `1ui0zVrvLkDE3D8nCzNJjQSzmcQqmt1gW` | RESTRICTED_REFERENCE / KNOWLEDGE |
| 10. Event | `1aVLhAmeQU9_vlovB-wTBDicFfdZCxV-v` | KNOWLEDGE / HISTORICAL |
| 11. Work Schedule | `1d9t5RcDbL4ysE7dfAiRI_g-H4XVEB-UW` | RESTRICTED_REFERENCE |
| 12. Other | `1hetxLAjzoHMOKphbhlVERlU9R7RVCwER` | MIXED; classify per source |

### Key Operational Sources

- Announcement: `OB-SOC-AN-0001 กฎระเบียบการทำงานใน SOC` — `1G_qYfw8_omAqK92nnqe0rSQUqvMcouWv`
- Announcement: `OB-SOC-AN-0002 หลักปฏิบัติการทำงานร่วมกัน` — `1Glm2-IZYqNdsDAbcwkNNQM7G3IHl3-jK`
- Case Manual Log Template — `19FjOybLEm3UXIVGcZzukn5ypXdRSETy0`
- Blacklist/Whitelist Master — `1dj1CxYFUw8u86yfnMYnMv4XTAZBCnz-v` — RESTRICTED_REFERENCE
- People Counting Report — `1uhOsb3K5I_UNoRS5EsDGv8Bh9QbwwqO9`
- Active CCTV Issue Record — `1NV7_iNxv-3quXH1Q4wk8euIlfEJKxZUh` — RESTRICTED_REFERENCE
- SOC Staff List — `1_HbI5o2BUuwGkdU0-9Iu76c2xlwEXn7C` — RESTRICTED_REFERENCE
- SOC Car Plate files — `1KEQveWiN9fGWtFo9NTUsVVs5IXwyPGkj`, `1eSdCKXhxu0sHg4ESi751htPI__4hSnsL` — RESTRICTED_REFERENCE

## C. SOP Revision Control

| Branch | Drive ID | State |
|---|---|---|
| SOP Document | `1ZYw3zBRyovp25irgsS_fMbhELyARr0B4` | Controlled Source Root |
| 00. Draft | `1Rx23hFRT_vLjqxEAL3OWNhhvlGfGTSEI` | DRAFT_SOURCE |
| 01. Rev.00 | `1K-WTdw1oQwEkg2_kR38QHaaTlat5meGT` | Approved/Previous depending document |
| 02. Rev.01 | `1elN42bUpy7IWvgAFmJ4nGvZhjL91YoAF` | Current where matching document exists |

Current Rev.01 sources found:

- Active Shooter EP Rev.01 Signed — `1KWGPPfLFextelO2pw7fjECH-V66lXA2T`
- BCP Mozart Down Rev.01 Signed — `1Sm0kSOMHaOCwL6_Cu0hhs1o3gZS_w04W`

Known control conflict:

- `OB_SOP_LW_0001 การรายงานอุบัติการณ์และการสอบสวนอุบัติเหตุ rev.01.pdf` is stored under the `Rev.00` branch; classify as **Pending Validation** until Document Control confirms its authoritative revision location.

## D. Training Structure

| Domain | Drive ID | Class |
|---|---|---|
| 01. OJT Training | `1l5gcvA4ZvyHpBMFVQGG8I36Rgsfm_rrK` | KNOWLEDGE |
| 02. General Training | `1b0WsiXvMY-DX13_fmR8Uo3-4a-nw7_TZ` | KNOWLEDGE |
| 03. FCC Training | `1lADX2ZFp5ttUNhGuUPNqrdBxJqLWMaGu` | KNOWLEDGE |
| 04. Examination | `1i8axEM_OKD5_2xR_EoW39ayoOOD3QUeD` | KNOWLEDGE / RESTRICTED_REFERENCE |
| 05. Training Record | `1vxdoF4eu4CdSlt1eSU5zOBm3xO2TlGMA` | RESTRICTED_REFERENCE |
| 06. SOC Weekly Training | `1kHtWqRey7YSy1uHiKSBs6w_ws2hhSARZ` | KNOWLEDGE |

## E. CCTV Document and Tracking

| Domain | Drive ID | Class |
|---|---|---|
| 01. Tracking | `1Mln20htf0XISOLPMGGO1fbsT_1OnaF7I` | KNOWLEDGE / RESTRICTED_REFERENCE |
| 02. CCTV Request Form | `1WbC8rU6cin5Q3oqZyTcYqqkTcdcScbQw` | KNOWLEDGE |
| 03. Form | `1NL2pZCj_kLgXWOe9hFZRxJykFuVS00SN` | KNOWLEDGE |
| 04. CCTV Record | `1ngvLaI2aW6UytSqfOAMc1REkf6HkEBj3` | RESTRICTED_REFERENCE |

## F. Operator Task

| Domain | Drive ID | Class |
|---|---|---|
| 01. CI Traffic | `1qJhLWlxV1FL8pUz30kVUnsOYBrrp3Vbw` | KNOWLEDGE |
| 03. Zone 1 | `1CnTSC0q_-ztNPhut1RimuAEpfQFXI7S9` | KNOWLEDGE |
| 04. Zone 2 | `10vP2LiHVrpkO-lyy8XkYmbknpu0JrzOB` | KNOWLEDGE |
| 07. Compound | `16GnHFozewJDE1BZ69fzzKLfE4foPfdeL` | KNOWLEDGE |
| Summary.xlsx | `1H7HX2CGhta5M23a3CR-5EwoCMxM78XFK` | KNOWLEDGE |
| CCTV Offline Checklist.xlsx | `1m0WkQUwV2I6ibJdboyXWyFfLUOKI1O5e` | KNOWLEDGE |

## G. Activity / Historical Evidence

- 2025 Activity Picture — `1rNoTwZ7o9dzSWTEXpylRb65BSKQEnYMF`
- 2026 Activity Picture — `1VwtQyPfq0VqDUCL5diXuURaNbLH5cXIR`

ภาพและ Evidence ไม่ถูกทำสำเนาเข้า Public Repository; ใช้ Drive เป็น Source of Truth และเก็บเฉพาะ Event/Activity Knowledge ที่เหมาะสม

## Import Progress Rule

ทะเบียนนี้เป็น Living Register และต้องขยายลงระดับ Child Folder/File เมื่อมีการ Crawl เพิ่ม โดยรักษา Drive ID เพื่อ Cross-reference เสมอ หากมี Source ซ้ำ ให้ Canonical Current Shared Drive source มีลำดับเหนือ Legacy Copy เว้นแต่ Document Control ระบุเป็นอย่างอื่น

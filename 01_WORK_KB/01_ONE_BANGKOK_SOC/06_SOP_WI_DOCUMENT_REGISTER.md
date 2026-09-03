---
kb_id: WK-OBK-SOP-001
title: "ทะเบียนเอกสาร SOP/WI ของ One Bangkok SOC (SOP/WI Document Register)"
description: "ทะเบียนเอกสาร SOP, WI, Forms และ Records ที่ตรวจพบจาก Shared Drive _SENSES SOC พร้อม Revision, Source Folder และสถานะการตรวจสอบ เพื่อใช้เป็นฐานสำหรับการนำเนื้อหาเข้าสู่ Master Knowledge Base"
owner: "SOC"
last_updated: 2026-09-03
status: active
domain: one_bangkok_soc
knowledge_type: index
source_authority: current_operational_practice
sensitivity: internal
---

# ทะเบียนเอกสาร SOP/WI ของ One Bangkok SOC (SOP/WI Document Register)

| รายการ | ข้อมูล |
|---|---|
| คำอธิบาย (Description) | ทะเบียนเอกสาร SOP/WI/Forms/Records ที่พบใน `_SENSES SOC` เพื่อควบคุม Revision และใช้เป็น Source Index สำหรับ KB |
| เจ้าของข้อมูล (Owner) | SOC |
| อัปเดตล่าสุด (Last Updated) | 3 กันยายน 2026 |
| สถานะ (Status) | ใช้งานจริง (Active) |

## กติกาการตีความสถานะเอกสาร

- `CURRENT_REV_CANDIDATE` = อยู่ในโฟลเดอร์ Revision ล่าสุดที่ตรวจพบ และชื่อไฟล์ระบุ Signed/Revision ชัดเจน แต่ยังต้องยืนยันกับ Document Control ก่อนใช้เป็นข้อกำหนดบังคับถ้ามีข้อสงสัย
- `SOURCE_PRESENT` = พบเอกสารใน Source Drive แต่ชื่อไฟล์/ตำแหน่งยังไม่พอให้ AI ยืนยันว่าเป็น Approved Current Revision
- `SUPERSEDED_SOURCE` = มี Revision ที่สูงกว่าของ Document Code เดียวกันใน Source Drive
- `DRAFT` = อยู่ใน Draft area หรือชื่อไฟล์ระบุ Draft; ห้ามใช้เป็น Approved Operational Rule
- Document Code, ชื่อไฟล์ และรูปแบบเครื่องหมาย `_` / `-` ต้องเก็บตาม Source เพื่อรองรับการ Cross-reference

## A. Current Revision Folder — Rev.01

| Document Code | Document Title / Source File | Revision | Source State | Drive File ID |
|---|---|---:|---|---|
| OB-SOP-EP-0036 | แผนการปฏิบัติการฉุกเฉินกรณีเหตุกราดยิง — `OB_SOP_EP_0036 แผนการปฏิบัติการฉุกเฉินกรณีเหตุกราดยิง Rev.01 (Signed).pdf` | Rev.01 | CURRENT_REV_CANDIDATE | `1Z78uFmVDPvmNhPUek2J7A-xSci8lVwDq` |
| OB-SOP-DCC-0002 | BCP - Mozart Down — `OB-SOP-DCC-0002 - BCP - Mozart Down - RV.01 - signed.pdf` | Rev.01 | CURRENT_REV_CANDIDATE | `10cXqWWPFzkvRaTUo7qNKxaNkkVA-41aO` |

## B. Rev.00 — Emergency Plan (EP)

| Document Code | Document Title / Source File | Revision | Source State | Drive File ID |
|---|---|---:|---|---|
| OB-SOP-EP-0004 | แผนบริหารจัดการเหตุแผ่นดินไหว — `OB_SOP_EP_0004 แผนบริหารจัดการเหตุแผ่นดินไหว Rev.00.pdf` | Rev.00 | SOURCE_PRESENT | `1b9jo7mKe3q2t_Yqss4rUixfRjqgevsFL` |
| OB-SOP-EP-0005 | แผนบริหารจัดการอุทกภัย — `OB_SOP_EP_0005 แผนบริหารจัดการอุทกภัย Rev.00.pdf` | Rev.00 | SOURCE_PRESENT | `18gWelYjMEOXeOrUuyLEaJ_9TIRspoU5Q` |
| OB-SOP-EP-0007 | แผนบริหารจัดการผู้ป่วยฉุกเฉิน — `OB_SOP_EP_0007 แผนบริหารจัดการผู้ป่วยฉุกเฉิน Rev.00.pdf` | Rev.00 | SOURCE_PRESENT | `1Yz6BJy2rasDcPWo783iWKGs0gOTvEYzT` |
| OB-SOP-EP-0020 | แผนบริหารจัดการเหตุการณ์สารเคมีรั่วไหล — `OB_SOP_EP_0020_แผนบริหารจัดการเหตุการณ์สารเคมีรั่วไหล Rev.00.pdf` | Rev.00 | SOURCE_PRESENT | `1zCpuLArMAGDhxx-cF5WKxZFKSqyQiKKu` |
| OB-SOP-EP-0046 | แผนบริหารจัดการความผิดเกี่ยวกับทรัพย์ — `OB_SOP_EP_0046 แผนบริหารจัดการความผิดเกี่ยวกับทรัพย์ Rev.00 Signed.pdf` | Rev.00 | SOURCE_PRESENT | `1yTlpyWAoLieSAgeZD2jeUm-_wqR7jNPe` |
| OB-SOP-EP-0009 | Protester Management Procedure — `OB-SOP-EP-0009 แผนบริหารเหตุการณ์จัดการผู้ชุมนุม Protester Management Procedure Rev.00 (Signed).pdf` | Rev.00 | SOURCE_PRESENT | `18hdWRPvKnMVN9O56d-LcNZQ50OvqVm2T` |
| OB-SOP-EP-0010 | แผนบริหารจัดการเหตุการณ์อาชญากรรม — `OB-SOP-EP-0010 แผนบริหารจัดการเหตุการณ์อาชญากรรม (Signed).pdf` | Rev.00/Unclear | SOURCE_PRESENT | `1cSUsaVG4BXLiPK8CDPs0O1c_5nHT531q` |
| OB-SOP-EP-0036 | แผนการปฏิบัติการฉุกเฉินกรณีเหตุกราดยิง — `OB-SOP-EP-0036 แผนการปฏิบัติการฉุกเฉินกรณีเหตุกราดยิง Signed.pdf` | Rev.00/Previous | SUPERSEDED_SOURCE | `1mMlAdqQcUDIZwYBbGZ99vMdb0gV4kCG-` |
| OB-SOP-EP-0039 | แผนบริหารกรณีพบผู้เสียชีวิตในพื้นที่โครงการ — `OB-SOP-EP-0039 แผนบริหารกรณีพบผู้เสียชีวิตในพื้นที่โครงการ (Signed).pdf` | Rev.00/Unclear | SOURCE_PRESENT | `10fAbdhXbBPYSRRLQJ2YdhGZPQfSzoS32` |

## C. Rev.00 — SSHE

| Document Code | Document Title / Source File | Revision | Source State | Drive File ID |
|---|---|---:|---|---|
| OB-SOP-SSHE-0001 | การขออนุญาตดู-บันทึกข้อมูลกล้องวงจรปิด — `OB-SOP-SSHE-0001 การขออนุญาตดู-บันทึก ข้อมูลกล้องวงจรปิด.pdf` | Rev.00/Unclear | SOURCE_PRESENT | `1q7ArD_g2AiT7dyBnViFYZcVib1usnKKS` |
| OB-SOP-SSHE-0003 | กระบวนการจัดการทรัพย์สินสูญหายและขอรับทรัพย์สินคืนเมื่อพบทรัพย์สิน — `OB-SOP-SSHE-0003 ... (Signed).pdf` | Rev.00/Unclear | SOURCE_PRESENT | `12hBD2fwok2SlTPyC_9qcKT4MVCLb-Xjd` |
| OB-SOP-SSHE-0011 | การจัดการระบบโทรทัศน์วงจรปิด — `OB-SOP-SSHE-0011 การจัดการระบบโทรทัศน์วงจรปิด(Signed).pdf` | Rev.00/Unclear | SOURCE_PRESENT | `11mzrfCyoLOF3fDPozg6Z6GfLGzoSZPr0` |
| OB-SOP-SSHE-0020 | การใช้งานเครื่องเติมอากาศ SCBA — `OB-SOP-SSHE-0020 การใช้งานเครื่องเติมอากาศ SCBA.pdf` | Rev.00/Unclear | SOURCE_PRESENT | `1bE0ttx_ty8si1rNV17Ur5qAcEH_IhHHD` |
| OB-SOP-SSHE-0029 | การดำเนินการกรณีแจ้งเตือนยานพาหนะบัญชีดำ (LPR Blacklist) | Rev.00/Unclear | SOURCE_PRESENT | `11JBDGdYgh3tVZfMnfHn6b9G6gskdY8dO` |
| OB-SOP-SSHE-0030 | การดำเนินการกรณีแจ้งเตือนบุคคลบัญชีดำ — `OB-SOP-SSHE-0030_การดำเนินการกรณีแจ้งเตือนบุคคลบัญชีดำ Signed.pdf` | Rev.00/Unclear | SOURCE_PRESENT | `13MHT9-4aBpypSNl31LIbNyYpVTWt_UbE` |

## D. Rev.00 — Administration (AD)

| Document Code | Document Title / Source File | Revision | Source State | Drive File ID |
|---|---|---:|---|---|
| OB-SOP-AD-0001 | Document Management — `OB-SOP-AD-0001_Document Management_Rev.00.pdf` | Rev.00 | SOURCE_PRESENT | `1c0ja1bSUNFb_KapNN8AAZkjqg1mRP5XL` |

## E. Rev.00 — Legal Work (LW)

| Document Code | Document Title / Source File | Revision | Source State | Drive File ID |
|---|---|---:|---|---|
| OB-SOP-LW-0001 | การรายงานอุบัติการณ์และการสอบสวนอุบัติเหตุ — `OB_SOP_LW_0001การรายงานอุบัติการณ์และการสอบสวนอุบัติเหตุ rev.01.pdf` | File says Rev.01 | SOURCE_PRESENT — REVISION/FOLDER CONFLICT | `1bk-rPAcdgcRg4jMmfcTuJj5QflpjRU6t` |
| OB-SOP-LW-0002 | การทดสอบความพร้อมใช้งานสายดับเพลิงผ้าใบ | Rev.00/Unclear | SOURCE_PRESENT | `1-MbEYG7phj9kCmXB2JoQ-kT60afXJQ-L` |
| OB-SOP-LW-0003 | การทดสอบตามที่กฎหมายกำหนด — `OB_SOP_LW_0003การทดสอบตามที่กฎหมายกำหนด Rev.00.pdf` | Rev.00 | SOURCE_PRESENT | `1Xa0X9s_x6tVni_ite4nxao3QNAR9CCNu` |
| OB-SOP-LW-0005 | การปฏิบัติตามกฎหมายและมาตรฐานอื่นๆ (Compliance of Legal and Other Requirement) | Rev.00 | SOURCE_PRESENT | `1Rh2ycLQXXE7P3tZEAnW3UzSbjZ8YvQ9Z` |

## F. Rev.00 — Forms and Records (FR)

| Document Code | Document Title / Source File | Revision | Source State | Drive File ID |
|---|---|---:|---|---|
| OB-FR-LW-0501 | ทะเบียนกฎหมายและมาตรฐานอื่นๆ (Legal and Other Standards Register) | Unclear | SOURCE_PRESENT | `1wdilblwijiCrMcHgkIQCIgPOOBYHLwPZ` |
| OB-FR-LW-0502 | เอกสารรายงานประเมินความสอดคล้องกฎหมาย | Unclear | SOURCE_PRESENT | `1__BkLd0NV1aEWfBVBOkH6_CPgo2I34wc` |
| OB-FR-LW-0503 | แบบฟอร์มแผนปฏิบัติการ (Action Plan Form) | Rev.00 | SOURCE_PRESENT | `1nXcuDgempbz0_yhFvGn-wJv3Z2n5OPhQ` |
| OB-FR-LW-0504 | Training Record Form | Rev.00 | SOURCE_PRESENT | `1YEmcmPQV8e42cs070fnZLCoxDmRxisD4` |
| OB-FR-LW-0505 | รายงานการประชุม (Minutes of Meeting Form) | Rev.00 | SOURCE_PRESENT | `1lsqyqTyGVR0-uhhkOtcTVOYfmmTtnLC7` |
| OB-SOP-FR-DCC-0201 | Case Manual Log Template | Unclear | SOURCE_PRESENT | `1qO5pAE-6YQyiaB4UHZ1-pE1ts39h4Vya` |
| OB-SOP-FR-SSHE-0101 | แบบฟอร์มขออนุญาตดูหรือคัดลอกภาพจาก CCTV | Unclear | SOURCE_PRESENT | `174hG7W4Ar98VyWqlVOHwqQDMwQcf2Bqt` |
| OB-SOP-FR-SSHE-0301 | Form Lost and Found | Unclear | SOURCE_PRESENT | `1szUGwYoKh0JIJxWiHNB_aTimWhcOJb1n` |
| OB-SOP-FR-SSHE-2001 | บันทึกการใช้งานเครื่องเติมอากาศ 300 BAR | Rev.00 | SOURCE_PRESENT | `1tyK4CnugWL8tVQMEsSBxbeU2J7sL_bzc` |

## G. Draft Area — Workstreams / Files Detected

### Draft workstream folders

- `Active Shooter`
- `Crowd Control`
- `Suicide`
- `Blacklist`
- `CCTV`
- `Death in Property`
- `Theft`
- `Lost & Found`

### Direct draft files detected

| Source File | State | Drive File ID |
|---|---|---|
| `OB_OW_WI_EP_0011แผนบริหารจัดการเหตุการณ์จับตัวประก1.docx` | DRAFT | `1iNUNy7xhU2nsZ-ObxPHgIDT2_z6QgZRd` |
| `OB_SOP_EP_0004แผนบริหารจัดการเหตุแผ่นดินไหว.pdf` | DRAFT / DUPLICATE CANDIDATE | `16lvOqzyZFIWhWbDMDaQ6APCBkUigTnuX` |
| `OB_SOP_EP_0012การดำเนินการเมื่อพบวัตถุต้องสงสัย.docx` | DRAFT | `18fqDvSiYthB0c49uMfA9G5unAkktRd36` |
| `OB_SOP_EP_0014แผนบริหารเหตุการณ์ถูกขู่ก่อการร้าย.docx` | DRAFT | `1_2KcoDIurCKIWdYxMzoM7xskL8FJ2GsI` |
| `OB-SOP-EP-0041 แผนการบริหารจัดการกรณีอาหารเป็นพิษ Mass Food Poisoning.docx` | DRAFT | `1MvT1Clx3DfJecX8cExj2fHlz_9fBQzop` |
| `OB-SOP-SSHE-0001 การขออนุญาตดู-บันทึก ข้อมูลกล้องวงจรปิด Draft 2.docx` | DRAFT | `1UgKrRcLNyewgL2iNpLpmZBbJPgHh30gW` |
| `OB-SOP-SSHE-0011 การจัดการระบบโทรทัศน์วงจรปิด - CCTV System Management.docx` | DRAFT | `1eaByf_bPAz4gXthUvohddgMVoY36K5ym` |

## Validation / Control Findings

1. `OB-SOP-EP-0036` พบทั้ง Source เก่าและ `Rev.01 (Signed)` ดังนั้น Source เก่าต้องถือเป็น `SUPERSEDED_SOURCE` สำหรับการอ้างอิง KB
2. `OB-SOP-LW-0001` ชื่อไฟล์ระบุ `rev.01` แต่ไฟล์อยู่ใต้โฟลเดอร์ `Rev.00`; ต้องยืนยัน Document Control ก่อนกำหนด Current Revision
3. เอกสารหลายฉบับอยู่ใน `Rev.00` แต่ชื่อไฟล์ไม่ระบุ `Signed`; AI ห้ามอนุมาน Approval Status จากตำแหน่งโฟลเดอร์เพียงอย่างเดียว
4. Draft area มีทั้ง SOP/WI ที่อาจเป็นการพัฒนาฉบับใหม่และไฟล์ซ้ำกับ Approved/Rev.00 source; ต้องเปรียบเทียบ Document Code และ Revision ก่อนนำเข้าเนื้อหา
5. รูปแบบ Document Code ในชื่อไฟล์มีทั้ง `_` และ `-`; Canonical Code ใน KB ควร normalize เพื่อค้นหา แต่ต้องเก็บ Source Filename เดิมไว้เพื่อ Traceability

## Import Progress

- [x] Source folder map captured
- [x] Current Rev.01 source list captured
- [x] Rev.00 EP / SSHE / AD / LW / FR source list captured
- [x] Draft workstream list captured
- [ ] Extract document metadata from inside each PDF/DOCX (effective date, approver, scope, owner)
- [ ] Build SOP-to-Swimlane cross-reference
- [ ] Build SOP-to-Mozart Event Type/Task Template cross-reference
- [ ] Build SOP-to-Training/Assessment cross-reference
- [ ] Validate Current Revision with Document Control source

## Source Locations

- Shared Drive: `_SENSES SOC`
- `SOC One Bangkok / 02. Standard Operation Procedure (SOP) / 03. SOP Document`
- Revision folders: `00. Draft`, `01. Rev.00`, `02. Rev.01`
- Source map: `WK-OBK-SRC-001`

## Authorized One Bangkok Controlled Document Library — 3 Sep 2026

Boss additionally authorized Google Drive root `1HQPhxkEpWY3Y0lNHoXD5k51ewugQ_bpa` as a controlled source. The source-level inventory is registered as `WK-OBK-LIB-001` in `10_ONE_BANGKOK_DOCUMENT_LIBRARY_INVENTORY.md`.

The six controlled Document Management Logs (Policy, MAN, SOP, WI, SP, EXT) expose **1,041 code records/slots** in total; the SOP log contains **281 SOP code records/slots**, including **209 populated titles**. Blank/reserved rows are retained in the Drive logs and are not interpreted as approved documents. Before using any procedure as an operational rule, verify its actual Drive source file, revision and source status.

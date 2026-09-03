---
kb_id: WK-OBK-LIB-001
title: "One Bangkok Document Library Inventory"
description: "Controlled inventory of the One Bangkok document library from the authorized Google Drive root, including Policy, Manual, SOP, WI, Supporting Documents, External Documents, Safety Awareness, ERP and Incident Report sources. Google Drive remains the Raw Source / Source of Truth."
owner: "SOC"
last_updated: 2026-09-03
status: active
domain: one_bangkok_soc
knowledge_type: source_inventory
source_authority: boss_authorized_google_drive
sensitivity: internal
---

# One Bangkok Document Library Inventory

## Source of Truth

Authorized Google Drive root: `1HQPhxkEpWY3Y0lNHoXD5k51ewugQ_bpa`

Drive URL: https://drive.google.com/drive/folders/1HQPhxkEpWY3Y0lNHoXD5k51ewugQ_bpa

**Control rule:** Google Drive is the Raw Source / Source of Truth. GitHub Inventory stores metadata, controlled cross-references and sanitized knowledge extracts only. Restricted raw data must remain in Drive.

## Root Library Structure

| No. | Source Domain | Drive Folder ID | Inventory Treatment |
|---|---|---|---|
| 01 | นโยบาย (Policy) | `1b0ADo9W2X7pSsFBidyZw0mZLhaYvs__I` | Indexed from Policy Document Management Log + source files |
| 02 | คู่มือ (Manual) | `1uxoWEvMK6sTSC7Ccw0gVKikNElzkvkWN` | Indexed from MAN Document Management Log + source files |
| 03 | มาตรฐานการปฏิบัติงาน (SOP) | `19h18S3edd0Q1HoJSVFGREb9nBYsveizN` | Indexed from SOP Document Management Log + domain folders |
| 04 | ขั้นตอนการปฏิบัติงาน (WI) | `10fgcp2lKcwX1kKBWH-tSlJsbqx0a4vcf` | Indexed from WI Document Management Log + domain folders |
| 06 | เอกสารสนับสนุน (Supporting Documents) | `1jh2iwJJMtijPN8liEs70ZgvPKCdd-ZFx` | Indexed from SP Document Management Log + domain folders |
| 07 | เอกสารภายนอก (External Documents) | `1ofl4pLGyKmtx-_FIV1NKTP1l2N8SBxek` | Indexed from EXT Document Management Log |
| 08 | Sustainable of Safety Awareness | `1dMBAR2Dy3Xg4q222nY3qbxkB4szr87LS` | 2025/2026 awareness library indexed |
| 09 | ERP Related | `1liKuc0p9YFvRgir4Zqz9L77w4dYg7Pvy` | ERP master plan, improvements, OBK/PARQ and swimlane sources indexed |
| 10 | รายงานอุบัติการณ์ (Incident Report) | `1hvbfK1plyPlrUI03y2YO87vTtzeYJTy_` | Metadata/reference only; case-level raw reports remain restricted in Drive |

## Controlled Document Management Logs

| Document Type | Canonical Log | Drive File ID | Records/Slots detected | Populated document titles | Status-bearing records |
|---|---|---|---:|---:|---:|
| Policy | Policy - Document Management Log - May 2026.xlsx | `1Wwv1OCvO7ZTr2OiGv49cl9ZnL2fpJjc5` | 152 | 3 | 3 |
| Manual | MAN - Document Management Log - May 2026.xlsx | `1HAbrS93wcZiexWPXGCIcx3VNNkguRFOe` | 152 | 1 | 1 |
| SOP | SOP - Document Management Log - June 2026.xlsx | `1KEtXzVjlOrUgANDHOSJQz4KLElTcU3Ej` | 281 | 209 | 197 |
| WI | WI - Document Management Log - May 2026.xlsx | `1SypNTk0wpsUtL2AXoRvo2dNomtdKi3OS` | 152 | 3 | 3 |
| Supporting Document | SP - Document Management Log - May 2026.xlsx | `1D8Qme50BzbUjTB4lZrfbclCGIZ0reBCk` | 152 | 2 | 4 |
| External Document | EXT - Document Management Log - May 2026.xlsx | `1-i_9uL0cYheg3UplnpM1M4Qm-sfxEwd4` | 152 | 0 | 0 |

Total controlled code records/slots detected across the six management logs: **1,041**.

### SOP Status Snapshot from the controlled log

The SOP log currently contains the following status-bearing records across the registered plan: **Complete 144, Obsolete 46, Not Start 10, On Process 8**. Blank/reserved rows are retained in the Drive log and must not be interpreted as approved documents.

### SOP Domain Coverage

The SOP source is structured by the following controlled process domains: `SSHE`, `BO`, `AD`, `EN`, `EP`, `MR`, `EE`, `SN`, `ME`, `PMEE`, `PMSN`, `PMME`, `SV`, `PP`, `GA`, `AM`, `LW`, `DCC`, `ICT`, `IRPM`, `CC`, and `L1`.

The SOP root also includes `SOP ที่ยกเลิกใช้งาน`; documents in that folder must remain explicitly marked cancelled/obsolete/historical and must never be silently promoted to current operational status.

## Key Current Policy / Manual Sources Located

- `OB-POL-SSHE-0001 - Smoking Policy Rev.00.pdf` — Drive ID `1PNhv2rAVC0dMUB9IOIIiGltR5s28bxsK`
- `OB-POL-SSHE-0002 - Safety Health and Environment (SHE) Policy Rev.00.pdf` — Drive ID `1PcjYbDcwy6ofDxPKWuHwXnRIsrfTAWgb`
- `OB-POL-SSHE-0003 - Resilience Policy Rev.00.pdf` — Drive ID `1Ju7oOYnRQjQc7grM35u7fReC-v_oa0dF`
- `OB-MAN-SSHE-0001 - คู่มือระบบบริหารจัดการอาชีวอนามัย และความปลอดภัย (OH&S Manual) Rev.00.pdf` — Drive ID `1gtp_KkCV5h9A9UGb_cT2GYKmp70fhRMr`

## Safety Awareness Library

### 2026

Indexed items currently visible in the authorized folder include:
- `OB-JLL-SSHE-SA-2026-001_Lock out Tag out (LOTO).pdf`
- `OB-JLL-SSHE-SA-2026-002_9 Ways to Reduce the Impact of PM2.5 in Office Buildings.pdf`
- `OB-JLL-SSHE-SA-2026-003 Nipah Virus Disease .pdf`
- `OB-JLL-SSHE-SA-2026-004 Get ready to enjoy the summer safely.pdf`
- `OB-JLL-SSHE-SA-2026-006 Know the Law. Follow the Rules. Keep Everyone Safe..pdf`
- `OB-JLL-SSHE-SA-2026-007 Safety Induction-The Critical Foundation for a Safe Workplace.pdf`
- `OB-JLL-SSHE-SA-2026-008_CAUTION Uneven Surface in Parking Area.pdf`
- `OB-JLL-SSHE-SA-2026-009 Safe Songkran.pdf`
- `OB-JLL-SSHE-SA-2026-010 Hazard Identification The Starting Point of Workplace Safety.pdf`

### 2025

Indexed items currently visible in the authorized folder include:
- `OB-JLL-SSHE-SA-2025-022 Small Cutter, Big Risk! Use It Safely.pdf`
- `OB-JLL-SSHE-SA-2025-023 Small Cutter, Big Risk! Use It Safely.pdf`
- `OB-JLL-SSHE-SA-2025-024 Safe moving of chemicals..pdf`
- `OB-JLL-SSHE-SA-2025-025 Understanding “Hurry Sickness” – The Inability to Wait.pdf`
- `OB-JLL-SSHE-SA-2025-026 Lifestyle Adjustments When PM 2.5 Contaminates Again.pdf`

Duplicate/near-duplicate titles are preserved as source facts and must be reviewed rather than silently merged.

## ERP Related Sources

Indexed at the ERP root:
- `ERP Master Plan 2026 as of 24 June 2026.xlsx` — Drive ID `1QX2eI2WgxvKctMTCCPmCf3x3PE44SyFH`
- `ERP Problems and Improvement Suggestion.xlsx` — Drive ID `1c4lCWGcxrLZWZiza1eK4C_qCgx9Y_99Y`
- `Stoplog Drill - 2026.xlsx` — Drive ID `1ONsoG5xb19FbAJQYnD0C4L2ybutEnYQB`
- `One Bangkok` folder — Drive ID `1SB-JtvIwmX_gk_PaU56rtq0GrFc8Y4hu`
- `The PARQ` folder — Drive ID `1Eo1GLU1HCmJ9YvVhwXB7NweXtKuWl76_`
- `OBK - Swimlane` folder — Drive ID `14GGcbJ1a39ZX0ntxFDVOK-5xJByH5pM7`
- `desktop.ini` is retained as a source artifact but has no operational knowledge value.

## Incident Report Source Boundary

The root contains `2026 Incident Report Logbook.xlsx` (Drive ID `1DGEEG79SdclbqAhx04BDNKHP_g4JJm6T`) and site/component folders including One Power, CI & Carpark, One Bangkok Forum, Parade, The Storeys, Tower 3, Tower 4, Tower 5, The Ritz-Carlton, Andaz One Bangkok, One89 Wireless, Eighteen Seven and Post 1928.

**Restriction:** Case-level incident reports may contain PII, medical details, investigation evidence or other sensitive operational content. GitHub stores only the source map/reference and safe derived knowledge; raw report contents remain in Google Drive.

## Import Rules Applied

1. Preserve the exact source status: Complete, On Process, Not Start, Obsolete, Draft, Signed, Historical or Cancelled where stated.
2. Never infer approval from filename or folder location alone when the source does not explicitly support it.
3. Preserve revision conflicts and duplicates as findings; do not reconcile them silently.
4. Use the Document Management Logs as the canonical structured register for controlled document codes and planning status.
5. Use the actual source file/folder in Drive for document-level verification before quoting procedures or operational requirements.
6. Restricted raw content remains in Drive; Inventory stores metadata/reference and sanitized extracts only.
7. New or modified Drive sources should be revalidated against this register before being treated as current.

## Relationship to Existing KB

- `WK-OBK-SOP-001` remains the detailed SOP/WI document register for operationally inspected files and revision findings.
- `WK-OBK-SRC-001` remains the broader source map.
- `WK-OBK-SRCINV-001` remains the source inventory framework.
- `WK-OBK-LIB-001` (this file) is the authorized One Bangkok document-library inventory for the Google Drive root supplied by Boss on 3 September 2026.

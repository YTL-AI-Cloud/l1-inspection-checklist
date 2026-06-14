# L1 Physical Hardware Inspection Checklist — GB200 Core POD

A self-contained, offline-capable HTML checklist for Level 1 engineers performing physical walkthrough inspections in a GB200/Core POD data hall.

**Live:** https://ytl-ai-cloud.github.io/l1-inspection-checklist/

---

## Versions

| File | Description | Items |
|---|---|---|
| [L1_Inspection_Checklist_GB200.html](L1_Inspection_Checklist_GB200.html) | v1 — original 12-section checklist | 91 |
| [L1_Inspection_Checklist_GB200_v2.html](L1_Inspection_Checklist_GB200_v2.html) | v2 — consolidated based on field feedback | 53 |

v2 is the recommended version for daily use.

---

## Features

- **No installation, no backend** — single HTML file, works offline and on mobile
- **Pass / Fail / N/A** status for each item with per-item remarks popup
- **CSV export** — saves all statuses, remarks, and handover notes to a timestamped file
- **CSV import** — load a previous session to resume or hand over between shifts
- **Progress bar** — live completion counter across all sections
- **Print / Export** — browser print dialog for paper copy

---

## How to Use

### Daily inspection
1. Open the checklist URL on your phone or laptop
2. Fill in the metadata (engineer name, date/time, zone, rack)
3. Work through each section — tap **Pass**, **Fail**, or **N/A** for each item
4. Add remarks via the **Add remark…** button for any finding
5. Tap **Save & Download CSV** when done

### Shift handover
1. Outgoing engineer saves CSV at end of shift
2. Incoming engineer opens the checklist and taps **Load CSV**
3. All statuses and remarks are restored — continue from where the previous shift left off
4. Fill in the **Handover Remarks** field and save a new CSV

---

## What v2 Changes (from field feedback)

- Granular LED/status items merged into single consolidated checks (sections 3, 4, 5, 6)
- Items removed that L1 engineers cannot access (VESDA panel, waste bin)
- Section 12 (alarm verification) removed — checks already covered in each section
- Shift Handover simplified to a single Handover Remarks field
- Final Sign-Off section removed

---

## L1 Boundary

L1 engineers **observe, record, raise tickets, and escalate**. This checklist does not authorise:
- Reseating servers, switches, PSUs, or modules
- Touching liquid cooling hoses, manifolds, or fittings
- Unplugging or transferring power cables
- Moving fiber cables without an approved MOP

---

## Repo Structure

```
index.html                                  ← GitHub Pages redirect
L1_Inspection_Checklist_GB200.html          ← v1 checklist
L1_Inspection_Checklist_GB200_v2.html       ← v2 checklist (recommended)
L1_Inspection_Checklist_GB200_with_photos.html  ← experimental photo version (archived)
```

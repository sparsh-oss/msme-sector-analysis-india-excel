# MSME Sector Analysis — India (Excel)

An Excel-based analysis of India's Udyam-registered MSME (Micro, Small & Medium Enterprises) data across 785 districts, exploring state-wise and district-wise distribution, and the manufacturing vs. service sector split.

## 📊 Project Overview

MSMEs are the backbone of India's economy — this project analyzes real government registration data to answer:

- Which states have the highest concentration of registered MSMEs?
- What's the manufacturing vs. service split nationally and by state?
- Which districts are India's top MSME hubs?

This project connects directly to my work at Limelight IT, where I support MSMEs in the RAMP scheme — this analysis reflects the same sector I work with professionally.

## 🛠️ Tools & Techniques Used

- **Power Query** for CSV import and data cleaning (handling "NA" placeholder values)
- **SUMIF** for state-level aggregation from district-level raw data
- **Sorting & ranking** to identify top states/districts
- **Dashboard design** with KPI cards and comparison charts

## 🔑 Key Findings

**Top 5 States by Total MSMEs**
| Rank | State | Total MSMEs | Manufacturing Share |
|---|---|---|---|
| 1 | Maharashtra | 36,70,797 | 77.1% |
| 2 | Tamil Nadu | 21,47,720 | 70.4% |
| 3 | Uttar Pradesh | 20,01,698 | 72.0% |
| 4 | Rajasthan | 15,40,402 | 70.7% |
| 5 | Gujarat | 15,36,720 | 64.5% |

Maharashtra leads by a wide margin — its MSME count is nearly 1.7x that of second-ranked Tamil Nadu.

**Top 10 Districts by Total MSMEs**
| Rank | District | State | Total |
|---|---|---|---|
| 1 | Pune | Maharashtra | 5,59,036 |
| 2 | Thane | Maharashtra | 4,00,521 |
| 3 | Ahmadabad | Gujarat | 3,31,635 |
| 4 | Bengaluru (Urban) | Karnataka | 3,28,253 |
| 5 | Jaipur | Rajasthan | 3,18,407 |
| 6 | Surat | Gujarat | 3,12,676 |
| 7 | Mumbai Suburban | Maharashtra | 2,88,509 |
| 8 | Chennai | Tamil Nadu | 2,55,762 |
| 9 | Mumbai | Maharashtra | 2,50,488 |
| 10 | Nashik | Maharashtra | 1,81,119 |

5 of the top 10 districts are in Maharashtra alone, reinforcing the state's dominant MSME density.

**Manufacturing vs. Service Split**
Most states show a strong manufacturing lean, typically 65–85% of registered MSMEs, with Gujarat showing a comparatively more balanced split (64.5% manufacturing) than states like Himachal Pradesh (~83%).

## 📁 Repository Contents

- `msme_sector_analysis.xlsx` — full workbook (Raw Data, Analysis, Top Districts, Dashboard)
- `MSME-UDYAM.csv` — source dataset

## 💡 Relevance

This analysis mirrors the kind of sector-level insight used in real MSME policy and support work — identifying where enterprise density is concentrated helps prioritize outreach, credit access programs, and scheme implementation (such as RAMP) in the states and districts where they matter most.

## 📌 Dataset Source

District-wise Udyam MSME Registration Data — Kaggle

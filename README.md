# Early-Stage Asset Analysis: IP, Market, and Indication Strategy for NEOK001
*Author: Yuying Fan*  
*Project developed as independent strategic analysis, April 2026*  

## Project Aim - Strategic Recommendation for Phase 1 Clinical Development

This project began as a student consulting case study through the Life Sciences Career Development Society (LSCDS) at University of Toronto, where I contributed and worked on the IP landscape workstream of the pipeline group. Building on the advisors feedback and recommendations from that engagement, this repository represents my own independent extension of the analysis — incorporating proteomic expression scoring across 12 candidate indications, commercial opportunity sizing, data-driven indication prioritization recommendation for Phase 1 clinical development, AI-assisted competitive patent landscaping, and in-depth analysis of current patent portfolio.

This project is a data-driven analysis identifying the optimal initial indication for NEOK001 (ROR1×B7-H3 bispecific ADC) Phase 1 clinical development - with comprehensive market sizing, competitive landscape mapping, value proposition and patent portfolio analysis.

---

### Disclaimer

**Independent analysis. All data sourced from publicly available information. For educational and portfolio purposes only.*

*All data is sourced from public databases including CPTAC, ClinicalTrials.gov, SEER, and Lens. This analysis was completed independently as a portfolio project and is not affiliated with NEOK Bio nor ABL Bio. Background information on both companies was compiled from public sources, including press releases, company news, investor decks, presentations, and publicly disclosed pre-clinical results.*

---
---

## Background

NEOK001 (or ABL206) is a first-in-class bispecific antibody-drug conjugate (BsADC) developed by ABL Bio and being advanced clinically by  NEOK Bio (Palo Alto, CA). 

It simultaneously targets two tumor-associated  antigens, **ROR1** and **B7-H3**, and uses a **topoisomerase I (Topo-I) inhibitor** payload via Synaffix's SYNtecan-E linker-payload platform.

NEOK Bio received FDA IND clearance for NEOK001 in January 2026 and plans to initiate Phase 1 trials mid-2026, with first clinical readouts expected for 2027.

NEOK Bio's CEO, Mayank Gandhi, has indicated the dual-targeting strategy is designed to address a wide range of indications with large unmet needs, with initial focus on <u>thoracic, gastrointestinal, and gynecological cancers</u> — tumor types known to be sensitive to Topo-I inhibition.

---

### Objective
To present a **strategic recommendation** to NEOK Bio senior leadership for  NEOK001's optimal initial Phase 1 indication(s), supported by:
- Medical and scientific feasibility scoring
- US market sizing and opportunity assessment
- Pricing strategy
- Competitive landscaping
- Patent Portfolio analysis

### Scope
This analysis is focused on the **United States market**, the largest 
global oncology market and the primary commercialization target for NEOK001 (given NEOK Bio's US-based operations and FDA IND clearance).

---
---

## How to Read This Repo
**Non-technical readers:** Read reports 1 to 8 in the `reports/` folder.
Each report contains results, figures, and key findings with no code.

**Technical readers:** Read the same reports for context, then go into the corresponding notebooks in `notebooks/` for methodology and code.

### Folder Structure

```
NEOK001-Strategy/
├── README.md
├── reports/                           ← narrative reports (no code
│   ├── 1_ADC_Biology.md
│   ├── 2_NEOK001_Asset.md
│   ├── 3_Indication_Scoring.md
│   ├── 4_Market_Research.md
│   ├── 5_Competitive_IP_Landscape.md
│   ├── 6_IP_Portfolio.md
│   ├── 7_IP_Portfolio.md
│   └── 8_Recommendation.md
├── notebooks/                         ← full code and methodology
│   ├── 0_setup.ipynb
│   ├── 4_indication_scoring.ipynb
│   ├── 5_ip_portfolio/
│   │   ├── 5a_global_adc_landscape.ipynb
│   │   ├── 5b_us_competitor_patents.ipynb
│   │   ├── 5c_neok001_competitive_risk.ipynb
│   │   └── 5d_neok001_own_portfolio.ipynb
│   ├── 6_market_research.ipynb
│   ├── 7_competitive_landscape.ipynb
│   └── 8_recommendation.ipynb
└── data/
│   ├── ai_results/
│   ├── images/
│   ├── processed/
│   └── raw/
└── ITCS_report.pdf
└── final_report.pdf
```

### File Contents

| File | Type | Description |
|------|------|-------------|
| `reports/1_ADC_Biology_and_Mechanism.md` | Report | What is an ADC, how do they work, payload classes, bispecific rationale |
| `reports/2_NEOK001_Asset_Profile.md` | Report | ROR1, B7H3, NEOK001 MoA, preclinical data, IND clearance, Synaffix linker |
| `reports/3_ABL_Bio_NEOK_Bio_Background.md` | Report | Company background, spinout story, CEO quotes, pipeline |
| `reports/4_Indication_Scoring.md` | Report | Medical + commercial scoring of 12 candidate indications |
| `reports/5_IP_Portfolio.md` | Report | Patent portfolio analysis, jurisdiction coverage, strategic gaps |
| `reports/6_Market_Research.md` | Report | Market sizing (TAM/SAM/SOM), customer discovery, value proposition |
| `reports/7_Competitive_Landscape.md` | Report | Direct/indirect competitors, pricing, reimbursement |
| `reports/8_Recommendation.md` | Report | Final strategic recommendation and clinical trial design |
| `notebooks/4_indication_scoring.ipynb` | Notebook | Full code for indication scoring analysis |
| `notebooks/5_ip_portfolio_analysis.ipynb` | Notebook | Patent portfolio analysis, jurisdiction coverage, strategic gaps |
| `notebooks/6_market_research.ipynb` | Notebook | Customer discovery, market sizing (TAM/SAM/SOM), value proposition |
| `notebooks/7_competitive_landscape.ipynb` | Notebook | Direct/indirect competitors, pricing, reimbursement, market share |
| `notebooks/8_recommendation.ipynb` | Notebook | Final strategic recommendation and clinical trial design |

---


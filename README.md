# Early-Stage Asset Analysis: Indication, Market and IP Strategy for NEOK001
*Author: Yuying Fan*  
*Project developed as independent strategic analysis, April 2026*  

## Project Aim - Strategic Recommendation for Phase 1 Clinical Development

This project began as a student consulting case study through the Life Sciences Career Development Society (LSCDS) at University of Toronto, where I contributed and worked on the IP landscape workstream of the pipeline group. Building on the advisors' feedback and recommendations from that engagement, this repository represents my own independent extension of the analysis - incorporating proteomic expression scoring across 12 candidate indications, commercial opportunity sizing, data-driven indication prioritization recommendation for Phase 1 clinical development, AI-assisted competitive patent landscaping, and in-depth analysis of current patent portfolio.

This project is a data-driven analysis identifying the optimal initial indication for NEOK001 (ROR1×B7-H3 bispecific ADC) Phase 1 clinical development - with comprehensive market sizing, competitive landscape mapping, value proposition and patent portfolio analysis.


> ### Disclaimer
> 
> **Independent analysis. All data are derived from publicly available sources and are presented for educational and portfolio purposes only.**
> 
> <u>Data sources:</u> Public databases including CPTAC, ClinicalTrials.gov, SEER, and The Lens. Data obtained from The Lens represent a curated and processed subset relevant to antibody-drug conjugates (ADCs); this repository does not reproduce or redistribute the full Lens database. Readers should refer to The Lens for full datasets and terms of use.
> 
> <u>Attribution and use:</u> Additional background information on NEOK Bio and ABL Bio was compiled from publicly available materials; including press releases, investor presentations, company reports, and disclosed preclinical results. This work is an independent analysis and is not affiliated with NEOK Bio or ABL Bio.
> 
> <u>Advisory note:</u> IP advisory was provided by Stacey Ivanchuk during the ITCS Program.
>

---

## Background

NEOK001 (or ABL206) is a first-in-class bispecific antibody-drug conjugate (BsADC) developed by ABL Bio and being advanced clinically by  NEOK Bio (Palo Alto, CA). 

It simultaneously targets two tumor-associated  antigens, **ROR1** and **B7-H3**, and uses a **topoisomerase I (Topo-I) inhibitor** payload via Synaffix's SYNtecan-E linker-payload platform. The bispecific design is intended to refine tumor selectivity by leveraging the broad coverage of B7-H3 while narrowing effective targeting through ROR1 expression.

NEOK Bio received FDA IND clearance for NEOK001 in January 2026 and plans to initiate Phase 1 trials mid-2026, with first clinical readouts expected for 2027.

NEOK Bio's CEO, Mayank Gandhi, has indicated the dual-targeting strategy is designed to address a wide range of indications with large unmet needs, with initial focus on <u>thoracic, gastrointestinal, and gynecological cancers</u> — tumor types known to be sensitive to Topo-I inhibition.

---

## Objective
To present a **strategic recommendation** to NEOK Bio senior leadership for  NEOK001's optimal initial Phase 1 indication(s), supported by:
- Medical and scientific feasibility scoring
- US market sizing and opportunity assessment
- Pricing strategy
- Competitive landscaping
- Patent Portfolio analysis

> ### Scope
> This analysis is focused on the **United States market**, the largest global oncology market and the primary commercialization target for NEOK001 (given NEOK Bio's US-based operations and FDA IND clearance).
>

---

## How to Read This Repo
**Non-technical readers:** Read reports 1 to 6 in the `reports/` folder.
Each report contains results, figures, and key findings with no code.

**Technical readers:** Read the same reports for context and explanation, then go into the corresponding notebooks in `notebooks/` for methodology and code.

### Folder Structure

```
NEOK001-Strategy/
├── README.md
├── reports/                           ← narrative reports (no code)
│   ├── 1_ADC_Biology.md
│   ├── 2_NEOK001_Asset.md
│   ├── 3_Indication_Scoring.md
│   ├── 4_Market_Research.md
│   ├── 5a_IP_Global_ADC_Landscape.md
│   ├── 5b_IP_US_ADC_Landscape.md
│   ├── 5c_IP_NEOK001_Portfolio.md
│   └── 6_Recommendation.md            ← Final Recommendation Report
├── notebooks/                         ← full code and methodology
│   ├── 0_setup.ipynb
│   ├── 3_indication_scoring.ipynb
│   ├── 4_market_research.ipynb
│   └── 5_ip_portfolio/
│       ├── 5a_global_adc_landscape.ipynb
│       ├── 5b-1_us_adc_patents.ipynb
│       ├── 5b-2_technical_competitors.ipynb
│       └── 5c_neok001_portfolio.ipynb
└── data/
    ├── ai_results/
    ├── images/
    ├── processed/
    └── raw/

```

### File Contents

### File Contents

| Path | File | Type | Description |
|------|------|------|-------------|
| `reports/` | `1_ADC_Biology.md` | Report | ADC fundamentals, Design, Bispecific rationale |
| `reports/` | `2_NEOK001_Asset.md` | Report | ABL Bio, NEOK Bio, NEOK001 MoA, Preclinical data |
| `reports/` | `3_Indication_Scoring.md` | Report | Clinical and commercial scoring of candidate indications, Indication Selection |
| `notebooks/` | `3_indication_scoring.ipynb` | Notebook | Code for indication scoring analysis |
| `reports/` | `4_Market_Research.md` | Report | Market analysis, ADC benchmarking, Market sizing (TAM/SAM/SOM), Pricing assumptions (dosing, WAC) |
| `notebooks/` | `4_market_research.ipynb` | Notebook | Code for market research |
| `reports/` | `5a_IP_Global_ADC_Landscape.md` | Report | Global ADC patent landscape and competitive intensity |
| `notebooks/5_ip_portfolio/` | `5a_global_adc_oncology_landscape.ipynb` | Notebook | Code for global ADC patent landscape analysis |
| `reports/` | `5b_IP_US_ADC_Landscape.md` | Report | US ADC patent landscape: AI-driven claim classification, competitor strategy, technical overlap analysis |
| `notebooks/5_ip_portfolio/` | `5b-1_us_adc_patents.ipynb` | Notebook | Code for US ADC patent landscape analysis |
| `notebooks/5_ip_portfolio/` | `5b-2_technical_competitors.ipynb` | Notebook | Code for US ADC patent landscape analysis |
| `reports/` | `5c_IP_NEOK001_Portfolio.md` | Report | NEOK001-specific patent strategy |
| `notebooks/5_ip_portfolio/` | `5c_neok001_portfolio.ipynb` | Notebook | Code and Detailed claim analysis for NEOK001-related patents |
| `reports/` | `6_Recommendation.md` | Report | **Final recommendation and report** |
| `data/raw/` | `*` | Data | Source datasets (primarily patent data exported from the Lens) |
| `data/processed/` | `*` | Data | Cleaned and analysis-ready datasets generated during workflows |
| `data/ai_results/` | `*` | Data | Outputs from AI-based claim classification and related analyses |
| `data/images/` | `*` | Data | Figures, plots and visual assets |

---


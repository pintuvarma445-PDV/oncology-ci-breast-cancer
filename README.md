# Breast Cancer Competitive Intelligence Project (Epidemiology + Clinical Pipeline)

This project provides a complete Competitive Intelligence (CI) analysis of **Metastatic Breast Cancer**, combining:

- 📊 Global Epidemiology (GLOBOCAN-style dataset)
- 🧪 ClinicalTrials.gov Pipeline Analysis (4000+ trials)
- 🧬 Intervention Trends
- 🏭 Top Sponsors & Competitive Landscape
- 🔍 CI Insights for Pharma R&D Strategy

---

## 📂 Project Structure

oncology-ci-breast-cancer/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── 01_data_preparation.ipynb
│ └── 02_epidemiology_analysis.ipynb
│
├── reports/
│ ├── figures/
│ ├── phase_summary.csv
│ ├── keyword_summary.csv
│ ├── status_summary.csv
│ └── top_sponsors.csv
│
├── src/
└── README.md


---

## 🧪 Clinical Trials – Phase Summary

| Phase     | Trials |
|-----------|--------|
| Phase 1   | 134 |
| Phase 2   | 138 |
| Phase 3   | 33 |
| Unknown   | 3802 |

🧠 **Insight:** Pipeline heavy in early development; only ~1% trials reach Phase 3.

---

## 🏭 Top Sponsors (20 Most Active)
Competitive landscape analysis identifies leaders such as:
- Major pharma companies  
- Biotech innovators  
- Academic research centers  

(Generated in: `reports/top_sponsors.csv`)

---

## 🧬 Intervention Trends  
Keywords extracted from interventions text:
- Antibody therapy  
- Immunotherapy  
- Hormone therapy  
- Targeted therapy  
- CDK4/6 inhibitors  
- HER2 therapies  

(See: `reports/keyword_summary.csv`)

---

## 🌍 GLOBOCAN-Style Epidemiology

### World Analysis  
Image saved at:
reports/figures/world_top10_asr.png


### India Regional Analysis  
Image saved at:
reports/figures/india_regions_asr.png


---

## 🚀 Run the Project

pip install -r requirements.txt
jupyter lab


---

## Author  
**Pintu Varma**  



<h1 align="center">Saikumarchary Sripathi</h1>
<h3 align="center">Sr. Healthcare Data Analyst · Pharm.D. · M.S. Health Data Science</h3>

<p align="center">
  <a href="mailto:Saikumarchary1709@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/saikumarchary-sripathi-569995260"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Location-St.%20Louis%2C%20MO-4B8BBE?style=flat-square"/>
  <img src="https://img.shields.io/badge/Open%20to%20Work-Yes-brightgreen?style=flat-square"/>
</p>

---

## 👋 About Me

I'm a **Healthcare Data Analyst** with a rare combination of **clinical depth** and **data engineering breadth** — a licensed **Pharm.D.** with an **M.S. in Health Data Science** and **3+ years** building production-grade analytics systems across payer, PBM, and hospital settings.

I don't just build reports — I build the infrastructure that makes reporting trustworthy. My work sits at the intersection of **SQL engineering**, **ETL architecture**, **HEDIS/STAR quality measurement**, and **ML-powered clinical tools** — all grounded in hands-on knowledge of how claims, eligibility, and pharmacy data actually flow in the real world.

> 🏥 Currently: **Sr. Healthcare Data Analyst @ Cardinal Health** supporting Medicare and Commercial analytics at scale.

---

## 🛠️ Technical Stack

### Languages & Databases
![SQL](https://img.shields.io/badge/SQL-T--SQL%20%7C%20PL%2FSQL%20%7C%20PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20Scikit--learn%20%7C%20XGBoost%20%7C%20SHAP%20%7C%20Streamlit-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-tidyverse%20%7C%20ggplot2-276DC3?style=flat-square&logo=r&logoColor=white)
![SAS](https://img.shields.io/badge/SAS-Basic-A100FF?style=flat-square)

### BI & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-DAX%20%7C%20RLS%20%7C%20Drillthrough-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-Dashboards%20%7C%20Utilization%20Analytics-E97627?style=flat-square&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Advanced%20%7C%20Power%20Query%20%7C%20Macros-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

### ETL & Data Engineering
![Informatica](https://img.shields.io/badge/Informatica-PowerCenter-FF4C00?style=flat-square)
![SQL Server](https://img.shields.io/badge/SQL%20Server-ETL%20%7C%20Automation%20%7C%20Pipelines-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Synapse%20(In%20Progress)-0089D6?style=flat-square&logo=microsoftazure&logoColor=white)

### Healthcare Standards & Systems
![HEDIS](https://img.shields.io/badge/HEDIS-PDC%20%7C%20Readmission%20%7C%20Measures-00897B?style=flat-square)
![CMS](https://img.shields.io/badge/CMS-STAR%20Ratings%20%7C%20Medicare%20Part%20D%20%7C%20PDE-005A9C?style=flat-square)
![EDI](https://img.shields.io/badge/EDI-837%20%7C%20835%20%7C%20834-6A1B9A?style=flat-square)
![EHR](https://img.shields.io/badge/EHR-Epic%20Clarity%20%7C%20Cerner%20%7C%20Facets-1565C0?style=flat-square)

---

## 📊 What I Bring to the Table

```
┌─────────────────────────────────────────────────────────────────────┐
│  CLINICAL KNOWLEDGE  +  DATA ENGINEERING  +  ML/ANALYTICS           │
│                                                                       │
│  ✔ Pharm.D.-trained — I understand NDC/GPI drug logic, PDC          │
│    calculation, and medication adherence at a clinical level          │
│                                                                       │
│  ✔ HEDIS/STAR production experience — denominator/numerator/        │
│    exclusion logic, CMS submission-ready, zero audit defects         │
│                                                                       │
│  ✔ SQL engineering at scale — CTE pipelines, window functions,      │
│    query optimization across 3M+ member datasets                     │
│                                                                       │
│  ✔ ML in production — XGBoost risk model actively used by           │
│    Pharm.D. interns for clinical decision support                    │
│                                                                       │
│  ✔ EDI expertise — end-to-end 837/835/834 validation in Facets      │
│    across enrollment, claims, and payment workflows                  │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Featured Projects

### 🔬 [BRFSS Chronic Disease Risk Engine v2](https://brfss-risk-engine-v2-hvqxy8iedykqhxypp95rye.streamlit.app) · *Live Production App*
> `Python` · `XGBoost` · `SHAP` · `Streamlit` · `CDC BRFSS 2019–2021`

A multi-disease risk prediction application **actively used by Pharm.D. interns** in a superspecialty hospital for clinical decision support — not a toy project, a real deployment.

- Predicts patient-level risk for **Diabetes, Hypertension, Heart Disease, and Obesity** from CDC BRFSS population data
- SHAP explainability surfaces **individual risk drivers** for clinician interpretability
- Resolved 12 production-level engineering challenges: age bin misalignment, label inconsistencies across survey years, and Streamlit Cloud deployment failures
- **Why it matters:** Bridges the gap between population health data and point-of-care clinical workflows

---

### 💊 [Medicare Part D High-Cost Patient Predictor](https://github.com/saikumar2608)
> `Python` · `XGBoost` · `SHAP` · `CMS PDE + Beneficiary Files` · `515K+ records (2015–2023)`

An end-to-end ML pipeline built on **real CMS public data** — not synthetic datasets.

- Engineered 14 predictive features including polypharmacy indicators (`POLY_5PLUS`, `POLY_10PLUS`), `GENERIC_PERCENT`, `OOP_TOTAL`, `ESRD_IND`
- **AUC: 0.974 | Recall: 0.833** for identifying top-10% high-cost Medicare beneficiaries
- SHAP analysis confirmed `TOTAL_FILLS` as the dominant cost driver (64.4% importance) — aligned with real PBM Medication Therapy Management targeting strategies
- **Why it matters:** Directly actionable for PBM cost containment and Medicare risk stratification programs

---

### 🗒️ [Clinical SOAP Note NLP — Disease Classification](https://github.com/saikumar2608)
> `Python` · `TF-IDF` · `XGBoost` · `Clinical NLP` · `10,000 SOAP Notes`

NLP pipeline classifying unstructured clinical notes into 6 disease categories for automated triage support.

- Built a **150+ term medical abbreviation expansion dictionary** to normalize clinical shorthand before vectorization
- TF-IDF (20K features + bigrams) + XGBoost achieved **90% accuracy, macro F1: 0.64** — outperforming Logistic Regression baseline by 27%
- Validated on an external clinical case dataset for out-of-sample generalization
- **Why it matters:** Demonstrates applied NLP on the messy, abbreviation-heavy text that defines real clinical documentation

---

### 🏥 [Healthcare SQL Analytics & ETL Validation Framework](https://github.com/saikumar2608)
> `SQL Server` · `PostgreSQL` · `HEDIS` · `Claims Analytics` · `EDI Validation`

A production-quality SQL portfolio replicating the logic used at real payers and PBMs.

- **Diabetic cohort engine:** ICD-10 (E10/E11) + NDC drug pathways with full PDC adherence metrics by drug class
- **HEDIS quality measures:** Complete 30-day all-cause readmission logic with denominator, numerator, and exclusion specifications
- **ETL validation framework:** 10 automated data quality rules — financial reconciliation, orphan record detection, eligibility overlap checks, CPT/ICD format validation
- Exception reporting dashboards for data governance and pipeline monitoring
- **Why it matters:** Shows I can build the foundation that HEDIS and STAR reporting actually depend on

---

## 📈 Experience at a Glance

| Role | Organization | Key Impact |
|------|-------------|------------|
| **Sr. Healthcare Data Analyst** | Cardinal Health | 3M+ member pipelines · $2M+ projected savings · 1,800 hrs/yr manual reporting eliminated |
| **Healthcare Data Analyst** | BCBS | 500K+ member analytics · 18% reduction in reporting errors · 200+ EDI defects resolved |
| **Data Analyst Intern** | Excelerate | Claims & pharmacy analytics · dashboard development · HIPAA compliance |
| **Clinical Data Analyst** | ESI Hospital | SQL/Oracle/Excel analytics · EDI validation · UAT support |

---

## 🎓 Education & Credentials

| Credential | Institution |
|-----------|------------|
| 🎓 M.S. Medical Informatics *(Aug 2025)* | Saint Louis University, USA |
| 💊 Doctor of Pharmacy (Pharm.D.) | JNTUH, India |
| 🏅 Certified Health Data Analyst (CHDA) | AHIMA |
| 🔒 HIPAA Privacy & Security Certification | — |

---

## 📬 Let's Connect

I'm open to **Senior Healthcare Data Analyst**, **Healthcare Analytics Engineer**, and **Clinical Informatics** roles where deep domain knowledge + technical execution both matter.

<p align="center">
  <a href="mailto:Saikumarchary1709@gmail.com"><b>📧 Saikumarchary1709@gmail.com</b></a> &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/saikumarchary-sripathi-569995260"><b>💼 LinkedIn</b></a>
</p>

---

<p align="center"><i>"Healthcare data is complex by nature. I build systems that make it simple, reliable, and decision-ready."</i></p>

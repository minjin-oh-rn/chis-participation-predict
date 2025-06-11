# Predicting Continuity in Community Health Programs Using CHIS 2023

This project provides a generalizable and theory-informed framework to analyze sustained participation in community health programs.  
Built on public health data (CHIS 2023), this pipeline is intended for use across diverse institutional settings—whether in nursing informatics, community health, or health equity labs.

---

## 1. Project Objective

- Predict whether individuals will continue participating in community health programs (≥2 times)  
- Identify key structural and psychosocial predictors using public health datasets  
- Support theory-informed community nursing practice through data-driven analysis

---

## 2. Theoretical Framework

- **Donabedian Model**: Structure → Process → Outcome  
- **Social Capital Theory**: Trust, reciprocity, informal support  

These theories guide the selection of predictors and the interpretation of results.

---

## 3. Data and Methods

| Item      | Description |
|-----------|-------------|
| Dataset   | California Health Interview Survey (CHIS) 2023 |
| Outcome   | Program continuity (1 = ≥2 times, 0 = ≤1) |
| Predictors | Access score, trust indicators, social support, demographics |
| Tools     | Python, pandas, scikit-learn, SHAP |
| Method    | Logistic regression and SHAP interpretation |

---

## 4. Repository Structure

```
├── data/                # Cleaned dataset (.csv)
├── notebooks/           # Analysis notebooks
│   ├── 01_preprocessing.ipynb
│   ├── 02_modeling.ipynb
│   └── 03_shap_analysis.ipynb
├── results/             # Risk group interpretation and notes
├── theory/              # Variable-to-theory mapping
├── poster/              # (optional) Conference poster PDF
└── README.md            # Project description (this file)
```

---

## 5. Key Findings

- Trust and access were among the strongest predictors of continued participation.  
- Low-trust and low-access groups were identified as dropout risk groups.  
- SHAP analysis enabled model interpretation and group-level insights.

---

## 6. Implications

This project demonstrates how public health datasets and nursing informatics can be combined to inform community-based care models.  
Results can support targeted interventions in underserved populations.

---

## 7. Author

**Min Jin Oh, RN**  
PhD applicant in Nursing Informatics and Community Health  
M.S. in Nursing (in progress)  
M.B.A. in Arts & Cultural Management  
Email: bravedolet@gmail.com

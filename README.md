
#  Predicting Community Health Program Continuity Using Nursing Informatics and Social Capital (CHIS 2023)

##  Project Purpose
This project aims to predict sustained participation (≥2 times) in community health programs using CHIS 2023 data. A nursing informatics approach was used to combine access-to-care indicators and social capital theory for predictive modeling and policy analysis.

##  Conceptual Framework
- **Donabedian Model**: Structure → Process → Outcome  
- **Social Capital Theory**: Trust, reciprocity, and informal support

These frameworks guide variable selection and interpretation.

##  Methodology
| Item | Description |
|------|-------------|
| Dataset | California Health Interview Survey (CHIS) 2023 |
| Outcome | Participation continuity (1 = ≥2 times, 0 = ≤1) |
| Predictors | Access score, trust indicators, social support, age, gender, income |
| Tools | Python, pandas, scikit-learn, SHAP |
| Analysis | Logistic regression + SHAP explanation |

##  Repository Structure

 data/ → Cleaned dataset  
 notebooks/ → Analysis notebooks (`01_preprocessing`, `02_modeling`, `03_shap_analysis`)  
 theory/ → Variable-theory mapping (`donabedian_mapping.md`, `social_capital_map.md`)  
 results/ → SHAP interpretation notes (`risk_group_notes.md`)  
 poster/ → Poster PDF for academic presentation

##  Key Findings
- Trust and access were the most influential predictors.
- Low-trust and low-access groups were identified as high-risk for program dropout.
- SHAP visualizations guided intervention suggestions.

##  Implications
This project demonstrates a theory-based, data-informed modeling approach in community nursing. Results can support policy design for improving engagement in health programs.

## ‍ About the Researcher
Min Jin Oh, MSN, RN  
PhD Applicant in Nursing Informatics and Community Health  
 [LinkedIn] |  minjin.research@gmail.com


## About the Researcher

Min Jin Oh, RN  
PhD applicant in Nursing Informatics and Community Health  
M.S. in Nursing (in progress)  
M.B.A. in Arts & Cultural Management  
bravedolet@gmail.com

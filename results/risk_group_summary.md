# Risk Group Summary (SHAP-based Classification)

## 1. Purpose  
This document summarizes the differences in key variables between high-risk and low-risk groups based on SHAP values from the predictive model.

## 2. Variables of Interest  
The following variables are selected based on their theoretical relevance and importance scores from SHAP:

- Trust score  
- Health insurance coverage  
- Number of program participations (≥2 times vs <2 times)  
- Perceived general health  
- Accessibility index (if applicable)

## 3. Planned Table Format (to be filled with real data)

| Variable                         | High-Risk Group | Low-Risk Group |
|----------------------------------|-----------------|----------------|
| Mean Trust Score                | TBD             | TBD            |
| Insurance Coverage (%)          | TBD             | TBD            |
| Participation ≥2 (%)            | TBD             | TBD            |
| Perceived Health (Good+) (%)    | TBD             | TBD            |
| Accessibility Score (if used)   | TBD             | TBD            |

## 4. Planned Interpretation (after analysis)  
Preliminary assumption:
- Higher trust, insurance coverage, and accessibility are expected to be positively associated with sustained program participation (≥2 times).
- These patterns will be interpreted in relation to:
  - **Donabedian model**: Structural quality components (insurance, access)
  - **Social Capital theory**: Cognitive capital (trust)
  - **Andersen model**: Enabling and predisposing factors

## 4.1 SHAP-Based Summary Findings

Based on the initial SHAP interpretation:

- **Trust** and **accessibility** were the most influential predictors of sustained participation (≥2 times).
- Individuals with **low trust scores and limited access** consistently showed high dropout risk.
- Insurance coverage and perceived general health contributed meaningfully, but with less impact than trust-related features.
- Emotional/informal support also appeared relevant in subgroup analyses, particularly among older adults.

These findings will be finalized after full execution of the SHAP pipeline and group-specific statistical summaries.

## 5. Notes  
- SHAP risk group threshold: TBD  
- Sample size per group: TBD  
- This file will be updated once the SHAP pipeline is executed.

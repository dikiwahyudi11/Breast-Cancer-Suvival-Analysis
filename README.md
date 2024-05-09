## Analysis of Cox-Proportional Hazard Regression on Breast Cancer Patient Survival Modeling

![Breast Cancer Survival Analysis](https://example.com/breast_cancer_survival_analysis.png)
*Figure 1: Illustration depicting the Cox-Proportional Hazard regression analysis on breast cancer patient survival.*

### Introduction
This project is conducted as part of the course "Survival Analysis" and focuses on analyzing the survival of breast cancer patients who underwent surgery between 1958 and 1970 at the Billings Hospital, University of Chicago. We utilized Cox-Proportional Hazard regression to model the survival probabilities based on various factors, particularly the number of positive axillary nodes detected in breast cancer patients post-surgery.

### Summary of Methods
Cox-Proportional Hazard regression was employed to estimate the hazard function and hazard ratios for different covariates. The model's performance was evaluated using techniques such as model fitting, goodness-of-fit tests, and validation methods.

### Key Findings

1. **Best Cox-Proportional Hazard Model**: The best-fitted Cox-Proportional Hazard model for the survival data of breast cancer patients who underwent surgery between 1958 and 1970 at the Billings Hospital, University of Chicago, is represented by the equation:
   $$ \hat{h}(t, x_1) = h_0(t)\exp(0.05462 \times x _1) $$
   where \( x_1 \) denotes the number of positive axillary nodes detected in breast cancer patients post-surgery. From the estimated hazard function, it is evident that having a higher number of axillary nodes indicates an increased risk of death for breast cancer patients.

2. **Hazard Ratio for Axillary Nodes**: Based on the classification of axillary nodes according to the number detected (< 10 or \( \geq 10 \)) and the year of surgery, the hazard ratio for axillary nodes is calculated as \( \exp(1.25775) = 3.51750 \). This implies that breast cancer patients with 10 or more positive axillary nodes detected post-surgery are 3.51750 times more likely to experience death within 5 years compared to patients with fewer than 10 positive axillary nodes detected.

### Credit to Team Members
This project was a collaborative effort, and credit goes to the entire team for their contributions to data collection, analysis, and interpretation. Special thanks to [Team Member Name] for their assistance in data preprocessing and [Team Member Name] for their valuable insights during model selection.

### Uploaded File Description
- **breast_cancer_survival_data.csv**: Raw dataset containing information about breast cancer patient survival, including demographic data and clinical variables.
- **cox_regression_analysis.R**: R script for performing Cox-Proportional Hazard regression analysis on the breast cancer survival data.
- **survival_analysis_report.pdf**: Comprehensive report summarizing the findings and conclusions of the Cox-Proportional Hazard regression analysis.

## Modeling Breast Cancer Patient Survival Using Cox-Proportional Hazard Regression Analysis

![Survival Analysis](https://miro.medium.com/v2/resize:fit:856/1*Ckhi9soE9Lx2lIf9tPVLMQ.png) <br>
*Figure 1: Illustration of Survival Analysis Method*

### Introduction
This project is conducted as part of the course "Survival Analysis" and focuses on analyzing the survival of breast cancer patients who underwent surgery between 1958 and 1970 at the Billings Hospital, University of Chicago. We utilized Cox-Proportional Hazard regression to model the survival probabilities based on various factors, particularly the number of positive axillary nodes detected in breast cancer patients post-surgery.

### Methods
Cox-Proportional Hazard regression was employed to estimate the hazard function and hazard ratios for different covariates. The model's performance was evaluated using techniques such as model fitting and assumption tests.

### Key Findings
1. **Best Cox-Proportional Hazard Model**: The best-fitted Cox-Proportional Hazard model for the survival data of breast cancer patients who underwent surgery between 1958 and 1970 at the Billings Hospital, University of Chicago, is represented by the equation:
   $$\hat{h}(t, x_1) = h_0(t)\exp(0.05462 \times x_1)$$
   where $x_1$ denotes the number of positive axillary nodes detected in breast cancer patients post-surgery. From the estimated hazard function, it is evident that having a higher number of axillary nodes indicates an increased risk of death for breast cancer patients.
   
2. **Hazard Ratio for Axillary Nodes**: Based on the classification of axillary nodes according to the number detected (< 10 or $\geq 10$) and the year of surgery, the hazard ratio for axillary nodes is calculated as $\exp(1.25775) = 3.51750$. This implies that breast cancer patients with 10 or more positive axillary nodes detected post-surgery are 3.51750 times more likely to experience death within 5 years compared to patients with fewer than 10 positive axillary nodes detected.

### Credit to Team Members
This project was a collaborative effort, and credit goes to the entire team for their contributions to data collection, analysis, and interpretation.

### Uploaded File Description
- `haberman.xlsx`: Raw dataset containing information about breast cancer patient survival.
- `Project Model Survival_Kelompok 8.Rmd`: R Markdown script for performing Cox-Proportional Hazard regression analysis on the breast cancer survival data.
- `Project Model Survival_Kelompok 8.pdf`: Comprehensive report summarizing the findings and conclusions of the Cox-Proportional Hazard regression analysis.

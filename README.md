## Problem Statement
Can we assess whether a loan will be approved or declined based on the data input by an applicant during the online application, including both the applicant's and loan information?

## Details
Dataset downloaded [here](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/).

### Conclusion
#### Model Comparison
<img width="564" alt="image" src="https://github.com/Allison67/data-classification-loan-prediction/assets/96998345/d6ab7a17-d9c6-4136-8b22-ea847155c7b0">
   
Among the models evaluated in this project, the Support Vector Machine (SVM) emerged as the top-performing model with the highest F1 score (0.897959184). SVM's robustness in handling complex decision boundaries and its ability to capture subtle relationships in the data contributed to its superior performance.
#### Feature Importance
From the feature importance analysis, it is evident that several key factors significantly influence the loan approval decision. Credit history, loan amount, applicant income, and co applicant income were identified as the most influential features in the classification process. These features carry the most weight in determining whether a loan application will be approved or declined, providing valuable insights into the decision-making process.
#### Applicability
These models find real-world use in financial institutions and online loan applications, automating assessments for streamlined, unbiased, and efficient approvals. Yet, they have limitations, including data quality, bias in historical data, and external economic factors. Ongoing monitoring and refinement ensure their relevance in dynamic lending environments.

#### Others
code refer to [Data_Classification.ipynb](https://github.com/Allison67/data-classification-loan-prediction/blob/main/Data_Classification.ipynb).    
report refer to [Data_Classification_Report.pdf](https://github.com/Allison67/data-classification-loan-prediction/blob/main/Data_Classification_Report.pdf).

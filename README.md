# SAS_Project_Drug-effect
# 💊 SAS-Based Clinical Study – Evaluating Drug A’s Effect on Blood Sugar

This project analyzes a clinical dataset of 3,400 patients from Arizona and California to evaluate the effectiveness of Drug A in reducing fasting blood sugar levels. Using SAS, I performed data cleaning, statistical testing, and visual analysis to uncover patterns across age groups, states, and treatment outcomes.

## 📌 Objectives

- Assess whether Drug A significantly reduces fasting blood sugar levels  
- Investigate differences in blood sugar levels across age groups and states  
- Explore interactions between demographic factors and treatment outcomes  
- Provide data-driven recommendations for improving drug administration protocols  

## 🧪 Methodology

### Data Preparation  
- Merged two datasets using Patient_ID  
- Cleaned missing values (Age, Length of Stay, Total Charge)  
- Final dataset: 2,975 observations, 7 variables  
- Performed SRS sampling to select 1,000 patients for analysis  

### Statistical Analysis  
- **Paired t-test**: Compared fasting sugar levels before and after Drug A  
- **One-sample t-test**: Tested if mean fasting sugar = 100  
- **Two-sample t-test**: Compared post-treatment sugar levels between AZ and CA  
- **One-way ANOVA**: Assessed differences across age groups  
- **Two-way ANOVA (PROC GLM)**: Evaluated interaction between age and state  
- **Correlation & Scatter Plot**: Explored relationships between age and sugar levels  

## 📊 Key Findings

- Drug A did **not** significantly reduce blood sugar levels  
- Mean fasting sugar level was **not** equal to 100 (actual ≈ 112.3)  
- No significant difference between AZ and CA post-treatment levels  
- Older age groups showed **higher** post-treatment sugar levels  
- Age and state had a **statistically significant interaction** effect  
- Strong positive correlation (r = 0.933) between pre- and post-treatment sugar levels  


## 📬 Contact

Connect with me on [LinkedIn](https://www.linkedin.com/in/payalvaidya) or explore more projects on my GitHub profile!

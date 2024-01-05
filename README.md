# College Graduation Rate Prediction Project

## Overview
Welcome to the College Graduation Rate Prediction Project. This project is focused on applying various machine learning and deep learning models to predict the graduation completion rates of bachelor's degree programs across colleges in the United States. The analysis is based on data sourced from the College Scorecard.

### Objective
The primary objective of this project is to develop predictive models that can accurately forecast the graduation rates of colleges, utilizing a comprehensive dataset that spans approximately 20 years.

## Data Sources
- **College Scorecard Website:** [https://collegescorecard.ed.gov/](https://collegescorecard.ed.gov/)
- **Data Page:** [https://collegescorecard.ed.gov/data](https://collegescorecard.ed.gov/data)
- **Documentation:** [View Documentation](https://collegescorecard.ed.gov/assets/InstitutionDataDocumentation.pdf)
- **Dataset Download:** [CollegeScorecard Raw Data (04/19/2023)](https://ed-public-download.app.cloud.gov/downloads/CollegeScorecard_Raw_Data_04192023.zip)

## Project Description
### Data Preprocessing
The dataset comprises data from over 20 years, resulting in approximately 3200 columns. A significant aspect of this project is cleaning and preprocessing this extensive data to make it suitable for predictive modeling.

### Modeling Approach
- **Phase 1: Machine Learning Models**
  - Initial modeling is being done using various machine learning techniques.
  - Models include [Linear Regression,polynomial Regression, Decision Tree, Random Forest, Bagged Regressor, Xgboost etc.].

- **Phase 2: Deep Learning Models**
  - Following machine learning, deep learning models will be employed to enhance prediction accuracy.
  - Models will include [RNN, LSTM].

## Progress Updates
I am actively working on this project, and updates will be posted here regularly. Be sure to check back every week to stay informed about the latest developments!

### Current Status
- Data cleaning and initial preprocessing are underway.
- Initial machine learning models are being tested and evaluated.

## Contributing
Your contributions, suggestions, and feedback are highly appreciated. If you wish to contribute or have any queries, feel free to open an issue or submit a pull request.


## Contact
- [Thrushwanth kakuturu]
- [KakuturuThrushwanth@gmail.com]

---

Thank you for visiting this repository! Stay tuned for more updates.



# Predicting University Graduation Rates: A Comparative Analysis of ML Regression Models

Welcome to the Predicting University Graduation Rates Project! This independent study, conducted as part of the Master of Professional Studies in Data Science program at the University of Maryland Baltimore County, focuses on constructing machine learning and deep learning models to predict graduation rates at four-year institutions. The project aims to enhance predictive capabilities for educational outcomes, identify influential features, assess and compare regression models, and empower stakeholders with actionable insights.

## Problem Statement
The landscape of higher education demands scrutiny for institutional effectiveness and student success, with graduation rates serving as pivotal benchmarks. This study endeavors to contribute to academic understanding and empower stakeholders with actionable insights to improve institutional effectiveness and student success.

## Objectives
1. Enhance predictive capabilities for graduation rates at four-year institutions, focusing on "C100_4," "C150_4," and "C200_4" variables.
2. Identify influential features affecting graduation rates.
3. Assess and compare regression models to guide future analyses in higher education.
4. Empower policymakers and institutions with actionable insights for informed decision-making.

## Data Sources
- College Scorecard Website: [College Scorecard](https://collegescorecard.ed.gov/)
- College Scorecard Data Web Page: [Data](https://collegescorecard.ed.gov/data)
- Documentation: [Institution Data Documentation](https://collegescorecard.ed.gov/assets/InstitutionDataDocumentation.pdf)
- Dataset: [CollegeScorecard Raw Data (04/19/2023)](https://ed-public-download.app.cloud.gov/downloads/CollegeScorecard_Raw_Data_04192023.zip)

## Feature Selection and Importance Analysis
The project utilized distribution analysis and exploratory data analysis (EDA) to identify features with significant predictive potential. Noteworthy features include Pell Grant Rate, Average SAT Scores, Out-of-State Tuition, Median Student Debt, Non-Traditional Student Percentage, Average Faculty Salary, Undergraduate Enrollment, Average 4-Year Program Cost, Overall Admission Rate, and Percentage of Asian Students.

## Comparative Performance of Predictive Models
Here's a snapshot of the comparative analysis of various models:

| Model | Train R2 | Test R2 | Train MSE | Test MSE |
| ------ | -------- | ------- | --------- | -------- |
| Linear | 0.75 | 0.74 | 0.0077 | 0.0078 |
| Polynomial | 0.83 | 0.71 | 0.005 | 0.008 |
| Decision Tree | 0.87 | 0.63 | 0.003 | 0.011 |
| Random Forest | 0.81 | 0.76 | 0.005 | 0.007 |
| XGBoost | 0.99 | 0.78 | 0.006 | 0.0002 |
| RNN LSTM | 0.93 | 0.82 | 0.001 | 0.006 |

## Evaluating Model Performance: A Closer Look
Detailed analyses were conducted on key models, such as RNN LSTM, Decision Tree Regression, XGBoost Tuned, and Polynomial with Lasso. Each model's strengths, weaknesses, and tuning strategies were discussed.

## Conclusion
- The RNN LSTM Tuned model excelled with robust train and test R2 scores near 85%.
- Key influencers on graduation rates include financial aid and academic metrics.
- Comparative analyses highlighted the strengths of models like XGBoost, Decision Tree, Polynomial with Lasso, and Random Forest.
- Opportunities for further improvements in the RNN LSTM model were identified, suggesting the potential integration of advanced techniques like attention mechanisms.
- The findings equip education stakeholders with actionable insights for strategic planning to boost student success and institutional performance.

## Total Findings
For a comprehensive overview of the total findings and detailed insights, please refer to the [Final Report](final_report.docx) included in this repository.

## References
- "Introduction to Machine Learning," taught by Professor Masoud Soroush at UMBC.
- [PyTorch Tutorials](https://pytorch.org/tutorials/)

Feel free to contribute, provide feedback, or explore the detailed reports available in the repository, including Merging Data.ipynb, Featureselection.ipynb, Models.ipynb, and the final report in final_report.docx. Thank you for visiting this repository! Stay tuned for more updates and insights.



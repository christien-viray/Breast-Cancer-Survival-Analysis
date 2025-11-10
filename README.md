Breast Cancer Survival Analysis: Does Age Matter?
Author: Christien Bryan Reyes Viray

Summary
This project explores how age at diagnosis impacts breast cancer survival, using data from the METABRIC dataset. I performed exploratory data analysis, created visualizations, trained a logistic regression model, and evaluated its performance.


Question
Does age affect the likelihood of breast cancer survival?


Tools Used
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (Logistic Regression, Train/Test Split, Evaluation Metrics)
- Jupyter Notebook


Key Steps
- Cleaned and preprocessed the dataset (dropped irrelevant columns, encoded values)
- Visualized relationships between age and survival status, survival months, tumor stage, tumor size, and HER2 status
- Trained a logistic regression model to classify survival outcomes (alive vs deceased)
- Evaluated model with precision, recall, f1-score, and accuracy


Model Performance
Accuracy: 82%
Precision: 81–82%
Recall: 78–85%
F1 Score: 80–83%

The model performs well within an expected range for medical data. There’s room to improve with feature engineering or alternative models like Decision Trees.


Visual Insights
- Patients between **30–55** show higher survival rates
- Patients **over 70**, especially **80+**, show significantly lower survival
- HER2-positive patients were mostly aged **40–65**, aligning with more aggressive tumor behavior


Dataset
[Breast Cancer METABRIC Dataset on Kaggle](https://www.kaggle.com/datasets/gunesevitan/breast-cancer-metabric)


Report
See [`Breast_Cancer_Age_Survival_Report.docx`](./Breast_Cancer_Age_Survival_Report.docx) for a full write-up and results summary.


What I Learned
- How to explore a medical dataset and identify meaningful features
- How age at diagnosis can be correlated with health outcomes in cancer survival
- How to communicate insights visually and statistically
- The strengths and limits of logistic regression in binary classification
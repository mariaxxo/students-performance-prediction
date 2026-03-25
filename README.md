# Predicting Student Performance: What really matters?

The project explores the key factors influencing student exam performance and builds a machine learning model to predict whether a student is a high performer or not.
The goal is not only to achieve high accuracy, but also to understand what truly drives academic success.

# Dataset

The dataset contains information about students, including:
- Study habits, like attendance and hours studied
- Socio-economic factors, for example family income
- Personal and environental characteristics

After data cleaning, the dataset contained no missing values and was ready for further analysis and modeling.

# EDA

The key findings are:
- Most students score between 65-70% forming a near normal distribution
- Attendance and study time show the strongest relationship with performance
- Gender has little to no effect on performance

These finding suggest that both effort and external conditions influence academic success.

# Modeling

A classification model was build to predict whether a student is a high-performer (in top 25% of the students).
Two models were used: Logistic Regression and Random Forest.

Results:
- Logistic Regression Accuracy: ~97.5%
- Random Forest Accuracy: ~89.6%

Interestingly, the simpler model outperformed the more complex one, suggesting that the relationships between the variables are relatively linear.

The Random Forest model revealed that the most important factors are:
- Attendance, by a strong margain
- Hours studied
- Previous Scores

This confirms that consisent engagement is the key driver of student success.

# Conclusion

The project shows that student performance is influenced by a combination of effort (attendance, study habits) and environment (income, access to resources). However, consistant attendance emerges as the strongest predictor of success.

# Tools & Technologies
- Python (Pandas, Numpy)
- Data Visualization (Seaborn, Matplotlib)
- Machine Learning (Scikit-Learn)

🔍 Defect Prediction Using Logistic Regression
📌 Project Overview

This project focuses on predicting product defects in a manufacturing environment using Logistic Regression. The goal is to identify defective products early, reduce production costs, and improve overall quality through data-driven insights.

🎯 Business Objective
Detect defective products in advance
Minimize production losses and operational costs
Improve product quality and decision-making using predictive analytics
📊 Dataset Description

The dataset was created by combining multiple production-related sources:

Production data (operational metrics)
Machine master data
Operator master data
Final output label: defect_flag (indicates defective or non-defective product)
🛠️ Data Preparation
Consolidated multiple datasets into a unified dataset
Merged machine and operator details with production data
Cleaned and prepared features for modeling
Performed exploratory data analysis (EDA)
🤖 Model Used
Logistic Regression
Chosen for its balance of:
High performance
Interpretability
📈 Model Performance
Metric	Score
Accuracy	96%
Precision	90%
Recall	95%
F1 Score	92%
AUC Score	0.99
📉 Confusion Matrix
✅ Total Matches: 2339
❌ Mismatches: 102
🔍 Key Insights
High recall (95%) ensures most defects are detected
Strong precision (90%) reduces false alarms
Balanced F1-score (92%) indicates reliable performance
AUC score of 0.99 shows excellent model discrimination capability
🚀 Recommendations
Deploy the logistic regression model in production for real-time defect detection
Use predictions to reduce manufacturing costs and improve quality
Explore advanced models like Random Forest for future improvements
🧰 Tech Stack
Python
Pandas, NumPy
Scikit-learn
Matplotlib / Seaborn (for visualization)
📌 Conclusion

This project demonstrates how machine learning can significantly enhance manufacturing processes by predicting defects early, enabling proactive decision-making and cost optimization.

🙌 Acknowledgement

Thank you for reviewing this project!

# Overview
Developed a machine learning model to predict the likelihood of loan defaults using a dataset of over 250,000 records. This project focuses on handling extreme class imbalance and optimizing business-centric metrics like Recall over simple accuracy.

# Insights

* Top Predictors: Identified Age as the strongest driver of default, followed by high Interest Rates and low Income.

* Risk Segments: Discovered that borrowers without co-signers or dependents have default rates exceeding 12%.

# Key Achievements

* Imbalance Management: Handled a dataset where 88% of entries were non-defaults.
* Threshold Optimization: Implemented a custom 0.6 probability threshold to achieve a Recall of 0.48, prioritizing the identification of high-risk borrowers.

* Model Performance: Achieved 80% accuracy using the XGBoost algorithm.

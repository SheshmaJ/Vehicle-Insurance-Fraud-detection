# Vehicle-Insurance-Fraud-detection
# Business Requirements in Insurance Fraud Projects

Data Quality & Preprocessing

Handle missing values, incorrect entries, irrelevant columns.

Convert categorical values (like Y/N fraud labels) into usable numeric form.

Exploratory Data Analysis (EDA)

Summary statistics, distributions, outlier detection.

Visualizations to identify fraud patterns.

# Model Building & Evaluation

At least one baseline model (Logistic Regression).

Compare advanced model (Random Forest, XGBoost, etc.).

Handle class imbalance (SMOTE).

Model Metrics

Confusion matrix, classification report, ROC-AUC curve.

Focus on minimizing false negatives (missed frauds).

# Business Interpretability

# Conclusion
The XGBoost model is the best overall performer.

It delivers the highest AUC score, lowest estimated business cost, and best recall–precision trade-off.

Its ensemble boosting strategy captures subtle fraud patterns missed by simpler models.

It also maintains interpretability through feature importance analysis and offers reliable generalization on unseen claims.

In business terms, XGBoost detects more fraudulent claims while minimizing unnecessary investigations — maximizing cost savings and fraud prevention efficiency.

# Final Findings

XGBoost

Highest AUC Score (0.77): Demonstrates superior overall discrimination capability between fraudulent and legitimate claims

Best Business Performance: Lowest total cost ($265,000) by optimally balancing false negatives and false positives

Strong Fraud Recall (66%): Captures more actual fraud cases than other models, crucial for minimizing financial losses

Handles Imbalance Effectively: Built-in scale_pos_weight and tuning parameters address class imbalance without needing external sampling

Feature Importance Insights: Provides interpretable feature rankings that align with business intuition

Feature importance (which variables drive fraud).

Trade-off analysis: catching fraud vs. customer inconvenience.

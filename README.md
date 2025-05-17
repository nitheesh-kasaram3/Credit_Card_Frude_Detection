### Credit_Card_Frude_Detection
#  Problem Statement
Credit card fraud is a growing concern in the financial industry. The goal of this project is to detect potentially fraudulent transactions from a large dataset of credit card usage.
Note: The problem statement should only highlight the issue, not the proposed solution.

# Proposed System / Solution
We propose a machine learning-based fraud detection system that uses classification algorithms to accurately identify fraudulent transactions based on historical data.

# System Development Approach (Technology Used)
Programming Language: Python

Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn

Modeling Techniques: Logistic Regression, Decision Trees, Random Forest, XGBoost

IDE: Jupyter Notebook / Google Colab

Data: creditcard.csv (anonymized Kaggle dataset)

# Algorithm & Deployment
Algorithm Used: Random Forest (best performing)

Preprocessing: Data balancing using SMOTE, standardization

Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

Deployment: Not deployed yet (can be deployed using Flask/Streamlit)


![Screenshot 2025-05-18 013911](https://github.com/user-attachments/assets/2fbb3ccb-550c-4410-af89-9b188f2854a5)

![Screenshot 2025-05-18 014336](https://github.com/user-attachments/assets/cfd66b0e-cf18-41e2-bfe2-7535c8585bf5)
![Screenshot 2025-05-18 014232](https://github.com/user-attachments/assets/d6e44e8f-b43d-4860-83e0-12e94d433bc8)
![Screenshot 2025-05-18 014316](https://github.com/user-attachments/assets/6fc36bd9-75ab-4b4e-99d3-7c7d3de2ddd4)


# Result 
Insert output graphs and model performance screenshots here.
Examples:

![Screenshot 2025-05-18 014401](https://github.com/user-attachments/assets/c988bfaa-c4d7-465b-a90d-c5b7b9766d57)

Confusion matrix plot

ROC-AUC curve

Feature importance chart



# Conclusion
The trained model was able to detect fraudulent transactions with high precision and recall. It shows promise for integration into real-time transaction systems to prevent financial losses.


# Future Scope
Deploy the model as an API for real-time fraud detection.

Use deep learning models like LSTM or Autoencoders.

Continuously retrain the model with new data to improve performance.

# References
Kaggle Credit Card Dataset

scikit-learn documentation

Articles and tutorials from Medium, Towards Data Science, and Stack Overflow


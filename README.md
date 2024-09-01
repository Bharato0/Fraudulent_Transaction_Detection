# Fraudulent_Transaction_Detection
#### Fraudulent Transaction Detection Using Machine Learning 

### Project Title: Fraudulent Transaction Detection Using Machine Learning on Large-Scale Financial Data.
### Description:
- Developed a sophisticated fraudulent transaction detection system using machine learning techniques to identify suspicious activities within a large-scale financial dataset comprising over 6.3 million records. This project involved extensive data preprocessing, feature selection, and the application of advanced techniques to manage the dataset's size and complexity, which posed significant computational challenges on a CPU-based system.
- Key tasks included balancing the highly imbalanced dataset using Synthetic Minority Over-sampling Technique (SMOTE) to enhance model accuracy. Multiple machine learning algorithms, including Logistic Regression, Random Forest, and Gradient Boosting, were tested, with the Decision Tree Classifier emerging as the most effective model.
#### The Decision Tree model, trained on SMOTE-balanced data, demonstrated exceptional performance:
### •	Class 0 (Non-Fraudulent Transactions): Precision: 1.00, Recall: 1.00, F1-Score: 1.00
### •	Class 1 (Fraudulent Transactions): Precision: 0.61, Recall: 0.97, F1-Score: 0.75

### The model's high recall of 97% for fraudulent transactions was particularly noteworthy, highlighting its ability to detect the majority of fraudulent activities, thereby minimizing financial risk.
### Tools & Techniques: 
- Python, Pandas, Scikit-learn, SMOTE, Decision Tree, Logistic Regression, Random Forest, Gradient Boosting
### Impact: 
- Successfully created a robust and scalable fraudulent transaction detection model capable of processing vast amounts of financial data, achieving high accuracy and recall, and providing valuable insights for risk management and prevention of financial fraud.

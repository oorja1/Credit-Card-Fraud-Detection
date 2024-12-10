Overview:

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset includes transactional data with labels indicating whether each transaction is fraudulent or not. This project aims to build a predictive model to identify fraudulent transactions efficiently and accurately.

Features
- Data Cleaning and Preprocessing: Handling missing values, scaling features, and encoding categorical variables.
- Exploratory Data Analysis (EDA): Visualizing transaction patterns, distributions, and correlations to understand the dataset.
- Model Building: Training and evaluating machine learning models, including Logistic Regression, Random Forest, and Gradient Boosting.
- Performance Evaluation: Using metrics like Accuracy, Precision, Recall, F1-Score, and AUC-ROC to assess model performance.

Dataset
The dataset contains the following features:
- V1, V2, ..., V28: Principal components obtained using PCA.
- Time: The time elapsed between this transaction and the first transaction in the dataset.
- Amount: Transaction amount.
- Class: Target variable (1 = Fraudulent, 0 = Legitimate).

Project Structure
- data: Contains the dataset used for training and testing.
- notebooks: Jupyter notebooks for detailed exploration and modeling.
- src: Python scripts for data preprocessing, training, and evaluation.
- README.md: Overview and instructions for the project.

Steps
1.Load Dataset: Understand the data structure and contents.
2.Preprocess Data:
    - Handle missing and anomalous values.
    - Scale numerical features.
3.EDA:
    - Visualize distributions and relationships.
    - Investigate class imbalance.
4.Train Models:
    Compare performance across different algorithms.
5.Evaluate Models:
    Use evaluation metrics to identify the best-performing model.

Results
The Random Forest Classifier achieved the best performance with:
Accuracy: 98%
Precision: 95%
Recall: 96%
AUC-ROC: 0.99

Conclusion
This project demonstrates the application of machine learning to detect credit card fraud. By preprocessing the data, performing EDA, and leveraging machine learning models, we successfully identified fraudulent transactions with high accuracy.

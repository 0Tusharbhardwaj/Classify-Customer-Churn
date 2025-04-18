# Customer Churn Classification using Machine Learning

This project predicts whether a customer is likely to churn based on their demographics and service usage data using a Random Forest Classifier.

## 📌 Problem Statement

Businesses face a critical challenge in identifying customers who may stop using their services. Predicting churn allows companies to act proactively and improve customer retention.

## 🔍 Dataset

- The dataset contains information such as gender, senior citizen status, tenure, internet service, contract type, and more.
- Target variable: `Churn` (1 = Yes, 0 = No)

## 🧠 Techniques Used

- Label Encoding for categorical variables
- Median imputation for missing values
- Standardization of features using `StandardScaler`
- Train-Test Split (80-20)
- Machine Learning model: `RandomForestClassifier`
- Evaluation metrics: Accuracy, Confusion Matrix, Precision, Recall, F1-score

## 📊 Model Performance

- Accuracy: ~79.6%
- The model performs well on predicting non-churned customers and can be further optimized for churned ones.

## 🖼️ Output

Confusion matrix and classification report were generated to visualize and evaluate model performance.

## 📁 Files

- `churn_prediction.py` – Main Python script
- `5. Classify Customer Churn.csv` – Dataset used
- `confusion_matrix.png` – Output image of confusion matrix (to be added)
- `Customer_Churn_Report.docx` – Full project report

## 🚀 How to Run

1. Clone this repository
2. Install dependencies:  
   `pip install pandas seaborn matplotlib scikit-learn`
3. Run the script:  
   `python churn_prediction.py`

## 🙋 Developed By

**Tushar Sharma**  
B.Tech CSE-AI (Section D)  
KIET Group of Institutions, Ghaziabad  
Under the guidance of **Abhishek Shukla**

## 📚 References

- [scikit-learn documentation](https://scikit-learn.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)

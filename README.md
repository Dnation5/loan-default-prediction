# loan-default-prediction
Machine Learning project for predicting loan default risk using classification models.

---

## Project Structure

LoanDefaultRisjPrediction/ <-- project root
├── data/ # Raw dataset, Processed dataset, Updated dataset and dataset for tableau Visualization
├── notebooks/ # Jupyter notebooks
├── src/ # Python package with reusable functions
├── model / # saved model
├── images / # saved plots
├── reports / # Prosal, Final Report
├── requirements.txt
├── loandefault_evn / # project environment path
└── README.md


---

## Technologies Used

- Python 3.13.9
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## Features

1. **Data Loading & Preprocessing**
   - Drop unnecessary columns (`ID`)
   - Encode categorical variables (Ordinal Encoding & One-Hot Encoding)
   - Scale features (StandardScaler)

2. **Exploratory Data Analysis (EDA)**
   - Class distribution visualization
   - Correlation heatmaps

3. **Machine Learning Models**
   - **Logistic Regression** for baseline modeling
   - **Random Forest Classifier** for model comparison
   - **Gradient Boosting Classifier** for model comparison

4. **Evaluation**
   - Confusion matrix 
   - Recall, Precision, F1 Score
   - ROC_AUC
   - Feature coeffiencient for Logistic Regression

5. **Final Report**

    - See reports/final_report.pdf
   

---



# Customer Churn Analysis

This project focuses on analyzing customer churn data to identify patterns and predict the likelihood of customers leaving a service. Churn analysis helps businesses understand the reasons behind customer attrition and develop strategies to improve retention.

## 📊 Project Overview

The dataset contains customer information including demographic data, account details, service usage, and whether or not the customer has churned.

The goal is to:
- Perform exploratory data analysis (EDA)
- Identify key churn drivers
- Train a classification model to predict churn

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## 📁 Files

- `churnanalysis.ipynb` – Main notebook containing all code and analysis.
- `README.md` – Overview and instructions.

## 📌 Key Features

- **Data Cleaning:** Handled missing values and encoded categorical variables.
- **EDA:** Correlation heatmaps, distribution plots, and comparative analysis between churned and non-churned customers.
- **Modeling:** Used logistic regression and decision trees to classify churn.
- **Evaluation:** Accuracy, confusion matrix, precision/recall, and F1-score.

## ⚙️ How to Run

1. Clone this repository or download the notebook.
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
3. Open the notebook using Jupyter:
   ```bash
   jupyter notebook churnanalysis.ipynb
   ```

## 📈 Sample Output

- Classification report with metrics
- Visuals such as:
  - Correlation matrix
  - Churn distribution bar plots
  - Feature importance from models

## ✅ Results

The model identifies important features such as:
- Tenure
- Monthly Charges
- Contract type
- Internet service type

The decision tree model gave reasonable accuracy in detecting churners based on these variables.

## 🚀 Future Improvements

- Hyperparameter tuning
- Try ensemble models (Random Forest, XGBoost)
- Use SHAP values for explainability
- Deploy as a web app with Streamlit or Flask

## 👩‍💻 Author

Keisha Wadhwa

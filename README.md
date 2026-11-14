<p align="center">
  <img src="./images/wycliffe-adek.png" alt="Wycliffe Adek" width="180">
</p>

<h1 align="center">Wycliffe Adek</h1>

<h3 align="center">Bank Fraud Detection Using Machine Learning</h3>

<p align="center">
  Turning Transaction Data into Actionable Fraud Prevention Insights
</p>

<p align="center">
  <strong>Data Analyst | Applied Statistics | Machine Learning | Business Analytics</strong>
</p>

<p align="center">
  Python • Pandas • NumPy • Scikit-learn • XGBoost • Jupyter Notebook
</p>

<p align="center">
  <a href="https://github.com/Adek321">GitHub Profile</a> |
  <a href="https://github.com/Adek321/bank-fraud-detection">Project Repository</a>
</p>

---


## 1. About the Author

I am **Wycliffe Adek**, a data analyst with an academic background in Applied Statistics and experience in data analysis and monitoring and evaluation.

I am passionate about transforming raw data into meaningful insights that support better decision-making. My interests include statistical analysis, machine learning, predictive modelling and business analytics.

This project demonstrates the application of data analytics and machine learning to a real-world financial challenge: detecting potentially fraudulent transactions.

---

## 2. Project Overview

Financial fraud is a significant challenge for banks and financial institutions. Fraudulent transactions can result in financial losses, undermine customer confidence and expose institutions to operational risks.

This project focuses on analysing financial transaction data, identifying patterns associated with fraudulent activities and developing machine learning classification models to support fraud detection.

The project follows a data analysis and machine learning workflow, from data preparation and exploratory analysis to model development, evaluation and business recommendations.

## 3. Project Objectives

- Clean and prepare transaction data for analysis.
- Explore transaction patterns and identify unusual behaviour.
- Examine relationships between variables and potential fraud indicators.
- Develop and compare machine learning classification models.
- Evaluate model performance using appropriate metrics.
- Identify important predictors of fraudulent transactions.
- Recommend practical fraud prevention and monitoring strategies.

---

## 4. Explore the Project

Access the project materials directly from the links below.

| Project Resource | Description |
|---|---|
| [Jupyter Notebook](./Analysis1.ipynb) | Complete analysis and machine learning workflow |
| [Charts and Visualizations](./images/) | Explore the generated charts |
| [Data Tables and Results](./tables/) | Access exported CSV files |
| [Trained Machine Learning Model](./models/) | Access the saved model |
| [Requirements](./requirements.txt) | Python dependencies |

---

## 5. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to understand the transaction data and identify patterns that could help distinguish fraudulent transactions from legitimate ones.

The analysis explores:

- Distribution of fraudulent and legitimate transactions.
- Transaction amount patterns.
- Relationships between transaction variables.
- Correlation analysis.
- Unusual transaction behaviour.
- Potential indicators of fraudulent activities.

**Explore the analysis charts:** 

### Visual Analysis Gallery

Click any chart to view it in full size.

#### 1. Fraud Rate by Transaction Amount

[![Fraud Rate by Amount Bucket](./images/01_fraud_rate_by_amount_bucket.png)](./images/01_fraud_rate_by_amount_bucket.png)

#### 2. Outlier Handling

[![Outlier Handling](./images/02_outlier_handling.png)](./images/02_outlier_handling.png)

#### 3. Fraud Rate by Transaction Type

[![Fraud Rate by Transaction Type](./images/03_fraud_rate_by_transaction_type.png)](./images/03_fraud_rate_by_transaction_type.png)

#### 4. Time-Based Overview — Chart 1

[![Time Based Overview 1](./images/04_time-based_overview.png)](./images/04_time-based_overview.png)

#### 5. Time-Based Overview — Chart 2

[![Time Based Overview 2](./images/05_time-based_overview.png)](./images/05_time-based_overview.png)

#### 6. Time-Based Overview — Chart 3

[![Time Based Overview 3](./images/06_time-based_overview.png)](./images/06_time-based_overview.png)

#### 7. Correlation Check

[![Correlation Check](./images/07_correlation_check.png)](./images/07_correlation_check.png)

**More analysis outputs:** [Explore all charts](./images/) | [Explore exported tables](./tables/)

**Explore the exported results:** [Open the tables folder](./tables/)

---

## 6. Downloadable Analysis Results

The following CSV files contain exported data and analytical results generated during the project.

### Data Preparation and Exploration

| File | Description |
|---|---|
| [01. Loading Data](./tables/01_loading_data_table1.csv) | Initial data loading results |
| [02. Missing Values Check](./tables/02_checking_missing_values_table1.csv) | Missing-value assessment |
| [03. Time-Based Overview](./tables/03_time-based_overview_table1.csv) | Time-based analytical results |
| [04. Analysis Results](./tables/04_results_table1.csv) | Exported analysis results |

### Machine Learning Model Results

| File | Description |
|---|---|
| [05. XGBoost Results – Table 1](./tables/05_from_xgboost_import_xgbclassifier_table1.csv) | XGBoost model results |
| [06. XGBoost Results – Table 2](./tables/06_from_xgboost_import_xgbclassifier_table2.csv) | Additional XGBoost results |
| [07. Random Forest Results – Table 1](./tables/07_rf_tuned_randomforestclassifier_table1.csv) | Tuned Random Forest results |
| [08. Random Forest Results – Table 2](./tables/08_rf_tuned_randomforestclassifier_table2.csv) | Additional Random Forest results |
| [09. Logistic Regression Results – Table 1](./tables/09_lr_tuned_logisticregression_table1.csv) | Tuned Logistic Regression results |
| [10. Logistic Regression Results – Table 2](./tables/10_lr_tuned_logisticregression_table2.csv) | Additional Logistic Regression results |

**All exported tables:** 

---

## 6. Machine Learning Approach

This project applies supervised machine learning classification techniques to predict potentially fraudulent transactions.

The models explored include:

1. Logistic Regression
2. Random Forest
3. XGBoost

The modelling workflow covers:

- Data preparation and preprocessing.
- Feature selection and preparation.
- Model training.
- Model comparison.
- Prediction and classification.
- Model performance evaluation.

### Model Evaluation

Fraud detection datasets are often highly imbalanced. This means fraudulent transactions may represent only a very small proportion of all transactions.

For this reason, accuracy alone is not sufficient to evaluate a fraud detection model.

The evaluation considers:

- Precision
- Recall
- F1-score
- ROC-AUC
- Precision-Recall AUC
- Confusion Matrix

The final performance results should be interpreted using an independent test dataset.

---

## 7. Business Recommendations

Machine learning predictions can support financial institutions in strengthening their fraud prevention processes.

Potential recommendations include:

**1. Real-time transaction monitoring**  
Flag suspicious transactions for further review.

**2. Risk-based authentication**  
Apply additional verification to transactions with elevated fraud risk.

**3. Fraud investigation**  
Prioritize suspicious transactions for investigation.

**4. Continuous model monitoring**  
Monitor false positives, missed fraud cases and changes in transaction behaviour.

**5. Model improvement**  
Regularly validate and update models as new transaction data becomes available.

---

## 8. Project Structure


## 9. Project Architecture

The repository is organised to make the analysis workflow, visual outputs, exported results and trained machine learning model easy to navigate.

| Component | Description |
|:---|:---|
| 📓 [Analysis1.ipynb](./Analysis1.ipynb) | Main Jupyter Notebook containing data preparation, exploratory analysis, model development and evaluation |
| 📊 [images/](./images/) | Seven visualizations generated during the analysis |
| 📁 [tables/](./tables/) | Ten exported CSV files containing analytical results and model outputs |
| 🤖 [models/](./models/) | Trained fraud detection model |
| ⚙️ [requirements.txt](./requirements.txt) | Python libraries required to reproduce the project |
| 📝 [.gitignore](./.gitignore) | Specifies files excluded from version control |
| 📖 [README.md](./README.md) | Project documentation and navigation guide |

### Project Workflow

```text
Transaction Dataset
        |
        ▼
Data Loading & Inspection
        |
        ▼
Data Cleaning & Preparation
        |
        ▼
Exploratory Data Analysis
        |
        ▼
Feature Preparation
        |
        ▼
Machine Learning Modelling
        |
        ▼
Model Evaluation & Comparison
        |
        ▼
Fraud Detection Insights
        |
        ▼
Business Recommendations
```


---

## 9. Technologies Used

| Technology | Application |
|---|---|
| Python | Main programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning and evaluation |
| XGBoost | Gradient boosting classification |
| Jupyter Notebook | Interactive analysis |

---

## 10. How to Run the Project

Clone the repository:

```bash
git clone https://github.com/Adek321/bank-fraud-detection.git
```

Navigate to the project directory:

```bash
cd bank-fraud-detection
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch the notebook:

```bash
jupyter notebook Analysis1.ipynb
```

**Dataset note:** The original transaction dataset is not included in this repository. An authorized copy of the dataset is required to reproduce the analysis. Configure the correct dataset path in the notebook before running it.

---

## 11. Limitations and Future Improvements

Future improvements may include:

- Further validation of the final model on an independent test dataset.
- Investigating false-positive predictions.
- Exploring additional feature engineering techniques.
- Testing alternative classification algorithms.
- Developing an interactive fraud monitoring dashboard.
- Deploying the model through an application programming interface.
- Monitoring model performance as transaction patterns change.

---

## 12. Author and Contact

**Wycliffe Adek**  
Data Analyst | Applied Statistics | Machine Learning | Business Analytics

**GitHub:** [Adek321](https://github.com/Adek321)

**Project Repository:** [Bank Fraud Detection](https://github.com/Adek321/bank-fraud-detection)

---

*Transforming Data into Decisions.*

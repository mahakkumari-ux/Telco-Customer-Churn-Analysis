# 📊 Telco Customer Churn Analysis Using Machine Learning

**Author:** Mahak Kumari
**Domain:** Data Analytics | Machine Learning | Artificial Intelligence
**Program:** Data Analytics with AI Academic Internship

## 📌 Project Overview

Customer churn is a major challenge for telecommunications companies. Understanding why customers leave helps businesses improve customer satisfaction, strengthen retention strategies, and make data-driven decisions.

This project analyzes customer churn data using Python, exploratory data analysis (EDA), and machine learning. It compares Logistic Regression and Random Forest models to identify a suitable approach for predicting customer churn.

## 🎯 Project Objectives

* Analyze customer data and identify churn patterns.
* Perform data cleaning and preprocessing.
* Explore relationships between customer characteristics and churn.
* Build and evaluate machine learning classification models.
* Compare models using accuracy, precision, recall, F1-score, and ROC-AUC.
* Provide data-driven recommendations to support customer retention.

## 📂 Dataset

The project uses the **Telco Customer Churn** dataset, containing customer demographics, subscribed services, contract details, billing information, tenure, and churn status.

**Dataset source:** [Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The original dataset contains 7,043 customer records and 21 columns.

## 🛠️ Technologies Used

* **Python** — programming and analysis
* **Pandas & NumPy** — data manipulation and preprocessing
* **Matplotlib & Seaborn** — data visualization
* **Scikit-learn** — machine learning and model evaluation
* **Google Colab / Jupyter Notebook** — development environment

## 🔍 Project Workflow

1. **Data Loading:** Load the dataset and inspect its structure.
2. **Data Cleaning:** Handle missing values and prepare data for analysis.
3. **Exploratory Data Analysis:** Examine churn distribution and customer characteristics.
4. **Feature Engineering and Preprocessing:** Prepare numerical and categorical features for machine learning.
5. **Model Building:** Train Logistic Regression and Random Forest classifiers.
6. **Model Evaluation:** Compare performance using multiple evaluation metrics.
7. **Feature Analysis:** Examine model-related feature importance to understand patterns associated with churn.
8. **Recommendations:** Identify potential opportunities to improve customer retention.

## 🤖 Machine Learning Models

* Logistic Regression
* Random Forest Classifier

## 📈 Model Performance

The following results were obtained from the project's model comparison:

| Evaluation Metric | Logistic Regression | Random Forest |
| ----------------- | ------------------: | ------------: |
| Accuracy          |              73.24% |        77.64% |
| Precision         |              49.75% |        57.25% |
| Recall            |              79.14% |        62.30% |
| F1-Score          |              61.09% |        59.67% |
| ROC-AUC           |              0.8420 |        0.8338 |

**Key observation:** Random Forest achieved higher accuracy and precision, while Logistic Regression achieved higher recall and ROC-AUC. Logistic Regression was selected as the preferred model in this project based on ROC-AUC.

## 💡 Key Business Insights

* Customer tenure and contract type are important factors to investigate when analyzing churn.
* Month-to-month contracts and internet service categories showed notable associations with the model's churn predictions.
* Customer retention efforts can focus on understanding the needs of customers who may be more likely to leave.
* Businesses should evaluate both churn detection and false-positive rates before choosing a model for operational use.

These observations describe patterns in this dataset and should not be interpreted as proof of causation.

## ▶️ How to Run the Project

1. Clone or download this repository.

2. Download the dataset from the Kaggle source linked above.

3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `IBM_Analyst_Certification_Project_py.ipynb` in Google Colab or Jupyter Notebook.

5. Upload the dataset or update the notebook's file path to match your environment.

6. Run the notebook cells in order to reproduce the analysis and model evaluation.

## 📁 Repository Contents

* `IBM_Analyst_Certification_Project_py.ipynb` — analysis, visualizations, preprocessing, and machine learning workflow.
* `MahakKumari_ProjectReport.docx` — detailed project report.
* `requirements.txt` — Python dependencies.

## 🚀 Future Improvements

* Tune model hyperparameters to improve performance.
* Evaluate class imbalance handling and probability calibration.
* Use cross-validation for more robust model comparison.
* Explore additional customer behavior features.
* Develop a dashboard to monitor churn patterns and retention metrics.

## 📝 Conclusion

This project demonstrates how data analytics and machine learning can be applied to customer churn analysis. By comparing Logistic Regression and Random Forest, it highlights the importance of evaluating multiple metrics rather than relying on accuracy alone.

The analysis provides a foundation for further investigation into customer retention and data-driven business decisions.

---

**If you find this project useful, feel free to explore the notebook and project report.**

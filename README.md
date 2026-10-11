# InsightIQ — E-Commerce Analytics & Predictive Intelligence

An end-to-end data analytics project that transforms online retail transactions into actionable business insights using Python, SQL, machine learning, and Power BI.

## Project Overview

InsightIQ analyzes e-commerce sales performance, identifies valuable customer segments, and predicts the likelihood of repeat purchases. The project combines data cleaning, exploratory analysis, SQL queries, customer segmentation, predictive modeling, and interactive dashboard reporting.

## Business Objectives

- Analyze revenue, orders, customers, and average order value.
- Identify top-performing products and countries.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Explore customer repurchase behavior using a Random Forest classifier.
- Present business insights through an interactive Power BI dashboard.

## Tools & Technologies

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Database & Queries:** SQL, SQLite
- **Machine Learning:** Scikit-learn, K-Means clustering, Random Forest
- **Visualization:** Power BI, Matplotlib, Seaborn
- **Development:** Jupyter Notebook, Git, GitHub

## Project Workflow

1. **Data Cleaning:** Handle missing customer IDs, invalid quantities, and non-positive prices.
2. **Exploratory Data Analysis:** Examine sales trends, products, customers, and countries.
3. **SQL Analysis:** Calculate key business metrics and summarize sales performance.
4. **Customer Segmentation:** Apply RFM analysis and K-Means clustering to group customers.
5. **Predictive Modeling:** Train a Random Forest model to estimate repeat-purchase behavior.
6. **Dashboard Development:** Build interactive Power BI reports for business users.

## Key Business Insights

- Total revenue was approximately **8.91 million** in the dataset's currency.
- The analysis covered approximately **4,338 customers**.
- Average order value was approximately **480.87** in the dataset's currency.
- Customer segmentation identified distinct groups, including at-risk customers and high-value loyal customers.
- The repeat-purchase model achieved approximately **68% accuracy** on the test data.

*Metrics reflect this project's current analysis and should be interpreted in the context of the dataset and model evaluation.*

## Power BI Dashboard

The report contains three pages:

1. **Executive Overview** — revenue, customers, orders, monthly trends, and top-performing products and countries.
2. **Customer Intelligence** — customer segments, RFM metrics, and recency-versus-monetary analysis.
3. **Predictive Analytics** — model performance metrics and feature importance.

## Project Files

- `InsightIQ_Analysis.ipynb` — analysis and modeling notebook.
- `business_analysis.sql` — business analysis queries.
- `clean_sales_sample.csv` — sample of the cleaned sales data.
- `customer_segments.csv` — customer segmentation results.
- `feature_importance.csv` — model feature importance.
- `model_metrics.csv` and `prediction_metrics.csv` — model evaluation results.
- `InsightIQ.pbix` — Power BI report.
- `requirements.txt` — Python dependencies.

## How to Run

1. Clone or download this repository.
2. Install the required dependencies:

   `pip install -r requirements.txt`

3. Open `InsightIQ_Analysis.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order, adjusting file paths if necessary.
5. Open `InsightIQ.pbix` using Power BI Desktop to explore the dashboard.

## 📊 Power BI Dashboard Preview

### 1. Executive Overview
![Executive Overview](Executive_Overview.png)

### 2. Customer Intelligence
![Customer Intelligence](Customer_Intelligence.png)

### 3. Predictive Analytics
![Predictive Analytics](Predictive_Analysis.png)

## 📁 Power BI Report

Download the report file from this repository: [InsightIQ_Final.pbix](InsightIQ_Final.pbix)

Open it using Power BI Desktop to explore the interactive dashboard.

## Future Improvements

- Improve predictive model performance through feature engineering and hyperparameter tuning.
- Add automated data refresh and dashboard updates.
- Deploy the analytics workflow as a web application.

## Author

**Abhinaya Galipelli**  
Computer Science Engineering Graduate | Aspiring Data Analyst

GitHub: [Abhinayahub](https://github.com/Abhinayahub)

# trace_final_project

# Online Retail Sales Prediction Project

## Overview

This project uses machine learning to predict future sales and analyze customer purchasing behavior from e-commerce transaction data. The goal is to help businesses improve revenue forecasting and better understand their customers.

---

## Dataset

This project uses the Online Retail Dataset from Kaggle:
https://www.kaggle.com/datasets/carrie1/ecommerce-data

### Dataset Details

* ~541,000 transactions
* Features include InvoiceNo, StockCode, Quantity, UnitPrice, CustomerID, Country, and InvoiceDate
* Data represents purchases from a UK-based online retailer

### Dataset Setup Instructions

1. Download the dataset from the link above
2. Extract the `.zip` file
3. Rename the file to:
   online_retail.csv
4. Place it in:
   data/raw/

---

## Project Structure

online-retail-ml-project/
├── README.md
├── final_project_draft.ipynb
├── data/
│   ├── raw/
│   └── processed/
├── .gitignore
└── requirements.txt

---

## How to Run the Project

1. Clone the repository:
   git clone YOUR_REPO_URL

2. Navigate into the project folder:
   cd online-retail-ml-project

3. Install dependencies:
   pip install -r requirements.txt

4. Open the notebook:
   final_project_draft.ipynb

5. Run all cells

---

## Machine Learning Models

* Random Forest Regression
  Predicts customer spending using engineered features (Recency, Frequency)

* Time Series Forecasting
  Predicts future sales trends using historical transaction data

---

## Current Results

* Data cleaned (removed missing CustomerID, returns, invalid prices)
* Feature engineering completed (RFM features: Recency, Frequency, Monetary)
* Two models implemented and evaluated
* Time series model performs better for forecasting sales trends

---

## Future Improvements

* Add additional engineered features (seasonality, day-of-week trends)
* Perform hyperparameter tuning
* Test advanced models (Gradient Boosting, ARIMA)
* Build interactive dashboard for business use



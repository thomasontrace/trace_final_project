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

## Results
| Model | RMSE | MAE | R² |
|------|------|------|------|
| Random Forest | 40.29 | 7.38 | 0.995 |
| Time Series | 5569.66 | 4564.68 | -0.085 |

## Key Insights
- Customer-level features significantly outperform time-based models
- Purchase behavior patterns are strong predictors of spending
- Time series patterns are highly volatile and less useful

## Recommendation
Use the Random Forest model for predicting customer spending and guiding marketing strategies.






# Customer Lifetime Value (CLV) Prediction

A Machine Learning project to predict the **Customer Lifetime Value (CLV)** using past transactional data. This helps businesses identify high-value customers and make informed marketing and sales decisions.

---

## Objective

To build an AI/ML model that can estimate the future value a customer will bring based on their historical purchase behavior.

---

##  Dataset Overview

The dataset typically contains:

| Column Name    | Description                                 |
|----------------|---------------------------------------------|
| CustomerID     | Unique customer identifier                  |
| InvoiceNo      | Invoice number for a transaction            |
| InvoiceDate    | Date of the transaction                     |
| Quantity       | Number of items purchased                   |
| UnitPrice      | Price per item                              |
| Country        | Customer's country                          |

---

## Technologies Used

- Python
- Pandas, NumPy – Data manipulation
- Matplotlib, Seaborn – Visualization
- Scikit-learn – Machine Learning models

---

## Key Features

- Data cleaning and preprocessing
- Feature engineering (e.g. Total Spent, Total Purchases)
- CLV formula implementation
- Model training using Linear Regression
- Model evaluation (R² score)
- CLV prediction for new customers

---

## How It Works

1. **Preprocess the Data**  
   Handle missing values and calculate Total Price.

2. **Feature Engineering**  
   Aggregate customer data into meaningful metrics.

3. **CLV Estimation**  
   Estimate lifetime value using a business-defined multiplier.

4. **Model Training**  
   Train a regression model on historical data.

5. **Predict New CLV**  
   Use the model to forecast future value of customers.

---

## How to Run

```bash
# Step 1: Clone the repo
git clone https://github.com/your-username/clv-prediction.git
cd clv-prediction

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the script
python clv_prediction.py


#Visualization
Python 3.7+
pandas
numpy
scikit-learn
matplotlib
seaborn


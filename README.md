# Customer Lifetime Value Prediction

This project predicts the lifetime value (LTV) of customers using transactional data and machine learning.

🧠 We use RFM features (Recency, Frequency, Monetary) and AOV (Average Order Value) to train an XGBoost regression model that estimates how much value a customer will generate.

## 🔧 Tools & Technologies

- Python (Pandas, NumPy, XGBoost, Scikit-learn)
- Jupyter Notebook
- Power BI (for dashboard)
- Dataset: Online Retail (UCI)

## 🚀 Project Workflow

- Cleaned and preprocessed e-commerce data
- Engineered RFM & AOV features
- Trained an XGBoost model to predict LTV
- Exported predictions to CSV
- Built a Power BI dashboard to visualize:
  - Top customers
  - LTV distribution
  - Average KPIs (LTV, Frequency, Recency, AOV)

## 📊 Dashboard

Power BI report includes:

- Bar chart of top LTV customers
- LTV distribution histogram
- KPI cards
- Segment-based slicer (High / Medium / Low)

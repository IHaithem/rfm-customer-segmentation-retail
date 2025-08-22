# RFM Customer Segmentation for Online Retail

This project applies RFM (Recency, Frequency, Monetary) analysis to segment customers from the Online Retail dataset. It includes data preprocessing, scoring logic, customer classification, and actionable business strategies based on segment behavior.

## 📊 Project Structure

- `online retail/`: Raw and cleaned datasets
- `task3/`: Step-by-step analysis in Jupyter format
- `README.md`: Project overview and documentation

## 🔍 Methodology

1. **Data Cleaning**: Removed nulls, filtered valid transactions, and standardized formats.
2. **RFM Scoring**: Calculated Recency, Frequency, and Monetary values per customer.
3. **Segmentation**: Mapped RFM scores to customer segments using quantiles and rules.
4. **Strategic Recommendations**: Proposed marketing actions for each segment.

## 🧠 Key Segments

| Segment          | Description                          |
|------------------|--------------------------------------|
| Champions        | Recent, frequent, high spenders      |
| Loyal Customers  | Frequent buyers with strong value    |
| Big Spenders     | High monetary value, less frequent   |
| At Risk          | Previously active, now disengaged    |
| Others           | Low engagement or low spend          |

## 📈 Business Use Cases

- Targeted email campaigns
- Loyalty program design
- Churn prevention strategies
- Upselling and cross-selling

## 🛠 Tools Used

- Python (Pandas, NumPy)
- Jupyter Notebook
- Markdown (for documentation)

## 📁 Dataset

- Source: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Format: Excel (.xlsx)


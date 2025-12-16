# Mutual Fund Performance Analysis (EDA)

## 📌 Project Overview
This project performs an exploratory data analysis (EDA) of mutual fund performance using a comprehensive dataset of Indian mutual funds. The analysis focuses on understanding long-term return behavior, cost structures, and risk-adjusted performance metrics that are critical for informed investment decision-making.

---

## 🎯 Problem Statement
Retail investors often choose mutual funds based on recent returns without adequately considering risk, expense ratios, or long-term consistency. This project aims to analyze mutual fund performance through both return-based and risk-adjusted metrics to provide a more holistic evaluation framework.

---

## 🗂️ Dataset
- **Source**: Publicly available mutual fund dataset
- **Observations**: Multiple mutual fund schemes
- **Key Features**:
  - 1-Year, 3-Year, and 5-Year Returns
  - Expense Ratio
  - Standard Deviation
  - Sharpe Ratio
  - Alpha

The dataset is located in the `data/` directory.

---

## 🧪 Methodology
1. Data loading and inspection
2. Column standardization and cleaning
3. Missing value imputation using pipelines
4. Exploratory data analysis using:
   - Boxplots
   - Histograms with KDE
   - Scatter plots for risk vs return analysis
5. Interpretation of financial metrics

---

## 📊 Key Insights
- Mutual fund returns exhibit significant variability, with noticeable outliers across 1-year, 3-year, and 5-year horizons.
- Expense ratios are right-skewed, indicating that most funds operate at lower costs while a small subset incurs high expenses.
- Funds with higher Sharpe ratios generally tend to exhibit higher 5-year returns, though the relationship is not strictly linear.
- Risk-adjusted metrics provide better comparative insights than absolute returns alone.

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Pipelines, Imputers)
- Jupyter Notebook

---

## 📁 Project Structure

mutual-fund-performance-analysis/
│
├── data/
│ └── comprehensive_mutual_funds_data.csv
│
├── notebooks/
│ └── mutual_fund_eda.ipynb
│
└── README.md


---

## 🚀 Future Scope
- Fund category-wise performance comparison
- Clustering of mutual funds based on risk-return profiles
- Integration of rolling returns for consistency analysis

---

## 📌 Conclusion
This project demonstrates how exploratory data analysis combined with financial metrics can uncover meaningful insights into mutual fund performance, supporting more informed investment decisions.

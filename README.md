# E-commerce Business Analytics — Customer Behavior & Revenue Optimization
A complete e-commerce analytics workflow — uncover KPIs, customer retention patterns, and RFM segments with Python. Turn raw transactions into actionable insights for revenue growth.

## 📌 Objective
This project builds a complete analytics workflow for an e-commerce business using a synthetic dataset. The goal is to uncover revenue drivers, customer behavior patterns, and actionable insights for retention and growth.

---

## 📝 Problem Statement
E-commerce businesses generate massive amounts of transactional data, but:
- KPIs are often scattered and inconsistent.
- Retention metrics are unclear.
- Customer segmentation is either too broad or too manual.
- Budget allocation decisions are made without evidence.

This project solves those challenges by simulating realistic data and building a reproducible analytics pipeline.

---

## ⚙️ Technologies Used
- **Python**: Core analysis
- **pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn, Plotly**: Visualization (static & interactive)
- **SciPy**: Statistical testing
- **scikit-learn**: Prepared for clustering/advanced modeling
- **Jupyter Notebook**: Development environment

---

## 🔍 Analysis Performed
1. **Exploratory Data Analysis (EDA)**
   - Data overview, types, missing values
   - Summary statistics

2. **KPI Tracking**
   - Revenue, profit, margins
   - Average Order Value (AOV), Purchase Frequency, Customer Lifetime Value (proxy)
   - MoM Revenue Growth

3. **Category & Channel Analysis**
   - Top-performing categories
   - Acquisition channel profitability

4. **Cohort & Retention Analysis**
   - Cohort tables by first purchase month
   - Active user retention patterns

5. **RFM Segmentation**
   - Recency, Frequency, Monetary scoring
   - Segments: Champions, At Risk, Loyalists, etc.

6. **Statistical Testing**
   - T-tests/ANOVA to compare AOV across segments

---

## 📊 Key Business Questions Answered
- What drives revenue and profit today?
- Who are our most valuable customers?
- How do we measure and improve retention?
- Which acquisition channels deliver the most value?
- How do we identify and win back at-risk customers?

---

## 💡 Pain Points Solved
- Provides a **single source of truth** for KPIs.
- Enables **data-driven budget allocation**.
- Surfaces **retention bottlenecks** early.
- Makes segmentation **actionable and repeatable**.
- Converts a one-off analysis into a **reproducible framework**.

---

## ✅ Results & Recommendations
- **Revenue Optimization**: Prioritize high-margin categories, manage discount levels.
- **Retention**: Launch loyalty perks for “Champions”; reactivation offers for “At Risk.”
- **Channel Strategy**: Allocate more budget to high-ROI channels; test personalization by acquisition source.

---

## 🚀 How to Run
### Setup
```bash
git clone <your-repo-url>
cd ecommerce-analytics
pip install -r requirements.txt

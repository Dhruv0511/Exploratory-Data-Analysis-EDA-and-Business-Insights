# 📊 Exploratory Data Analysis (EDA) and Business Insights

## 🧩 Overview

This repository showcases a collection of **Exploratory Data Analysis (EDA)** and **Business Analytics** projects across multiple domains — **finance**, **retail**, **entertainment**, and **marketing**.

Each project demonstrates a full data-analytics workflow:

> **Data Cleaning → Exploration → Visualization → Statistical Analysis → Insights & Recommendations**

Some projects also extend into **predictive modeling** using machine learning.

---

## 🗂️ Repository Structure

| Folder / File                           | Description                                                |
| --------------------------------------- | ---------------------------------------------------------- |
| 📁 `Stock Market Portfolio/`            | Stock data analysis using yFinance                         |
| 📁 `Netflix Content Strategy Analysis/` | Analysis of Netflix’s 2023 viewership and release patterns |
| 📁 `Adidas Web Store/`                  | Retail pricing analysis across countries                   |
| 📁 `Customer Segmentation/`             | Customer grouping using K-Means clustering                 |
| 📁 `Customer Lifetime Value/`           | CLV calculation and business value prediction              |

---

## 🧾 Projects Overview

### 1️⃣ Stock Market Portfolio Analysis

**Files:** `Stock Market Portfolio.ipynb`, `Stock Market Portfolio.pdf`
**Domain:** Finance & Investment
**Category:** 🧠 *EDA & Diagnostic Analytics*
**Tools:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`

**Highlights:**

* Downloads stock data for **AAPL, AMZN, META, MSFT, TSLA, GOOGL**.
* Computes **50-day** and **200-day moving averages**.
* Analyzes **daily returns**, **volatility**, and **Sharpe ratios**.
* Visualizes **closing prices**, **correlation heatmaps**, and **return distributions**.

📈 *Key Insight:* Tech stocks show strong inter-correlation, with varying risk-adjusted performance.

---

### 2️⃣ Netflix Content Strategy Analysis

**Files:** `Netflix Content Strategy Analysis.ipynb`, `Netflix Content Strategy Analysis.pdf`, `netflix_content_2023.csv`
**Domain:** Media & Entertainment
**Category:** 🧠 *EDA & Trend Analysis*
**Tools:** `pandas`, `plotly`, `numpy`, `datetime`

**Highlights:**

* Explores **global content** and **viewership data for 2023**.
* Compares **shows vs. movies** and **language-based viewership**.
* Identifies **seasonal**, **monthly**, and **weekday** release patterns.
* Detects spikes in **holiday releases** (e.g., Christmas, Valentine’s Day).

📺 *Key Insight:* Shows dominate viewership; Friday releases maximize engagement.

---

### 3️⃣ Adidas Web Store Analysis

**Files:** `Adidas Web Store.ipynb`, `Adidas Web Store.pdf`, `country_dim.csv`, `shoes_dim.csv`, `shoes_fact.csv`
**Domain:** E-Commerce / Retail
**Category:** 📈 *EDA + Inferential Statistics*
**Tools:** `pandas`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`

**Highlights:**

* Merges multi-source Adidas datasets (product, country, price).
* Standardizes pricing by converting all currencies to **Euros**.
* Cleans inconsistent categories and merges metadata (color, gender).
* Uses **heatmaps** and **boxplots** to compare price variation by **country**, **gender**, and **category**.
* Performs **ANOVA and Tukey HSD** tests to confirm significant price differences.

👟 *Key Insight:* US prices are significantly higher; BE and DE have similar price levels.

---

### 4️⃣ Customer Segmentation Using Unsupervised Machine Learning

**Files:** `Customer Segmentation Using Unsupervised Machine Leaning.ipynb`, `new.csv`
**Domain:** Marketing Analytics
**Category:** 🤖 *EDA + Predictive Modeling (Clustering)*
**Tools:** `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

**Highlights:**

* Performs **feature scaling** and **K-Means clustering**.
* Determines **optimal clusters** using the **elbow method**.
* Profiles customers by income, spending score, and engagement.

🤓 *Key Insight:* Clear segmentation enables targeted marketing strategies and personalized offers.

---

### 5️⃣ Customer Lifetime Value (CLV) Analysis

**Files:** `CUSTOMER LIFE TIME VALUE ANALYSIS.ipynb`, `customer_acquisition_data.csv`
**Domain:** Business Intelligence / Marketing
**Category:** 💰 *Predictive & Prescriptive Analytics*
**Tools:** `pandas`, `numpy`, `matplotlib`, `seaborn`

**Highlights:**

* Computes **Average Order Value**, **Purchase Frequency**, and **Retention Rate**.
* Estimates **Customer Lifetime Value (CLV)** across segments.
* Visualizes **revenue concentration** and **customer profitability**.

📊 *Key Insight:* A small percentage of high-value customers drives a majority of total revenue.

---

## 🧮 Analytical Classification

| Project                  | Domain        | Type of Analytics            |
| ------------------------ | ------------- | ---------------------------- |
| Stock Market Portfolio   | Finance       | Descriptive / Diagnostic     |
| Netflix Content Strategy | Entertainment | Descriptive / Diagnostic     |
| Adidas Web Store         | Retail        | Diagnostic / Inferential     |
| Customer Segmentation    | Marketing     | Predictive (Unsupervised ML) |
| Customer Lifetime Value  | Marketing     | Predictive / Prescriptive    |

---

## ⚙️ Installation & Setup

Run the following to install dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn yfinance scipy statsmodels
```

To open any notebook:

```bash
jupyter notebook
```

---

## 🧠 Skills Demonstrated

* Data Cleaning & Preparation
* Exploratory Data Analysis (EDA)
* Data Visualization (Seaborn, Plotly, Matplotlib)
* Statistical Inference (ANOVA, Hypothesis Testing)
* Predictive Modeling (K-Means Clustering, CLV Estimation)
* Business Interpretation & Insight Communication

---

## 📈 Future Enhancements

* Add **interactive dashboards** (Streamlit or Power BI).
* Automate data retrieval with APIs.
* Incorporate **forecasting models** (ARIMA, Prophet).
* Develop **PowerPoint reports** from analysis outputs.

---

## 👨‍💻 Author

**Data Analyst:** Dhruv Kotecha
**Tools:** Python, Jupyter Notebook, Pandas, Seaborn, Plotly, Scikit-learn
**Focus Areas:** EDA • Data Visualization • Machine Learning • Business Analytics

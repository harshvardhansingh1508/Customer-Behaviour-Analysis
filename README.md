# Customer Behaviour Analysis

## 📌 Project Overview

This project focuses on analyzing customer transaction and behavioral data to identify **customer segments, purchasing patterns, revenue drivers, and potential churn risks**.

The analysis was performed using Python and popular data analysis libraries to generate actionable business insights that can help improve **customer retention, engagement, and revenue**.

---

## 🎯 Objectives

* Analyze customer purchasing behavior.
* Perform **RFM (Recency, Frequency, Monetary) analysis**.
* Segment customers based on their purchasing behavior.
* Identify high-value and at-risk customers.
* Analyze customer retention and repeat purchasing patterns.
* Identify revenue-generating customer segments.
* Provide actionable business recommendations.

---

## 📊 Dataset

The dataset contains approximately **250,000 customer transaction records** with **13 columns** related to customer demographics, transactions, purchases, and behavior.

**Dataset Source:** Kaggle – Customer Behavior Analysis

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical analysis
* **Matplotlib** – Data visualization
* **Google Colab** – Development environment
* **GitHub** – Project repository and version control

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preprocessing

* Loaded and inspected the dataset.
* Checked dataset dimensions and data types.
* Identified missing values and duplicates.
* Converted date-related columns into appropriate formats.
* Prepared the dataset for further analysis.

### 2. Exploratory Data Analysis

Analyzed:

* Customer purchasing trends
* Order frequency
* Revenue distribution
* Product/category performance
* Customer purchase patterns
* Repeat customer behavior

### 3. RFM Analysis

RFM analysis was performed using:

* **Recency** – How recently a customer made a purchase.
* **Frequency** – How frequently a customer purchases.
* **Monetary** – How much revenue a customer generates.

Customers were segmented into:

* 🏆 Champions
* 💎 Loyal Customers
* 🌱 Potential Loyalists
* ⚠️ At Risk
* 🔴 Lost Customers

---

## 📈 Key Insights

| Metric                     |              Result |
| -------------------------- | ------------------: |
| Total Records              |             250,000 |
| Repeat Customer Rate       |              96.67% |
| Largest Customer Segment   | Potential Loyalists |
| Highest Revenue Segment    |           Champions |
| Highest Churn-Risk Segment |           Champions |
| Champions Churn Rate       |              20.59% |

### Customer Segment Distribution

* **Potential Loyalists:** 13,357
* **Loyal Customers:** 13,337
* **Champions:** 9,583
* **At Risk:** 7,102
* **Lost Customers:** 6,282

### Champions

Champions generated the highest monetary value, with an average monetary value of approximately **22,506.30**.

However, this segment also showed a relatively high churn risk, making customer retention an important priority.

---

## 💡 Business Recommendations

### 🏆 Protect Champions

Provide Champions with:

* Loyalty rewards
* Exclusive offers
* Personalized recommendations
* Early access to new products

### 🌱 Convert Potential Loyalists

Use:

* Targeted discounts
* Personalized marketing campaigns
* Product recommendations
* Loyalty program incentives

to encourage Potential Loyalists to become Loyal Customers.

### 💎 Engage Loyal Customers

Maintain engagement through:

* Personalized communication
* Reward programs
* Cross-selling and upselling
* Special customer offers

### ⚠️ Win Back At-Risk Customers

Launch targeted win-back campaigns using:

* Limited-time discounts
* Personalized offers
* Reminder campaigns
* Re-engagement emails

### 🔴 Recover Lost Customers

Identify previously valuable customers and test targeted reactivation campaigns.

---

## 📂 Project Structure

```text
Customer-Behaviour-Analysis/
│
├── Customer_Behaviour_Analysis_Harshvardhan_Singh.ipynb
├── Customer_Behaviour_Analysis_Report_Harshvardhan_Singh.pdf
├── README.md
```

> The exact file names may vary depending on the final files uploaded to the repository.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Open the notebook

Open:

```text
Customer_Behaviour_Analysis.ipynb
```

using **Google Colab** or **Jupyter Notebook**.

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib
```

### 4. Run the notebook

Execute the cells sequentially to reproduce the analysis and visualizations.

---

## 📊 Project Outcome

The analysis provides a data-driven understanding of customer behavior and identifies important customer segments based on their purchasing activity.

The findings can help businesses:

* Improve customer retention
* Identify high-value customers
* Reduce churn
* Increase customer lifetime value
* Personalize marketing campaigns
* Improve overall revenue performance

---

## 👨‍💻 Author

**Harshvardhan Singh**

B.Tech Student | Data Analytics & Data Engineering Enthusiast

---

## ⭐ Acknowledgement

Dataset sourced from **Kaggle – Customer Behavior Analysis**.

This project was completed as part of a data analysis internship/project assignment with **Alfido Tech**.

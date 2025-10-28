# 🛍️ Customer Shopping Behavior Analysis

## 📘 Overview

This project explores customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective is to uncover insights into spending habits, customer segments, product preferences, and subscription trends to support data-driven business decisions.

## 📑 Table of Contents
- [Overview](#-overview)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Project Steps](#-project-steps)
- [Key Results & Insights](#-key-results--insights)
- [How to Run the Project](#-how-to-run-the-project)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 🧾 Dataset

* **File:** `customer_shopping_behavior.csv`
* **Rows:** 3,900
* **Columns:** 18
* **Key Features:**

  * **Demographics:** Age, Gender, Location, Subscription Status
  * **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
  * **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type
* **Missing Values:** 37 nulls in `review_rating` (handled during cleaning)

---

## 🧰 Tools & Technologies

* **Python (Pandas, NumPy, Matplotlib, Seaborn)** – for data loading, cleaning, and exploratory analysis
* **MySQL / PostgreSQL** – for running SQL queries and business analysis
* **Power BI** – for interactive dashboard creation
* **Gamma App** – for final presentation and report generation

---

## ⚙️ Project Steps

### 1. Data Loading & Cleaning

* Imported dataset with `pandas`
* Performed structure and summary checks (`.info()`, `.describe()`)
* Imputed missing values using median by product category
* Standardized column names to snake_case
* Engineered new features like `age_group` and `purchase_frequency_days`
* Ensured consistency by removing redundant fields

### 2. Exploratory Data Analysis (EDA)

* Visualized customer demographics and purchase distributions
* Analyzed correlations between purchase amount, discounts, and review ratings
* Detected spending trends by season, gender, and age group

### 3. SQL Analysis

Executed queries on the cleaned dataset stored in MySQL/PostgreSQL to answer key business questions:

* **Revenue by Gender**
* **Top 5 Products by Rating**
* **High-Spending Discount Users**
* **Shipping Type Comparison**
* **Subscribers vs. Non-Subscribers**
* **Revenue by Age Group**
* **Customer Segmentation** (New, Returning, Loyal)

### 4. Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

* Revenue distribution across demographics
* Product performance and ratings
* Discount utilization
* Customer segment performance

### 5. Reporting & Presentation

Insights were summarized into a professional **report** and **Gamma presentation** highlighting major findings and recommendations.

---

## 📊 Key Results & Insights

* Female customers generated slightly higher revenue overall.
* Discount users with high spend rates indicate potential for premium loyalty programs.
* Express shipping customers have a higher average purchase value.
* Subscribers consistently show stronger lifetime value and repeat purchase behavior.
* Top-rated products drive the majority of repeat sales.

---

## 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/no4hxl/customer-shopping-behavior.git
   cd customer-shopping-behavior
   ```
2. **Open the Jupyter Notebook:**

   ```bash
   jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb
   ```
3. **Set up SQL connection:**

   * Update your MySQL/PostgreSQL credentials in the notebook.
   * Run the provided SQL queries for analysis.
4. **View Dashboard:**

   * Open the Power BI file (`Customer_Behavior_Dashboard.pbix`)
   * Interact with the filters and visuals.
5. **View Report & Presentation:**

   * Open the PDF report (`Customer Shopping Behavior Analysis.pdf`)
   * Review the Gamma link for the final presentation = https://gamma.app/docs/Customer-Shopping-Behavior-Analysis-q35bqfuyvsu0kbk?mode=doc

---

## 🧩 Future Improvements

* Incorporate time-series analysis for purchase forecasting
* Expand SQL analysis to include customer churn prediction
* Automate ETL pipelines for real-time dashboards

---

## 👤 Author

**Abubakar Nurudeen**
Data Analyst | Python | SQL | Power BI
📧 nurudeena225@gmail.com | 🌐 https://www.linkedin.com/in/abu-nurudeen-776b4835b/

---


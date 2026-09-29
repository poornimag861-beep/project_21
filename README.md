# project_21
# SpendDNA – Personal Finance Analytics

SpendDNA is a Python-based personal finance analytics project that analyzes transaction data and generates insights about spending habits, income, vendors, categories, monthly trends, time-of-day spending, anomalies, and spending patterns.

## 📌 Project Overview

The project uses a transaction dataset to clean and transform financial data and perform exploratory analytics using Python and Pandas.

It provides a final **Personal Finance Analytics Report** containing:

* Spending overview
* Income and spending analysis
* Category-wise spending
* Vendor analysis
* Monthly spending trends
* Time-of-day spending analysis
* Anomaly detection
* Spending archetype detection
* Transaction data verification

## 🎯 Objectives

* Analyze personal transaction data.
* Clean and standardize transaction records.
* Extract vendors from transaction descriptions.
* Categorize transactions based on keywords.
* Calculate total spending and income.
* Identify monthly spending patterns.
* Analyze spending based on time of day.
* Detect unusual transactions using Z-score analysis.
* Identify the user's spending archetype.
* Generate a consolidated financial analytics report.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Jupyter Notebook**
* **CSV Dataset**
* Statistical analysis using **Z-score**

## 📂 Project Structure

```text
SpendDNA/
│
├── minor_project_2.ipynb
├── rahul_transactions.csv
└── README.md
```

## 🔄 Project Workflow

```text
Transaction Dataset
        ↓
Data Loading
        ↓
Data Cleaning & Preprocessing
        ↓
Date & Amount Conversion
        ↓
Transaction Type Standardization
        ↓
Vendor Extraction
        ↓
Transaction Categorization
        ↓
Spending Analysis
        ↓
Monthly Trend Analysis
        ↓
Time-of-Day Analysis
        ↓
Anomaly Detection
        ↓
Spending Archetype Detection
        ↓
Final SpendDNA Report
```

## 📊 Features

### 1. Spending Overview

Calculates:

* Total Spending
* Total Income
* Net Savings
* Savings Rate
* Transaction Count
* Unique Vendors
* Average Transaction
* Highest Transaction

### 2. Vendor Extraction

Transaction descriptions are processed to identify vendors such as:

* Amazon
* Swiggy
* Zomato
* Blinkit
* Zepto
* BigBasket
* Uber
* Ola
* Starbucks
* DMart
* and other vendors

### 3. Category Analysis

Transactions are categorized using keyword-based classification.

Example categories include:

* Food & Dining
* Shopping
* Transport
* Other

### 4. Monthly Trend Analysis

The project calculates spending for each month and analyzes month-to-month spending patterns.

### 5. Time-of-Day Analysis

Transactions are analyzed based on the time of the transaction.

Time periods include:

* Morning
* Afternoon
* Evening
* Night

### 6. Anomaly Detection

The project uses a **within-category Z-score** approach to identify unusually high spending transactions.

Transactions with a Z-score greater than 2 are identified as potential anomalies.

### 7. Spending Archetype Detection

The project analyzes category spending percentages and identifies spending patterns such as:

* Shopping-Heavy Spender
* Category-Focused Spender
* Food-Focused Spender
* Balanced Spender

## 📈 Final Output

The project generates a **SpendDNA Personal Finance Analytics Report** containing key financial metrics and spending insights.

Example:

```text
======================================================================
                         SpendDNA
              Personal Finance Analytics Report
======================================================================

[1] SPENDING OVERVIEW
----------------------------------------------------------------------

Total Spending
Total Income
Net Savings
Savings Rate
Transaction Count
Unique Vendors
Average Transaction
Highest Transaction
```

## ▶️ How to Run

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the project

Open the project folder in **Jupyter Notebook** or **JupyterLab**.

### Step 3: Install Pandas

```bash
pip install pandas
```

### Step 4: Keep the dataset in the same folder

Make sure:

```text
minor_project_2.ipynb
rahul_transactions.csv
```

are in the same project folder.

### Step 5: Run the notebook

Open:

```text
minor_project_2.ipynb
```

and execute the cells from top to bottom.

## 💡 Key Learning Outcomes

Through this project, I learned:

* Data loading using Pandas
* Data cleaning and preprocessing
* Date and amount conversion
* Feature engineering
* Vendor extraction
* Keyword-based categorization
* GroupBy and Pivot Table analysis
* Monthly trend analysis
* Time-based analysis
* Z-score based anomaly detection
* Financial data interpretation
* Generating a structured analytics report

## 🚀 Future Enhancements

* Interactive dashboard using Streamlit
* Spending charts and visualizations
* Budget recommendation system
* Automated financial insights
* More advanced anomaly detection
* Machine learning based spending prediction
* Personal finance dashboard

## 👩‍💻 Project

**Project Name:** SpendDNA – Personal Finance Analytics
**Type:** Minor Project
**Domain:** Data Analytics / Personal Finance
**Language:** Python
**Main Library:** Pandas

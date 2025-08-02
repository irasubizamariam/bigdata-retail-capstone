# bigdata-retail-capstone
Final Capstone Project – Online Retail Analysis using Python &amp; Power BI
# 🛒 Capstone Project – Online Shopping Trend Analysis

## 👩‍💻 Student: IRASUBIZA Mariam  
Course: Introduction to Big Data Analytics – INSY 8413  
Assistant Lecturer: Eric Maniraguha

---

## 🏷️ Title
Can We Predict the Best Time and Day for Online Shopping Deals?

## 📌 Sector
Retail

## 🧠 Problem Statement
This project uses Big Data Analytics to uncover customer shopping patterns using historical online sales data. It aims to identify the best times and days for running promotions to increase e-commerce sales.

## 📂 Dataset
- **Source**: [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **File**: Excel format (Structured)
- **Rows**: 541,909  
- **Columns**: 8  
- **Needs Preprocessing**: ✅ Yes

## ⚙️ Tools
- Python (Colab/Jupyter)  
- Power BI  
- GitHub  
- Excel  
- Matplotlib / Seaborn / Sklearn

## 📈 Project Steps
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Logistic Regression Model to predict peak shopping hours
4. Power BI dashboard to visualize insights
5. Innovation: Time-based heatmap and custom suggestion function

## 🎯 Key Insights
- Most online orders occur between **9AM–3PM**
- **Tuesdays–Thursdays** are peak shopping days
- UK contributes the majority of orders
- Promotions should be run midweek during business hours

## 📊 Power BI Dashboard
The dashboard includes:
- Orders by Day and Hour
- Interactive filters
- Country-based charts
- Revenue summary cards

## 🤖 ML Model
A logistic regression model was used to classify shopping behavior as peak/non-peak based on Quantity and Unit Price.

## 💡 Innovation
- Created a custom suggestion function to advise best times for marketing
- Visualized hourly and daily trends using heatmaps

## 📁 Folder Structure

bigdata-retail-capstone/
├── data/
│   └── Online Retail.xlsx
├── code/
│   └── online_shopping_analysis.ipynb
├── dashboard/
│   └── Online_Shopping_Dashboard.pbix
├── presentation/
│   └── Online_Shopping_Capstone_Presentation.pptx
└── README.md

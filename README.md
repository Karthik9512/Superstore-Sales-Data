# 🏬 Superstore Sales Forecasting & Power BI Dashboard

### 🚀 A complete end-to-end Data Science project using **Python (Pandas, NumPy, Scikit-learn)** and **Power BI** for advanced sales analytics and forecasting.

---

## 🧠 Project Overview

This project demonstrates how data analytics and machine learning can help businesses understand their sales trends and forecast future performance.  
We use **Python** for data cleaning, feature engineering, and model building — and **Power BI** for interactive dashboards and visual insights.

---

## 🎯 Objective

- Analyze historical Superstore sales data  
- Predict future sales using regression models  
- Identify top-performing regions, products, and customer segments  
- Visualize insights using Power BI dashboards  

---

## 🧰 Tech Stack

| Tool / Library | Purpose |
|----------------|----------|
| 🐍 **Python 3.x** | Programming and data manipulation |
| 🧮 **Pandas, NumPy** | Data cleaning and preprocessing |
| 🤖 **Scikit-learn** | Machine Learning (Sales Prediction) |
| ⚡ **Power BI** | Interactive Dashboard for insights |
| 💻 **Jupyter Notebook** | Development environment |

---

## 🧩 Dataset Details

The dataset contains sales transactions from a Superstore including:
- 🛒 **Order Details** — Order ID, Order Date, Ship Date  
- 👤 **Customer Info** — Name, Segment, Region  
- 📦 **Product Info** — Category, Sub-Category, Product Name  
- 💰 **Sales Metrics** — Sales, Profit, Quantity  
- ⏱️ **Shipping Days** — Calculated as delivery duration  

---

## 🧱 Project Workflow

### 1️⃣ Data Preparation (`SuperstoreSales.ipynb`)
- Imported the dataset (`train.csv`)
- Cleaned missing and duplicate values  
- Converted date columns to datetime format  
- Engineered new features:  
  - `Month`, `Year`, `Month Name`, `Shipping Days`
- Used NumPy for basic statistical calculations  

### 2️⃣ Machine Learning Model
- Encoded categorical columns using `LabelEncoder`
- Selected features: `Month`, `Category`, `Region`, `Quantity`
- Built regression models:
  - `LinearRegression`
  - `RandomForestRegressor`
- Evaluated models using **R² Score** and **Mean Absolute Error**
- Generated predicted results and exported to `sales_predictions.csv`

### 3️⃣ Power BI Visualization
- Imported `sales_predictions.csv` into Power BI  
- Created interactive visuals:
  - Line chart: *Sales Trend Over Time*  
  - Bar chart: *Top 10 Products by Sales*  
  - Pie chart: *Sales by Region*  
  - Card visuals: *Total Sales*, *Avg Profit*, *Forecast Accuracy*  
- Added slicers for **Region**, **Category**, and **Year**  
- Published the final dashboard to Power BI Service  

---

## 📂 Folder Structure

📁 Personal Project / Superstore Sales Data /
│
├── 📘 SuperstoreSales.ipynb # Data cleaning, analysis, and ML model
├── 📊 sales_predictions.csv # Final dataset with predicted sales for Power BI
├── 📊 sales_preditNormal.csv # Intermediate ML output
├── 📊 train.csv # Original dataset

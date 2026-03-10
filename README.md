# 🚖 Uber Ride Analytics using Apache Spark & Power BI

## 📌 Project Overview
This project analyzes Uber ride data using **Apache Spark** to process large datasets and generate meaningful analytics.  
The cleaned and aggregated data is then visualized using **Power BI** to create an interactive dashboard.

The goal of this project is to simulate a **real-world data engineering pipeline**, where raw ride data is processed, transformed, and used for business insights.

---

## 🏗️ Project Architecture

Raw Dataset → Spark ETL Pipeline → Cleaned Data → Aggregations → Power BI Dashboard

---

## 📂 Project Structure
uber-spark-analytics
│
├── notebooks
│ uber_analysis.ipynb

├── scripts
│ spark_etl.py

├── dashboard
│ uber_analytics_dashboard.pbix

├── data
│ sample_data.csv

├── output
│ daily_revenue.csv
│ busy_hours.csv
│ pickup_hotspots.csv

└── README.md


---

## ⚙️ Technologies Used

- Apache Spark
- PySpark
- Python
- Power BI
- Git & GitHub

---

## 🔄 Data Processing Pipeline

1. Load Uber ride dataset using **PySpark**
2. Perform **data cleaning**
   - Remove invalid trips
   - Handle missing values
3. Feature Engineering
   - Extract pickup hour
   - Calculate trip metrics
4. Generate analytics datasets:
   - **Daily Revenue**
   - **Busiest Pickup Hours**
   - **Top Pickup Locations**
5. Export processed data to **CSV**
6. Build **Power BI Dashboard**

---

## 📊 Dashboard Insights

The Power BI dashboard provides insights such as:

### 🚦 Busiest Hours
Identifies peak ride demand hours.

### 💰 Revenue Trend
Shows daily revenue generated from trips.

### 📍 Pickup Hotspots
Highlights the most popular pickup locations.

### 📈 Business Insights
Helps understand ride demand patterns and revenue distribution.

---

## 📷 Dashboard Preview

*(Add screenshots of your Power BI dashboard here)*

Example:



---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository


git clone https://github.com/yourusername/uber-spark-analytics.git


### 2️⃣ Install Dependencies


pip install pyspark


### 3️⃣ Run Spark Pipeline


python scripts/spark_etl.py


### 4️⃣ Open Power BI Dashboard

Open the `.pbix` file inside the **dashboard** folder using Power BI Desktop.

---

## 📊 Key Skills Demonstrated

- Big Data Processing with Apache Spark
- Data Engineering ETL Pipelines
- Data Cleaning & Transformation
- Analytical Data Modeling
- Data Visualization with Power BI

---

## 📚 Dataset

NYC Taxi / Uber Ride Data

This dataset contains ride-level information including:
- pickup time
- dropoff time
- trip distance
- passenger count
- fare amount
- pickup location

---

## ⭐ Future Improvements

- Add Spark **window functions**
- Implement **partitioning for performance**
- Use **Parquet format instead of CSV**
- Deploy dashboard to **Power BI Service**

---

## 👨‍💻 Author

Jason Joshuva J
Aspiring Data Engineer / Data Analyst

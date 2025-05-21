# 📦 Sales Data ETL & Predictive Analytics Project

This project showcases a complete end-to-end ETL (Extract, Transform, Load) pipeline followed by feature engineering, predictive analytics, clustering, and data visualization. It uses Snowflake as the data warehouse and integrates with Power BI for visualization.

## 🚀 Project Overview

**Goals:**
- Extract, clean, and preprocess raw sales data
- Perform feature engineering and store structured data in Snowflake
- Use SQL to query data into a notebook
- Perform predictive analytics and clustering tasks
- Visualize insights in Power BI

---

## 🧰 Technologies Used

| Layer             | Tools Used                        |
|------------------|-----------------------------------|
| Programming      | Python (pandas, sklearn, seaborn) |
| Data Warehouse   | Snowflake                         |
| Query Language   | SQL                               |
| Visualization    | Power BI                          |
| Notebook         | Jupyter / VS Code                 |

---

## 📁 Project Structure




---

## 🔄 ETL Pipeline Steps

1. **Extract**
   - Load raw sales data from CSV files using Python and pandas.
   
2. **Transform**
   - Clean missing values, remove duplicates, handle outliers.
   - Perform initial feature engineering (e.g., derive shipment status, delivery time).

3. **Load**
   - Load structured, cleaned data into Snowflake using `snowflake-connector-python`.

---

## 🔍 Data Mining Tasks

Performed inside `data_mining.ipynb`:

1. **Predictive Modeling**
   - `Predict Shipment Status`
   - `Sales Forecasting`
   - `Order Profitability Prediction`

2. **Clustering**
   - Cluster customers/orders by shipping and buying behavior using KMeans.

3. **Geographical Analysis**
   - Analyze delivery delays and profit trends by geolocation (latitude/longitude).

---

## 📊 Power BI Dashboard

- Connected Power BI to Snowflake directly.
- Visualized key KPIs and insights:
  - Shipment performance by region
  - Delivery time trends
  - Profitability by geography
  - Clustering of buyer behavior

---

## ✅ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sales-etl-predictive-analytics.git
cd sales-etl-predictive-analytics
```
### Create and Activate Virtual Environment

```
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows

```

### Install Dependencies

```
pip install -r requirements.txt

```

### Set up Snowflake Connection

```
SNOWFLAKE_USER=your_username
SNOWFLAKE_PASSWORD=your_password
SNOWFLAKE_ACCOUNT=your_account_url
SNOWFLAKE_WAREHOUSE=your_warehouse
SNOWFLAKE_DATABASE=your_db
SNOWFLAKE_SCHEMA=your_schema

```

### Run Jupyter Notebooks

```
jupyter notebook

```

### 📦 Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- snowflake-connector-python
- python-dotenv


## 📈 Results & Visuals

- Power BI file is located in the `powerbi/` folder.
- Visuals include:
  - 📍 Shipment performance maps  
  - 🔍 Cluster distribution of customer behavior  
  - ⏱ Delivery trends over time  
  - 💰 Profit forecasting dashboards  

---

## 🙌 Acknowledgements

Thanks to:

- 🐍 Open source Python libraries (pandas, scikit-learn, etc.)  
- ❄️ Snowflake free-tier access for cloud data warehousing  
- 📊 Power BI for advanced data visualization tools  

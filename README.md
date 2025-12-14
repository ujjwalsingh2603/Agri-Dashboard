# 🌾 Agriculture Analytics Dashboard  
### AWS S3 • Snowflake • Power BI

This project is an **end-to-end cloud-based data analytics solution** that analyzes agricultural data to uncover insights related to **rainfall, temperature, yield, and humidity** across different years, seasons, locations, and crops.  
The goal is to support **data-driven agricultural and business decisions** using modern analytics tools.

---

## 📌 Project Overview

This project follows a complete analytics pipeline:
- Cloud data storage using **AWS S3**
- Data ingestion and transformation using **Snowflake**
- Interactive reporting using **Power BI**

The analysis focuses on understanding how **environmental and seasonal factors** impact crop yield and agricultural outcomes.

---

## 🧱 Architecture & Workflow

1. Created an **Amazon S3 bucket** and uploaded raw CSV data  
2. Configured **IAM roles** and trust policies for secure integration  
3. Created **Snowflake integration objects**  
4. Loaded data from **S3 into Snowflake**  
5. Performed **data exploration and transformation using Snowflake SQL**  
6. Added derived columns such as **Rainfall Groups**  
7. Connected **Power BI to Snowflake**  
8. Built multiple analytical dashboards  
9. Published the report to **Power BI Service**

---

## 🗂️ Dataset Description

The dataset contains agricultural and environmental attributes with the following columns:

| Column Name | Description |
|------------|-------------|
| Year | Year of observation |
| Location | Geographic location |
| Area | Cultivated area |
| Rainfall | Rainfall amount |
| Temperature | Average temperature |
| Soil type | Type of soil |
| Irrigation | Irrigation availability |
| Yields | Crop yield |
| Humidity | Humidity percentage |
| Crops | Crop type |
| Price | Market price |
| Season | Season of cultivation |

---

## 🛠️ Tools & Technologies Used

- **Cloud Storage:** AWS S3  
- **Data Warehouse:** Snowflake  
- **Query Language:** Snowflake SQL  
- **Visualization:** Power BI  
- **Data Source:** CSV files  

---

## 📊 Power BI Reports Created

Four interactive Power BI reports were developed:

1. **Rainfall Analysis**
2. **Temperature Analysis**
3. **Yield Analysis**
4. **Humidity Analysis**

Each report allows analysis by:
- Year  
- Season  
- Location  
- Crop type  

---

## ❓ Business Questions Answered

### 1️⃣ How does rainfall vary across different seasons and locations?
**Answer:**  
Rainfall patterns vary significantly by season and region, helping identify areas prone to water scarcity or excess rainfall.

---

### 2️⃣ What is the relationship between temperature and crop yield?
**Answer:**  
Moderate temperature ranges show higher yields, while extreme temperatures negatively impact crop productivity.

---

### 3️⃣ Which crops perform best under specific rainfall and humidity conditions?
**Answer:**  
Certain crops demonstrate higher yields in high-humidity and moderate-rainfall conditions, supporting optimized crop selection.

---

### 4️⃣ How do seasonal changes impact agricultural yield?
**Answer:**  
Seasonal trends reveal yield fluctuations, enabling better planning for sowing and harvesting cycles.

---

### 5️⃣ Which locations consistently produce higher yields?
**Answer:**  
Specific locations show stable high yields across years, indicating favorable environmental and soil conditions.

---

## 📈 Key Insights

- Environmental factors such as **rainfall and temperature** have a direct impact on crop yield  
- Seasonal analysis helps identify **optimal growing periods**  
- Location-based insights support **region-specific agricultural planning**  
- Interactive dashboards improve **decision-making efficiency**

---

## 🔗 Power BI Report Link

👉 **Live Dashboard:**  
[https://github.com/ujjwalsingh2603/Agri-Dashboard/blob/main/agri%20%20dashboard.pbit]

---

## 🖼️ Dashboard Preview

> Add screenshots of your Power BI dashboards below for better visibility.

```markdown
![Rainfall Dashboard](images/rainfall_dashboard.png)
![Temperature Dashboard](images/temperature_dashboard.png)
![Yield Dashboard](images/yield_dashboard.png)
![Humidity Dashboard](images/humidity_dashboard.png)

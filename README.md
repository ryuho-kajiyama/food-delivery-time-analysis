README Food delivery Analysis

## 📌 Food Delivery Time Analysis Dashboard
Exploring internal, external, and logistical factors that impact delivery time using Python, SQL, and Power BI

## 📈 1. Project Overview
This project analyzes food delivery time data to identify patterns associated with delivery performance.

Using:<br/>
- **Python (Pandas)** for data exploration and cleaning
- **SQL** for validating key drivers identified during EDA
- **Power BI** for interactive visualization
- **Kaggle Notebook** for code and documentation

The goal is to answer key questions related to food delivery time, such as:
-  How do weather conditions impact average delivery time?  
-  How does delivery distance affect delivery time?
-  How are preparation times associated with overall delivery times?

## 📊 2. Dataset
- **Columns**: 9
- **Rows**: 1,000
- **Missing Values**:<br/>
**Weather**: 30 rows<br/>
**Traffic_Level**: 30 rows<br/>
**Time_of_Day**: 30 rows<br/>
**Courier_Experience_yrs**: 30 rows

## 🧹 3. Data cleaning
- Filled missing numeric values with median and categorical values with "Unknown."
- Converted the data type of Courier_Experience_yrs to integer.

## 🔍 4. Exploratory Data Analysis
- Most deliveries occur during clear weather.
- Traffic density is mostly medium, followed by low.
- Average delivery time is around 57 minutes.
- Distance ranges from 0.59 km to 19.99 km.

These exploratory observations provide context for identifying the key drivers of delivery time, which are further analyzed through KPIs, SQL, and the dashboard.

## 🧠 5. Key performance indicators
- **1. Delivery Time**:
Measures the overall average delivery time across all orders.
- **2. Delivery Time by Weather**:
Measures how different weather conditions impact average delivery time.
- **3. Delivery Time by Traffic Level**:
Measures how traffic density affects average delivery time.
- **4. Delivery Time by Distance**:
Measures average delivery time across four distance categories.
- **5. Delivery Time by Preparation Time**:
Measures how restaurant preparation time influences average delivery time.

## 🔍 6. SQL Analysis
### Why SQL is used
- To validate key drivers identified during EDA, including weather, traffic levels, and delivery distance patterns.
### What this section validates
- Weather conditions and traffic levels significantly increase average delivery time.
- Delivery times are distributed across distance categories with slightly higher volumes in longer distance groups.

## 🧾 7. Dashboard Overview
This dashboard is designed to highlight the key drivers that impact delivery time and support operational decision–making. 
It helps delivery managers focus on actions to reduce delivery time by addressing the most influential drivers.
### Executive Summary
Preparation Time has the strongest controllable impact on delivery delays.
**Recommendation:** Monitor and optimize restaurant preparation during peak hours.
![Dashboard Screenshot: Score Cards](images/dashboard_overview.png)
### Key Delivery Time Drivers
Delivery time increases with worse weather, higher traffic, longer distance, and longer preparation time.
![Dashboard Screenshot: Key Charts](images/dashboard_key_charts.png)
### Interactive Filters
Users can filter delivery performance by traffic level to explore how conditions affect delivery time.
![Dashboard Screenshot: Filters](images/dashboard_filters.png)

## 💡 8. Key Insights
- **Insight 1**: Weather conditions and traffic levels significantly increase average delivery time.
- **Insight 2**: Average delivery time increases as the delivery distance becomes longer.
- **Insight 3**: Longer preparation times are associated with higher overall delivery times.

### Business Impact
By focusing on preparation time, delivery managers can reduce delays using an internal, controllable lever, rather than external factors such as weather or distance.

## 🧰 9. Tools & Technologies
- **Python**
- **SQL**
- **Power BI**
- **GitHub Repository**

## 🚀 10. Next Step
- Continue building end–to–end BI projects and expanding Power BI dashboards to strengthen my analytical and storytelling skills.

👨‍💻 *Created by: Ryuho Kajiyama
📍 Netherlands | 📧 Kumagorou.ryuho@gmail.com | 🔗 [GitHub: https://github.com/ryuho-kajiyama / LinkedIn: https://www.linkedin.com/in/ryuho-kajiyama-979205362/]

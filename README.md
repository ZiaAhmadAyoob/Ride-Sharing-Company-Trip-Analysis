# 🚗 GoRide – Ride-Sharing Trip Data Analysis (Case Study)

## 📌 Project Overview
This project presents a **data analysis case study for GoRide**, a ride-hailing company operating in 5 major cities of Pakistan.  
The objective is to clean, process, visualize, and analyze real trip data to extract insights that help **improve pricing strategies**, **identify top drivers**, **monitor service quality**, and **understand customer behavior**.

---

## 🧭 Objectives
- Perform data cleaning and transformation to prepare trip data for analysis.  
- Analyze revenue, driver performance, payment methods, and passenger ratings.  
- Visualize key trends and patterns using Python libraries.  
- Produce a professional business insights report.

---

## 📂 Dataset
- **File:** `ride_sharing_trip_data.csv`  
- **Records:** 200 (1 year of completed trips)  
- **Columns:**  
  - `Ride ID`  
  - `Ride Date` (dd-mm-yyyy)  
  - `City`  
  - `Car Type` (Bike / Economy / Business / etc.)  
  - `Driver`  
  - `Distance (km)`  
  - `Base Fare`  
  - `Total Fare`  
  - `Discount Applied`  
  - `Payment Method` (Card / Cash / Wallet)  
  - `Passenger Rating` (out of 5)

---

## 🛠️ Tools & Libraries
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook

---

## 🧹 Part 1 – Data Cleaning
- Loaded dataset and inspected structure.  
- Converted `Ride Date` to datetime format.  
- Handled missing values in `Driver` and `Total Fare` logically (replacement/dropping).  
- Created new columns:
  - `Month` → extracted from `Ride Date`  
  - `Final Revenue` = `Total Fare` − `Discount Applied`

---

## 📊 Part 2 – Data Analysis
Performed key business analyses, including:

1. **💰 Total revenue** (after discounts) and **total rides**  
2. **🚘 Average fare per km** by Car Type  
3. **🏆 Top 3 drivers** by total revenue  
4. **🌆 City-wise** ride counts and average passenger ratings  
5. **💳 Payment methods** usage frequency and total revenue per method

---

## 📈 Part 3 – Data Visualization
The following visualizations were created to explore trends and patterns:

1. **📅 Line Plot** – Monthly total revenue trend (Matplotlib)  
2. **👨‍✈️ Bar Chart** – Top 5 drivers by revenue (Seaborn)  
3. **🥧 Pie Chart** – Rides distribution by Car Type  
4. **📦 Box Plot** – Fare variation across Car Types (Seaborn)  

All charts include descriptive titles, axis labels, legends, and color enhancements for clarity.

---

## 📌 Key Insights
- 🚖 **Economy and Bike** rides generated the highest ride counts, but **Business rides** had higher average fare per km.  
- 💼 Top drivers significantly outperformed the average, indicating strong revenue concentration.  
- 🌇 Major cities like **Karachi and Lahore** contributed most to total rides and revenue.  
- 💳 Digital payments (Card/Wallet) are gaining traction but **Cash** remains dominant.  
- ⭐ Passenger ratings were generally high, with some variation by city and car type.

---

## 🚀 Business Recommendations
- **Incentivize high-performing drivers** to maintain service quality and retention.  
- **Adjust pricing strategies** based on car type profitability and distance metrics.  
- **Promote digital payments** to reduce handling delays and improve revenue tracking.  
- **Focus on service quality in key cities** to maintain strong customer satisfaction.  
- **Leverage seasonal/monthly trends** for targeted promotions.

---

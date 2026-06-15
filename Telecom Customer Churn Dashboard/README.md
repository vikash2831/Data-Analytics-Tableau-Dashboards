📡 Telecom Customer Churn Dashboard (Tableau)

📌 Project Overview

This project presents an **interactive Telecom Customer Churn Dashboard** built using Tableau, based on a dataset containing **4,835 customer records** and **36 columns**.
The dashboard analyzes customer churn behavior, revenue contribution, contract types, payment methods, and internet service usage.

---

📁 Dataset Details

* 📄 File: `Telecom_Customer_Churn_Data.xlsx`
* 📊 Total Records: **4,835 rows**
* 🧾 Total Columns: **36**

Major Columns Included:

* CustomerID
* Gender
* Age
* Married
* Dependents
* City
* Zip Code
* Latitude
* Longitude
* Number of Referrals
* Tenure in Months
* Offer
* Internet Type
* Online Security
* Online Backup
* Device Protection Plan
* Premium Tech Support
* Streaming TV
* Streaming Movies
* Contract
* Payment Method
* Monthly Charge
* Total Charges
* Customer Status
* Churn Category
* Churn Reason
* Total Revenue

---

🔧 Data Processing

* Removed null and duplicate values
* Converted location data for map visualization
* Cleaned revenue and monthly charge columns
* Categorized churned, stayed, and joined customers
* Created calculated fields:

  * Churn Rate %
  * Average Monthly Charges
  * Average Tenure
  * Total Revenue

---

📊 Dashboard Features

🔹 Key Performance Indicators (KPIs)

* 👥 Total Customers: **4,835**
* 📉 Churn Rate: **32.8%**
* 💰 Total Revenue: **₹18.15M**
* 💵 Avg Monthly Charge: **₹80.31**
* ⏳ Avg Tenure: **33.04 Months**

---

🔹 Visualizations

🌐 Internet Service Analysis

Shows customer distribution across:

* Fiber Optic
* DSL
* Cable

Fiber Optic dominates customer usage.

---

🗺️ Revenue by City (Top 15)

Map visualization showing revenue contribution by location.

---

👥 Customer Status Distribution

Breakdown of:

* Stayed
* Churned
* Joined

Helps identify churn volume clearly.

---

💸 Customer Revenue Analysis

Scatter plot comparing:

* Monthly Charges
* Revenue contribution

Used for identifying high-value customers.

---

💳 Payment Method vs Churn

Analyzes churn based on payment method:

* Bank Withdrawal
* Credit Card
* Mailed Check

Bank withdrawal has the highest churn count.

---

📜 Churn by Contract Type

Contract categories:

* Month-to-Month
* One Year
* Two Year

Month-to-month contracts have the highest churn.

---

🔹 Filters / Slicers

* Gender
* Customer Status
* Contract Type
* Internet Type
* Payment Method
* Multiple Lines

---

🎯 Key Insights

* 📌 **32.8% churn rate** indicates moderate customer loss
* 📌 Fiber Optic users have higher churn concentration
* 📌 Month-to-month customers churn more frequently
* 📌 Bank withdrawal users show higher churn behavior
* 📌 High monthly charges often correlate with churn
* 📌 Major revenue comes from loyal long-tenure customers

---

🛠️ Tools & Technologies

* Tableau Desktop
* Microsoft Excel

---

🚀 How to Use

1. Download the Tableau workbook (`.twbx`)
2. Open in Tableau Desktop
3. Load dataset if required
4. Explore dashboard filters and insights

---

👨‍💻 Author

* Vikash
* Aspiring Data Analyst

---

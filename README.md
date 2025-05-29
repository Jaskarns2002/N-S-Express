# 🚚 **NS Express – Trucking Data Management & BI Dashboard**

---

## 📌 Overview  
NS Express is a growing trucking company aiming to streamline daily operations and fuel cost tracking. This project brings their workflow into the digital age using **MySQL**, **Excel**, **Python**, and **Tableau** to build a full-stack data management and visualization system.

From manually entering costs and load data to building automated pipelines and a live dashboard, this solution empowers NS Express to make faster, smarter business decisions.

---

## 🎓 What I Learned  
🔹 **Database Design** – Built relational schemas and ERDs to model real business operations  
🔹 **Excel → MySQL Integration** – Made spreadsheets the live heartbeat of a backend database  
🔹 **Python Automation** – Wrote a script to sync Excel updates straight to MySQL automatically  
🔹 **SQL Analysis** – Wrote queries for revenue, cost, profit, profit margin, and trends  
🔹 **BI with Tableau** – Built interactive dashboards to visualize performance and monitor metrics  

---

## 📂 Files in This Repo  
• `NSExpress_Database.xlsx` – Core Excel file with all trucking data (Loads, Costs, Drivers, Trucks)  
• `NS_Package.twbx` – Final Tableau dashboard connected directly to the Excel file  
• `nsexpress.py` – Python script that automates Excel → MySQL syncing  
• `N&S_RelationalSchema.png` – Final relational schema design with foreign keys  
• `N&S_ERD.png` – Initial ERD diagram from planning stage  

---

## 🧩 Project Workflow

### 🧾 Phase 1: Data Collection & ERD Modeling  
To begin the project, I manually gathered operational data from the company’s trucking records and structured it into Excel spreadsheets categorized by loads, diesel costs, drivers, and trucks. Based on this foundational data, I created an Entity-Relationship Diagram (ERD) to logically map out the database structure. This ensured a scalable design that supports relational integrity and business-specific querying needs.

<img width="1440" alt="ERD Diagram" src="https://github.com/user-attachments/assets/7f0ad426-2fc9-46c1-909f-2e49174a5267" />
<img width="1440" alt="Excel" src="https://github.com/user-attachments/assets/19a38d76-7d16-4957-a134-e0d7a346ec51" />

---

### 🛠️ Phase 2: Data Cleaning & Automation  
After establishing the schema, I implemented a MySQL database to store and manage the cleaned data. This involved normalizing tables, removing nulls, and performing key financial calculations like total revenue, cost, and profit margins using SQL. To enhance efficiency, I developed a Python automation script that dynamically updates the MySQL database as new data is entered into the Excel sheets—enabling real-time data sync and eliminating manual data transfers.

<img width="1440" alt="Python Script" src="https://github.com/user-attachments/assets/04a56cd1-6d90-4257-95a5-edc3965ce298" />  
<img width="1440" alt="MYSQl" src="https://github.com/user-attachments/assets/0073f5d4-c63b-4d9e-b342-0809e7b37620" />

---

### 📊 Phase 3: Dashboard Development  
With a clean and automated data pipeline in place, I transitioned to designing a professional-grade business intelligence dashboard using Tableau. The dashboard integrates financial KPIs, trend analysis, and driver-level metrics to provide real-time insights for operational and strategic decision-making. The final product includes interactive filters, route breakdowns, and monthly profit trend lines—allowing stakeholders to easily monitor performance and identify business opportunities.

<img width="1440" alt="Tableau Dashboard" src="https://github.com/user-attachments/assets/baa5f866-afbd-4fb6-8db3-27c979f12c2c" />  

---

## 📈 Tableau Dashboard Highlights  
✔ Revenue vs. Cost – Dual-axis trend over time  
✔ Monthly Profit & Margin tracking  
✔ Driver performance analysis  
✔ Route-level insights with map visuals  
✔ One-click filters to drill into any aspect of the business  

> 💡 Built for clarity. Scaled for growth. Designed for action.

---

## 👨‍💻 My Role: Full-Stack Developer & Data Analyst  
- Collected and organized operational data  
- Built schema and backend from scratch  
- Scripted automation using Python  
- Cleaned, queried, and analyzed real business metrics  
- Designed and deployed the Tableau dashboard  
- Tailored insights to small business goals & operations  

---

## 🛠️ Tools & Technologies  
- **Excel** – Operational hub for trucking data  
- **MySQL** – Relational database and querying backend  
- **Python** – Scripted automation for real-time data syncing  
- **Tableau** – Interactive business intelligence dashboard  

---

## 📝 Lessons Learned  
- Automation = fewer mistakes and more time for strategy  
- Data-driven decisions can transform small business success  
- Dashboards must balance simplicity with insight  
- Great analytics start with a clean schema  

---

## ✅ Project Status  
✅ Project is fully deployed and in use by NS Express  
🚀 Ready to scale up as the business grows

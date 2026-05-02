🍔 QuickBite Express: Crisis Impact Analysis

"Power BI" (https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)
"SQL" (https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
"Power Query" (https://img.shields.io/badge/Power_Query-0078D4?style=for-the-badge&logo=Microsoft&logoColor=white)

---

📊 Overview

This project presents a Business Intelligence dashboard analyzing the impact of a business crisis on QuickBite Express.

The analysis compares:

- 📈 Pre-Crisis Performance
- 📉 Crisis Period Performance

Timeframe: Jan 2025 → Sept 2025

📄 Dashboard preview:
➡️ New_one_Project.pdf

---

🏗️ Data Architecture

graph TD
A[(Raw Data / SQL)] -->|Extraction| B(Power Query)
B -->|Cleaning & Transformation| C{Data Model}
C -->|DAX Measures| D[Power BI Dashboard]
D --> E((Insights))

---

🚀 Key Insights

flowchart LR
Rev[Revenue] -->|70.92% Drop| RevDrop[37.6M ➡️ 10.9M]
Ord[Orders] -->|78K Lost| OrdDrop[113K ➡️ 35K]
Can[Cancellations] -->|Doubled| CanSpike[~6% ➡️ 12.51%]
Sat[Satisfaction] -->|Crashed| SatDrop[4.7 ⭐ ➡️ 2.3 ⭐]

📉 Business Impact

- Revenue Drop: 37.6M ➝ 10.9M (-70.92%)
- Order Loss: ~78,000 orders lost
- Cancellation Rate: ~6% ➝ 12.51%
- Customer Rating: 4.7 ⭐ ➝ 2.3 ⭐

---

🔍 Deep Dive Analysis

🌍 City-Level Impact

- ~70% drop across all major cities:
  - Delhi
  - Pune
  - Mumbai
  - Ahmedabad
  - Bengaluru

🍽️ Restaurant Performance

- Top vendors saw heavy decline
- Biryani and Paratha outlets hit hardest

---

⏱️ Operations Breakdown

- Cancellation spike during mid-2025
- Delivery delays increased
- Discounts increased but failed to recover demand

---

😠 Customer Sentiment

- Sentiment dropped from +0.87 ➝ -0.35
- Major decline across:
  - Starters
  - Biryani
  - Beverages
  - Curries

---

🛠️ Tech Stack

Tool| Usage
SQL| Data extraction & querying
Power Query| Data cleaning & transformation
Power BI| Dashboard & visualization

---

📂 How to Use

1. Clone repository:

git clone https://github.com/yourusername/QuickBite-Crisis-Analysis.git

2. Open:

- New_one_Project.pdf → Dashboard preview

3. Launch:

- .pbix file in Power BI Desktop

4. Explore:

- Filter by city
- Filter by restaurant_name

5. Compare:

- Use Crisis_Phase slicer
- Switch between Pre-Crisis and Crisis

---

📌 What This Project Shows

- Real-world business impact analysis
- Strong data storytelling
- Ability to convert raw data into actionable insights

---

⭐ Support

If you found this useful, give it a ⭐ on GitHub.

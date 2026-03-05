Olist E-Commerce Ecosystem: Data-Driven Business Strategy Analysis

📌 Project Overview
This project provides a comprehensive Exploratory Data Analysis (EDA) of Olist, the largest department store marketplace in Brazil. By analyzing over 100,000 orders from 2016 to 2018, this interactive Power BI dashboard identifies key growth drivers, logistics bottlenecks, and customer behavioral patterns to provide actionable strategic recommendations.
🛠️ Tech Stack
Data Visualization: Power BI (Desktop & Service)

Data Modeling: Star Schema (1:N relationships, Date Tables)

Data Transformation: Power Query (M Language) for data cleaning and localization

Calculations: DAX (Data Analysis Expressions) for Time Intelligence, correlation, and custom KPIs

📊 Key Analysis Modules
1. Sales Performance & Time Intelligence
Implemented Sales MTD (Month-to-Date) and YoY (Year-over-Year) comparisons.

Analyzed seasonal trends, identifying the significant impact of Black Friday on total GMV.

Insight: A consistent growth trajectory was observed from 2017 to 2018, with a shift in dominant product categories.
<img width="1121" height="636" alt="image" src="https://github.com/user-attachments/assets/e795224b-3308-438a-8335-dfe2a66bbe1c" />

2. Logistics & Operational EfficiencyCalculated On-time Delivery Rate and Average Delivery Lead Time.Developed a correlation analysis between Delivery Delay Days and Customer Review Scores.Insight: Data reveals a strong negative correlation ($r$); every additional day of delay beyond the estimated date significantly increases the probability of a 1-star review.
<img width="1115" height="633" alt="image" src="https://github.com/user-attachments/assets/363c086f-8a0d-4b41-9607-a8756c3a0ccd" />

3. Consumer Finance & Payment Behavior
Analyzed the unique Brazilian Installment payment culture.

Mapped the relationship between Product Price and the number of Payment Installments.

Insight: Higher-priced items (Electronics, Appliances) show an 85%+ dependency on installment plans, suggesting that financial flexibility is a primary conversion driver.
<img width="1120" height="625" alt="image" src="https://github.com/user-attachments/assets/110255cd-6474-46d6-8299-f37ce052849b" />

4. Geographic Market Density
Used Spatial Analysis (Filled Maps & Bubble Maps) to visualize order density across Brazilian states.
<img width="519" height="457" alt="image" src="https://github.com/user-attachments/assets/af80db3d-a27e-4c53-89e4-a0dd965cad9d" />

Insight: While 40% of orders are concentrated in São Paulo (SP), remote states face higher shipping costs and longer lead times, highlighting a need for decentralized regional distribution centers.
<img width="552" height="270" alt="image" src="https://github.com/user-attachments/assets/f471017a-3dac-4ddc-9c39-d06fcfefe580" />

📈 Dashboard HighlightsInteractive Slicers: Dynamic filtering by Year, Category, and State.Drill-through Capability: Ability to move from high-level state data down to specific city-level performance.Advanced DAX: Custom measures for rolling averages and statistical correlation.

📂 Dataset Source
The data used in this project is the Brazilian E-Commerce Public Dataset by Olist, originally sourced from Kaggle. It includes information on order status, price, payment, freight performance, customer location, and product attributes.



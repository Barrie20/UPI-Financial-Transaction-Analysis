# Analysis of UPI Financial Transactions

**By Alpha Yerroh Barrie**

---

## Project Overview 📈

This project is a deep-dive analysis of Unified Payments Interface (UPI) transactions in the Indian FinTech landscape. The goal was to transform raw transactional data into a dynamic and interactive Power BI dashboard. This dashboard serves as a business intelligence tool to monitor transaction patterns, identify top user segments, and understand the overall health of the UPI ecosystem.

---

## Data Source

The dataset is a CSV file containing anonymized UPI transaction records. It includes key fields such as transaction date, time, transaction volume, and payment type, providing a solid foundation for time-series and categorical analysis.

---

## Tools & Technologies

* **Data Transformation:** Power Query (in Power BI)
* **Data Analysis & Calculations:** DAX (Data Analysis Expressions)
* **Data Visualization & Dashboarding:** Power BI
* **Version Control:** Git & GitHub

---

## Project Methodology

1.  **Data Loading and Cleaning:** I imported the raw CSV data into Power BI and utilized Power Query to perform data cleansing. This involved managing data types, splitting date-time columns for granular analysis, and ensuring the dataset was free of inconsistencies.
2.  **DAX for Custom KPIs:** I wrote several key DAX measures to create critical business metrics that were not available in the original dataset. These KPIs included Total Transaction Volume, Average Transaction Value, and Year-over-Year Growth Percentage.
3.  **Interactive Dashboard Design:** I designed a user-centric dashboard focused on intuitive navigation. A key feature is the implementation of advanced slicers for date ranges and transaction types, allowing stakeholders to easily filter the data and drill down into specific insights, as showcased in the design document (`4. Size+&+Position+Slicers.pptx`).

---

## Key Insights from the Dashboard

* **Peak Transaction Hours:** The analysis revealed that the highest volume of UPI transactions consistently occurs between 7 PM and 9 PM.
* **Monthly Growth Trend:** The dashboard visualizes a clear upward trend in transaction volume, with an average month-over-month growth of 12%.
* **Dominant Payment Types:** Person-to-Person (P2P) transfers constitute over 65% of the total transaction value, highlighting their dominance in the UPI ecosystem.

---

## Dashboard Preview

Below is a screenshot of the main dashboard interface, demonstrating the clean layout and interactive filtering capabilities.

*(Here, you should add a screenshot from your `4. Size+&+Position+Slicers.pptx` file. You can take a screenshot of the main slide and upload it to your repository.)*

![UPI Dashboard Preview](Your-Dashboard-Screenshot.png)

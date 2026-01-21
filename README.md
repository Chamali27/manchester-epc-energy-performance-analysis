# Manchester EPC Energy Performance Analysis

**Data-driven analysis of residential building energy performance in Manchester using SQL Server and Power BI**

---

## Project Overview

This project analyzes **Energy Performance Certificate (EPC)** data for residential properties in Manchester to understand energy efficiency, carbon emissions, and cost patterns. Using **SQL Server** for data cleaning and **Power BI** for interactive dashboards, we turned raw EPC data into actionable insights for building sustainability.

The analysis focuses on **property characteristics**, **energy ratings**, and **recommended improvements**, helping identify areas with high potential for energy efficiency interventions.

---

## Folder Structure
```
manchester-epc-energy-performance-analysis/
│
├── report/
│   └── Manchester_EPC_Energy_Performance_Report.pdf
│
├── sql/
│   └── epc_analysis_queries.sql
│
├── powerbi/
│   └── dashboard_screenshots/
│       ├── home.png
│       ├── overview.png
│       ├── cost_dashboard.png
│       ├── energy_efficiency.png
│       ├── property_characteristics.png
│       └── recommendation.png
│
└── README.md

```

---

## Datasets

Analysis was conducted using:
- `certificates.csv` – EPC certificate-level data  
- `recommendations.csv` – recommended energy efficiency improvements  

Data is sourced from the **UK Government EPC Open Data Portal** and filtered for Manchester properties.

---

## Key Insights

- Heating contributes the most to residential energy costs  
- Mid-terrace and gas-heated properties dominate EPC certificates  
- Most properties are rated **C or D**, showing strong improvement potential  
- Recommended upgrades (heating, solar installations) reduce costs and CO₂ emissions  
- Interactive dashboards (shown via screenshots) allow exploration by property type, energy rating, and period  

---

## Technologies Used

- **SQL Server** – data management and transformation  
- **Power BI** – dashboards and visual insights  
- **CSV / Excel** – raw EPC datasets  

---

## Academic Context

This project was completed as part of the module:

**Advanced SQL and Cloud Databases**  
BSc in Applied Data Science Communication  
General Sir John Kotelawala Defence University  

---

## How to Use This Repository

1. Review the project report in the `report/` folder  
2. Explore SQL logic in the `sql/` folder  
3. View dashboard insights via the screenshots in `powerbi/dashboard_screenshots/`  

---

## Authors / Team Members

**Chamali Abeysekara**  
BSc in Applied Data Science Communication  

**Team Members / Contributors:**  
- Rajintha Lakshani  
- Hussein Ziyard  
- Muhammed Nasir  

---

## Acknowledgements

This project was successfully completed through effective collaboration and shared effort. Special thanks to all contributors for their support in data preparation, SQL development, and Power BI visualization.

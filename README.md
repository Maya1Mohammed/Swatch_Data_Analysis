# Swatch Data Analysis – Power BI Project

## Project Overview

This project presents a **data analysis of Swatch-related data** using **Power BI**. The goal is to explore, model, and visualize the data to extract meaningful insights through interactive dashboards and reports.

The project is stored using the **Power BI Project format (`.pbip`)**, which separates the report visuals and the data model into structured files suitable for version control (GitHub).

---

## Repository Structure

```
Swatch_Data_Analysis/
│
├── Swatch_Data_Analysis_PowerBI.pbip   # Power BI project entry file
│
├── report/                            # Report visuals & pages
│   ├── report.json
│   └── sections/                      # Individual report pages
│
├── semanticModel/                     # Data model & analysis logic
│   ├── model.bim                      # Tables, relationships, DAX measures
│
└── README.md
```

---

## Where the Actual Work Is

### Visuals & Dashboards

* Located in the **`report/`** folder
* Includes:

  * Charts and visuals
  * Dashboard pages
  * Filters and interactions

> These are stored as structured JSON files and are reconstructed by Power BI Desktop.

### Data Model & Analysis

* Located in the **`semanticModel/`** folder
* Includes:

  * Data tables
  * Relationships
  * DAX measures and calculations

This folder represents the **analytical logic** behind the visuals.

---

## How to Open the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Maya1Mohammed/Swatch_Data_Analysis.git
   ```
2. Open **Power BI Desktop**
3. Open the file:

   ```
   Swatch_Data_Analysis_PowerBI.pbip
   ```
4. Power BI will automatically load the report and data model

---

## Important Notes

* GitHub **cannot render Power BI visuals** directly
* The `.pbip` file is only a project reference — visuals are not missing
* To easily showcase results, screenshots or a `.pbix` export can be added

---

## Sample Charts

<img width="852" height="510" alt="chart1" src="https://github.com/user-attachments/assets/5e9335f8-8da2-445b-a355-6a21a6e09707" />

<img width="666" height="337" alt="chart2" src="https://github.com/user-attachments/assets/4493f9a5-a7db-4e4a-81d1-9f55aa10cd0d" />

---

## Tools Used

* **Power BI Desktop**
* **Power BI Project (.pbip) format**
* **GitHub** for version control

---

## Author

**Maya Mohammed**

If you have any questions about the analysis or project structure, feel free to reach out.

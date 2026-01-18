# 🌋 Power BI Volcano Analysis Dashboard

## 📌 Project Overview

This project is an end-to-end **Power BI data analytics dashboard** built on a real-world volcano dataset. The goal of the project is to analyze volcanic activity, eruption history, geographical distribution, and impact assessment using an optimized **Snowflake Schema** data model.

The dashboard converts raw volcanic data into meaningful insights that can support **risk assessment, disaster preparedness, and decision-making**.

---

## 🏗️ Data Architecture & Model

The project follows a **Snowflake Schema** for better normalization and performance.

### 🔹 Fact Tables

* **Eruption_Details** – Stores eruption history, eruption type, VEI, start and end dates.
* **Eruption_Impacts** – Contains eruption impact details such as casualties and damage description.

### 🔹 Dimension Tables

* **Volcano_Details** – Volcano metadata including region, country, elevation, type, and status.
* **Volcano_Locations** – Location-specific details such as nearest city, distance to city, tectonic setting.
* **Volcano_By_Country** – Aggregated country-level volcano statistics (Active, Dormant, Extinct).

Relationships are built using **Volcano ID** and **Eruption ID**, ensuring accurate filtering and drill-down analysis.

---

## 🔄 Data Processing (ETL)

* Imported data from structured datasets (CSV / Excel).
* Cleaned and transformed data using **Power Query**.
* Removed unnecessary columns and optimized data types for performance.
* Built relationships and validated data integrity.

---

## 📊 Dashboard Features

* Interactive dashboards fully driven by the dataset.
* Global and regional analysis of volcano distribution.
* Eruption trend analysis over time.
* Risk and severity analysis using VEI.
* Country-wise comparison of active, dormant, and extinct volcanoes.
* Drill-through and slicers for dynamic exploration.

---

## 🧮 DAX & Analytics

* Created calculated measures for:

  * Total Eruptions
  * Average VEI
  * Eruption Trends by Year
  * Impact analysis based on casualties
* Used time-based calculations for trend analysis.

---

## 💡 Key Insights

* Identified regions with high volcanic concentration and activity.
* Highlighted volcanoes with higher historical eruption severity.
* Analyzed proximity of volcanoes to populated cities.
* Provided data-driven insights to support disaster risk planning.

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **DAX**
* **Power Query**
* **Data Modeling (Snowflake Schema)**

---

## 📂 Project Files

* `Project.pbix` – Power BI dashboard file
* Dataset files – Volcano-related data sources

---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open it in Power BI Desktop.
3. Refresh data if required.
4. Explore dashboards using slicers and filters.

---

## 👤 Author

**[Nazish Shaikh]**
Power BI | Data Analytics 

---



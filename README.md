
# 📊 Daikibo Factory Telemetry Analysis Dashboard

## 📌 Project Overview

This project was completed as part of the **Deloitte Data Analytics Virtual Experience Program**. The objective was to analyze machine telemetry data collected from four Daikibo manufacturing plants using **Tableau** and identify:

* Which factory experienced the highest machine downtime.
* Which machine types contributed the most to downtime in that factory.

The dashboard provides an interactive visualization that helps stakeholders quickly identify operational issues and make data-driven maintenance decisions.

---

## 🎯 Business Problem

Daikibo collected telemetry data from machines across four factories:

* 🇯🇵 Meiyo Factory (Tokyo, Japan)
* 🇯🇵 Seiko Factory (Osaka, Japan)
* 🇩🇪 Berlin Factory (Berlin, Germany)
* 🇨🇳 Shenzhen Factory (Shenzhen, China)

Each factory contains nine different machine types that send telemetry data every 10 minutes.

The business wanted answers to the following questions:

1. Which factory had the highest machine downtime?
2. Which machine types contributed the most to downtime in that factory?

---

## 🛠️ Tools & Technologies

* Tableau Public / Tableau Desktop
* JSON Dataset
* Data Visualization
* Calculated Fields
* Interactive Dashboard Design

---

## 📂 Dataset

* **Source:** Deloitte Virtual Experience Program
* **Format:** JSON
* **Time Period:** May 2021
* **Data:** Machine telemetry collected every 10 minutes from four factories.

---

## 📈 Dashboard Features

### Down Time per Factory

* Visualizes total downtime across all factories.
* Helps identify the factory with the maximum downtime.

### Down Time per Device Type

* Displays downtime by machine category.
* Dynamically updates based on the selected factory.

### Interactive Dashboard

* Factory chart acts as a filter.
* Selecting a factory automatically updates the device-type breakdown.

---

## ⚙️ Data Processing

A calculated field named **Unhealthy** was created.

Logic:

* If machine status = **Unhealthy**
* Assign value **10**
* Otherwise assign **0**

Since telemetry is generated every 10 minutes, each unhealthy record represents **10 minutes of potential machine downtime**.

---

## 📊 Key Insights

* Identified the factory with the highest downtime.
* Determined which machine types experienced the most failures.
* Built an interactive dashboard for quick operational analysis.

---

## 📁 Repository Structure

```
Daikibo-Telemetry-Dashboard/
│
├── Dashboard Screenshot.png
├── Daikibo Dashboard.twb
├── README.md
└── assets/
    └── dashboard.png
```

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Tableau Dashboard Development
* Calculated Fields
* Interactive Filters
* Business Intelligence
* Manufacturing Data Analysis
* Data Storytelling
*KPI visualization

⭐ If you found this project interesting, feel free to star the repository.
👩‍💻 Author
Syed Gulshan
B.Tech (Artificial Intelligence & Data Science)
LinkedIn: https://www.linkedin.com/in/syed-gulshan-490a66390


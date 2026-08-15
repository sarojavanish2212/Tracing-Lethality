
# Tracing Lethality – Power BI Analytics Dashboard

## 📊 Project Overview

**Tracing Lethality** is a Power BI data analytics project that explores weapon-related datasets from both a broad armament collection and historical **Maratha weaponry**.

The main goal of the project is to turn raw weapon data into meaningful visual insights. It looks at factors such as **attack power, range, weight, durability, armor penetration, training complexity, and lethality** to understand how weapon characteristics changed over time.

The dashboard covers **1,000 global weapon records** and **495 historical Maratha weapon records from 1650–1800**.

---

## 🎯 Objectives

* Analyze important weapon characteristics such as attack power, range, weight, and armor penetration.
* Compare different weapon types, materials, and rarity levels.
* Study the historical development of Maratha weaponry between **1650 and 1800**.
* Identify patterns in lethality and damage potential.
* Classify weapons into **Lethal / Not so Lethal** and **Danger / Not so Danger** categories.
* Present the analysis through an interactive Power BI dashboard.

---

## 🗂️ Dataset

The project uses data retrieved from **Kaggle** and works with two main datasets:

### 1. Weapons Dataset

This dataset contains general weapon information, including:

* Weapon ID
* Weapon Type
* Material
* Rarity
* Attack Power
* Durability
* Range
* Danger Category

The dataset contains **1,000 weapon records**.

### 2. Maratha Weapons Dataset

This dataset focuses on historical Maratha weaponry and contains information such as:

* Weapon Name
* Era / Year
* Length
* Weight
* Range
* Cost
* Lethality / Damage Potential
* Training Complexity
* Armor Penetration
* Lethal Status

## The project analyzes **495 Maratha historical records covering 1650–1800**.

## 📑 Dashboard Pages

### Page 1 – Quantitative Overview & Material Analysis

This page provides a high-level view of the complete weapon dataset.

It includes:

* Total number of weapons
* Weapon type distribution
* Material distribution
* Rarity classification
* Comparison of range, durability, and attack power
* Weapon performance across different categories

Materials such as **Titanium, Composite, Bronze, and Steel** are highlighted in the analysis.

### Page 2 – Historical Focus & Tactical Metrics

This page focuses on historical Maratha weaponry.

It includes:

* Damage potential
* Lethality comparison
* Historical weapon specifications
* Weapon weight and length
* Range and cost
* Battlefield role distribution

Weapons analyzed include examples such as **Firangi, Talwar, Cannon, Gurz, Bhala, Musket, and Wagh Nakhe**.

### Page 3 – Historical Timeline & Performance Trade-offs

This page explores how weapon characteristics changed across different historical periods.

The dashboard tracks:

* Lethality / Damage Potential
* Training Complexity
* Armor Penetration
* Lethal vs. Not so Lethal classification
* Historical trends from **1650 to 1800**

This makes it easier to identify relationships and changes in weapon performance over time.

---

## 🛠️ Tools & Technologies

The project was developed using:

* **Microsoft Power BI Desktop** – Dashboard development and interactive visualization
* **Power Query (M)** – Data cleaning, transformation, and preparation
* **DAX** – KPIs, calculations, and analytical measures
* **Python / R** – Support for statistical analysis and custom visualizations

The project uses Power Query for ETL operations, DAX for analytical calculations, and Power BI for the final dashboard.

---

## 🧹 Data Preparation

Before building the dashboard, the datasets were prepared through several steps:

1. Standardized numeric fields such as length, weight, and range.
2. Cleaned categorical fields such as weapon type, material, and rarity.
3. Handled missing values.
4. Standardized physical measurement units.
5. Created classifications for **Danger / Not So Danger** and **Lethal / Not so Lethal**.
6. Prepared the data for visualization and analysis.

---

## 📈 Key Findings

Some important findings from the dashboard include:

* **1,000** weapons were analyzed in the global dataset.
* **495** historical Maratha weapon records were analyzed.
* **369** global weapons were classified as Danger, while **631** were classified as Not So Danger.
* The Maratha dataset contained **295 Lethal** and **200 Not so Lethal** weapons.
* Cannon, Firangi, Musket, Shamsher, and Talwar showed high damage potential in the analysis.
* Titanium, Composite, Bronze, and Steel were among the dominant materials.
* The historical analysis showed higher lethality during periods including **1680–1720** and **1740–1760**.

---

## 💡 What I Learned

This project helped me understand how raw datasets can be transformed into an interactive analytical dashboard.

While working on the project, I gained practical experience in:

* Data cleaning with Power Query
* Data transformation and feature engineering
* Creating calculated measures using DAX
* Building interactive Power BI dashboards
* KPI creation
* Exploratory Data Analysis
* Historical trend analysis
* Comparing multiple metrics through visualizations
* Turning complex datasets into easy-to-understand insights

---

## 🚀 How to Use the Project

1. Download and install **Microsoft Power BI Desktop**.
2. Open the `Tracing lethality(2).pbix` file.
3. Allow Power BI to load the associated data if prompted.
4. Explore the three dashboard pages.
5. Use the available filters and visuals to compare weapons, materials, historical periods, and lethality classifications.
6. Interact with the charts to investigate different patterns in the dataset.

---

## 📁 Project Files

```text
Tracing-Lethality/
│
├── Tracing lethality(2).pbix
├── Tracing Lethality documentation.docx
└── README.md
```

---

## 👨‍💻 Project Information

**Project Name:** Tracing Lethality
**Student:** Avanish Saroj
**Student ID:** AF05200613
**Batch Code:** ANP-D6212
**Project Guide:** Ms. Maseera Shaikh

---

## 📌 Conclusion

**Tracing Lethality** demonstrates how Power BI can be used to transform large and complex weapon datasets into an interactive analytical experience. The project combines general weapon statistics with historical Maratha weapon records to study performance, material usage, lethality, and historical trends.

The final dashboard provides a structured way to explore the data and understand relationships between different weapon characteristics rather than relying only on raw tables and numbers.

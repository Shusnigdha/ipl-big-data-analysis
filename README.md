# 🏏 IPL Big Data Analysis using PySpark

## 📌 Project Overview

This project performs **large-scale data analysis on Indian Premier League (IPL) datasets** using **Apache Spark and PySpark**. The goal is to explore player performance, team success, and match trends by processing ball-by-ball match data and generating meaningful insights.

Using **distributed data processing with PySpark**, the project demonstrates how large sports datasets can be cleaned, transformed, analyzed, and visualized to extract valuable insights.

---

## ⚙️ Technologies Used

* **Python**
* **PySpark (Apache Spark)**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook / Google Colab**

---

## 📂 Dataset used

The analysis is based on IPL datasets containing ball-by-ball match information and player details.

Files used in this project:

* `Ball_By_Ball.csv` – Ball-by-ball delivery data
* `Match.csv` – Match-level information (season, teams, winner)
* `Player.csv` – Player details
* `Team.csv` – Team information
* `Player_match.csv` – Player participation data

These datasets together provide detailed information for analyzing **player performance, team success, and match statistics**.

---

## 🧹 Data Processing Steps

The following preprocessing and transformations were performed using **PySpark**:

1. Defined **explicit schema using StructType** for efficient data loading.
2. Loaded datasets into **Spark DataFrames**.
3. Removed **invalid deliveries (wides and no-balls) for accurate batting analysis**.
4. Performed **joins across multiple tables** to enrich player and match information.
5. Applied **aggregations and window functions** for advanced analytics.

---

## 📊 Key Analyses Performed

### 1️⃣ Top Run Scorers

Identified players with the highest total runs across IPL matches.

### 2️⃣ Most Successful Teams

Analyzed match results to determine teams with the highest number of wins.

### 3️⃣ Season-wise Run Trends

Studied how total runs scored vary across different IPL seasons.

### 4️⃣ Top Wicket Takers

Ranked bowlers based on total wickets taken.

### 5️⃣ Boundary Distribution

Analyzed how frequently boundaries (4s and 6s) occur in matches.

### 6️⃣ Season-wise Player Ranking

Used **window functions** to rank players by total runs within each season.

---

## 📈 Data Visualizations

The project includes several visualizations built using **Matplotlib**, such as:

* Bar chart of **Top 10 Run Scorers**
* Line chart showing **Total Runs per IPL Season**
* Horizontal bar chart for **Most Successful Teams**
* Histogram showing **Run Distribution per Ball**

These visualizations help present insights in a clear and intuitive manner.

---

## 📊 Insights

Some insights derived from the analysis include:

* Certain players consistently dominate the **top run-scoring charts** across multiple seasons.
* A small number of teams account for the **majority of IPL match wins**.
* IPL scoring patterns show **increasing total runs across seasons** due to more aggressive batting.
* Most deliveries result in **0 or 1 run**, while boundaries occur less frequently but significantly impact match outcomes.

---

## 🚀 Project Workflow

```
Data Collection
      ↓
Schema Definition
      ↓
Data Cleaning & Preprocessing
      ↓
Spark Transformations & Joins
      ↓
Aggregation & Window Analysis
      ↓
Visualization & Insights
```

---

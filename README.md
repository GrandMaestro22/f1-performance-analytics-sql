# 🏎️ F1 Performance Analytics  
**SQL‑based analysis of Formula 1 driver, constructor, and race performance using a relational motorsport database.**

---

## 📌 Overview  
This project explores historical Formula 1 performance using a structured motorsport dataset.  
The goal is to demonstrate strong SQL skills, relational modeling, and data‑driven storytelling.

The analysis includes:

- Driver performance trends across seasons  
- Constructor dominance cycles  
- Race‑level performance insights  
- Standings analysis and ranking behavior  
- Visualizations generated from SQL query outputs  

---

## 🗂️ Dataset  
The database includes tables for:

- Drivers  
- Constructors  
- Engines, chassis, tyre manufacturers  
- Circuits and Grand Prix  
- Season standings  
- Race standings  

This project uses the **relational F1DB schema**, not the telemetry/pit‑stop dataset.

---

## 🧠 Key SQL Concepts Demonstrated  

- Multi‑table joins  
- Window functions  
- Aggregations and grouping  
- CTEs (Common Table Expressions)  
- Data cleaning and filtering  
- Time‑series analysis  
- Schema exploration  

---

## 📊 Visualizations  
All charts were generated from SQL query outputs using DataGrip.

Examples include:

- Driver points over time  
- Constructor points per season  
- Race finishing position scatter plots  

See the `visuals/` folder for images.

---

## 📁 Repository Structure  

```
data/       → schema diagrams, dataset notes  
sql/        → all SQL queries used in the project  
visuals/    → charts generated from query results  
notebooks/  → analysis notes and commentary  
```

---

## 🚀 How to Reproduce  

1. Download the F1DB relational dataset  
2. Import it into DataGrip (SQLite recommended)  
3. Run the queries in the `sql/` folder  
4. Generate charts from the result grid  

---

## 🧩 Future Work  

- Add predictive modeling features  
- Build a dashboard (Power BI / Tableau)  
- Add driver vs teammate comparisons  
- Add constructor reliability metrics  

---

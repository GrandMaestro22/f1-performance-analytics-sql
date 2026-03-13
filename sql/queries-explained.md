# SQL Queries Explained

This document provides explanations for the SQL queries used in the project. Each query is designed to highlight a specific analytical technique or insight.

---

## 1. Constructor Dominance by Season

**Purpose:**  
Analyze how constructors perform across seasons based on championship points.

**Key Concepts:**  
- Multi-table joins  
- Ordering by season and position  

**Tables Used:**  
- `season_constructor_standing`  
- `constructor`  

---

## 2. Driver Performance Over Time

**Purpose:**  
Track a driver's points across multiple seasons.

**Key Concepts:**  
- Time-series analysis  
- Filtering by driver  

**Tables Used:**  
- `season_driver_standing`  
- `driver`  

---

## 3. Teammate Comparison

**Purpose:**  
Compare teammates within the same constructor and season.

**Key Concepts:**  
- Multi-key joins  
- Aligning standings with team assignments  

**Tables Used:**  
- `season_entrant_driver`  
- `season_driver_standing`  
- `driver`  
- `constructor`  

---

## 4. Race-Level Performance

**Purpose:**  
Analyze finishing positions and points at the race level.

**Key Concepts:**  
- Race metadata joins  
- Sorting by round  

**Tables Used:**  
- `race`  
- `race_driver_standing`  
- `driver`  

---

## Notes

Each query is written to be compatible with the relational F1DB schema.  
Some queries may require minor adjustments depending on the SQL engine (SQLite, MySQL, etc.).

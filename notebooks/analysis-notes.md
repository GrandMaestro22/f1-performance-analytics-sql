# Analysis Notes

This document contains high-level commentary and observations made during the analysis process.

---

## Initial Exploration

The relational F1DB schema is highly normalized, requiring careful joins to extract meaningful insights. Early exploration focused on identifying key relationships:

- Drivers to constructors via `season_entrant_driver`
- Standings linked by `driver_id` and `year`
- Constructor performance via `season_constructor_standing`

---

## Insights Identified

### 1. Constructor Dominance Cycles
Certain eras show clear dominance patterns (e.g., long stretches of consistent constructor performance). Points data reveals competitive vs non-competitive seasons.

### 2. Driver Consistency
By plotting driver points over time, patterns emerge around consistency, peak performance years, and decline phases.

### 3. Teammate Dynamics
Teammate comparisons highlight:
- Drivers outperforming teammates consistently  
- Constructors with balanced vs unbalanced driver lineups  
- Seasonal shifts in driver performance  

---

## Visualization Strategy

Charts were generated directly from SQL query results using DataGrip.  
Recommended chart types:

- Line charts for time-series trends  
- Bar charts for teammate comparisons  
- Scatter plots for race finishing positions  

---

## Future Directions

- Add deeper statistical analysis (variance, deltas, correlations)  
- Build a dashboard in Power BI or Tableau  
- Integrate machine learning for predictive modeling  
- Expand analysis to include constructor components (engine, chassis, tyres)  

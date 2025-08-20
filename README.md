# SQL-DATA-ANALYTICAL-PROJECT
SQL DATA ANALYTICS for productive and auditable worflow

---

A modular SQL project designed to explore, analyze, and report on structured data using best practices in query design, performance tracking, and layered analysis. Each script builds upon the previous, forming a reproducible and auditable workflow.

---

## 🧭 Objectives

- Initialize and explore the database schema  
- Perform dimensional and range-based data profiling  
- Conduct analytical deep-dives: magnitude, ranking, time-based change, cumulative trends  
- Segment data and analyze part-to-whole relationships  
- Generate final reports for key business entities (customers, products)

---
# ANALYTICAL STRUCTURE

![Data Architecture](docs/DATA_ARCHITECTURE.png)

---

## 🗂️ Repository Structure

| File | Purpose |
|------|---------|
| `00_init_database.sql` | Create and initialize database |
| `01_database_exploration.sql` | Schema and table overview |
| `02_dimensions_exploration.sql` | Categorical profiling |
| `03_data_range_exploration.sql` | Range and distribution checks |
| `04_measures_exploration.sql` | Numeric column profiling |
| `05_magnitude_analysis.sql` | Absolute value comparisons |
| `06_ranking_analysis.sql` | Top-N and percentile ranking |
| `07_change_over_time_analysis.sql` | Time series trends |
| `08_cumulative_analysis.sql` | Running totals and accumulation |
| `09_performance_analysis.sql` | Efficiency and throughput checks |
| `10_data_segmentation.sql` | Group-wise analysis |
| `11_part_to_whole_analysis.sql` | Contribution and share metrics |
| `12_report_customers.sql` | Final customer insights |
| `13_report_products.sql` | Final product insights |

---

## 🛠️ Tech Stack

- SQL (ANSI-compliant)  
- Layered query logic (Bronze → Silver → Gold)  
- Execution time logging and error handling (where applicable)

---

## 🚀 How to Use

1. Run scripts sequentially from `00_` to `13_`  
2. Ensure database connection and permissions are configured  
3. Review outputs in your SQL IDE or export results as needed

---

## 📌 Highlights

- Modular script design for clarity and reuse  
- Consistent naming and formatting across all queries  
- Ready-to-integrate with BI tools or reporting layers

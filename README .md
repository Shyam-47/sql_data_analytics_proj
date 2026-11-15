# 📊 SQL Data Analytics Project

An advanced SQL data analytics repository showcasing business intelligence techniques such as changes over time, cumulative aggregations, performance analysis, data segmentation, and part-to-whole analysis.

---

## 📁 Repository Structure

* **02_datasets/**: Contains data backups (`DataWarehouseAnalytics.bak`) and raw CSV files for database loading.
* **03_scripts/**: Contains SQL scripts for database initialization, exploratory data analysis, and advanced analytics queries.
* **LICENSE**: Project license terms (MIT License).

---

## ⚙️ Getting Started

### Database Setup
You can set up the database using either of the following methods:

1. **Database Restore (Recommended):** Restore `02_datasets/DataWarehouseAnalytics.bak` directly using SQL Server Management Studio (SSMS) *(Requires SQL Server 2022 or newer)*.
2. **Build from Source CSVs:** Execute the initialization script in `03_scripts/` to construct the database schema and populate tables directly from `02_datasets/csv_files/`.

---

## 🗺️ Project Scope & Analytical Techniques

This project demonstrates various core data analysis patterns using **T-SQL**:
- **Changes Over Time:** Tracking trends, periodic growth, and time-series metrics.
- **Cumulative Analysis:** Running totals and moving averages.
- **Performance Analysis:** Evaluating performance benchmarks across dimensions.
- **Data Segmentation:** Grouping customers and products into behavioral tiers.
- **Part-to-Whole Analysis:** Measuring individual contributions against totals.

---

## 🛡️ License
Distributed under the [MIT License](LICENSE).

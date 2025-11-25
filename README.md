# Bright Motors — Car Sales Analysis

**Project:** Bright Motors — Car Sales Analysis (Case Study)

**Purpose:** Deliver actionable sales and inventory insights to the new Head of Sales using the Bright Motors historical car sales dataset.

**Author:** Sne Phewa
**Date:** 2025-11-24

---

## Repository structure

(See folder list at the repo root.)

---

## Summary of what was done

This project ingests the Bright Motors vehicle sales dataset, performs ETL and cleaning, computes revenue and profit metrics, analyzes pricing, mileage and region trends, and produces a presentation and dashboard with recommendations to increase dealership profitability.

---

## Tools used

- SQL (Snowflake / MySQL / PostgreSQL — SQL scripts included)
- Microsoft Excel (pivot tables & charts)
- Power BI (dashboard, optional)
- Miro (architecture diagram)
- PowerPoint / Canva (final presentation)

---

## How to run

1. Place the raw CSV into `1. Project Description & Raw Data/bright_car_sales_raw.csv`.
2. Run the SQL script `3. Data Processing/car_sales_queries.sql` on your chosen SQL engine. The SQL contains CREATE TABLE, data cleaning, and transformation queries.
3. Export transformed table to `car_sales_processed.xlsx` for Excel/Pivot/Power BI.
4. Open the presentation `4. Project Presentation/BrightMotors_Presentation.pdf`.

---

## Key findings (high level)

- Top revenue-generating makes & models
- Price is negatively correlated with mileage, positive with year
- Regions A, B, C show highest sales volume (see dashboard for exact cities/provinces)
- Recommendations: Optimize inventory mix toward high-margin models, localized marketing in high-sales provinces, implement dynamic pricing for older high-mileage inventory.

---

## Files of interest

- `3. Data Processing/car_sales_queries.sql` — SQL queries and transformations.
- `2. Project Planning/Miro_Architecture_Diagram.png` — ETL & architecture.
- `4. Project Presentation/BrightMotors_Presentation.pdf` — final narrative + slides.

---

## Contact

For questions or to request reproducible scripts and PBIX, contact: [your email]

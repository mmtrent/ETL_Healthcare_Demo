# Healthcare ETL Demo

An end-to-end data pipeline built in SSIS that extracts de-identified healthcare encounter data from CSV files, transforms it into a star schema (`DimPatient`, `DimProvider`, `DimLocation`, `FactEncounter`), and loads it into a SQL Server data warehouse for Power BI or Tableau reporting.

---

## 🧱 Architecture

CSV (source) → SSIS (ETL) → SQL Server (Docker) → Power BI/Tableau (visualization)

---

## Technologies

- **SQL Server 2022** (Docker)
- **SQL Server Integration Services (SSIS)**  
- **Visual Studio 2022**  
- **Power BI / Tableau** for dashboards
- **Git + GitHub** for version control

---

## Project Structure
healthcare-etl-demo/
├─ data/ # Sample CSVs
├─ sql/ # DDL scripts & quality checks
├─ ssis/ # .dtsx packages
├─ reports/ # Power BI / Tableau dashboards
└─ README.md
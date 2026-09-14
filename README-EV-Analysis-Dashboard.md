# ⚡ Electric Vehicle (EV) Analysis Dashboard (Tableau)

An interactive Tableau dashboard exploring electric vehicle population data — makes, models, vehicle types, and adoption trends by state, county, and year.

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

## 📊 Overview

`Dashboard 1` combines five worksheets analyzing registered electric vehicles, filterable by make/model.

## 📄 Worksheets

| Worksheet | What it shows |
|---|---|
| Make & Model | Vehicle counts by make and model |
| Map | Geographic distribution of EVs by state/county |
| Top 10 country | Top locations by EV count |
| Vehicle Type Donut | Split between EV types (e.g., BEV vs. PHEV) |
| Year and Type | EV registrations by model year and type |

## 🔑 Key Fields

`Make`, `Car Make`, `Electric Vehicle Type`, `Model Year`, `State`, `County`, `Postal Code`, `DOL Vehicle ID` — filterable via a make/model parameter.

## 🗂️ Data Source

Connects to an `Electric_Vehicle_Population_Data.xlsx` workbook via an Excel connection (based on the public [Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data) dataset).

> ⚠️ **Heads up:** this `.twb` file stores only the *workbook definition* — it points to the source Excel file by its original local file path, not to embedded data. To make this fully portable for anyone who downloads it from GitHub:
> - Include `Electric_Vehicle_Population_Data.xlsx` in this repo alongside the `.twb`, **or**
> - Re-save the file in Tableau as a **packaged workbook (`.twbx`)** via *File → Export Packaged Workbook*, which bundles the data inside a single file.
> Otherwise, Tableau will prompt to relocate the data source when opened on another machine.

## 🚀 How to Use

1. Download `EV_Analysis__Dashboard.twb` (and the Excel data file, or the `.twbx` version if provided).
2. Open it in [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Reader](https://www.tableau.com/products/reader) (free, view-only).
3. If prompted, reconnect the data source to wherever you saved the Excel file.
4. Use the parameter filter to explore by make/model.

## 📸 Preview

<!-- Add a screenshot here, e.g.: -->
<!-- ![Dashboard preview](screenshots/dashboard.png) -->

## 👤 Author

[Kunal](https://github.com/KKunal-007)

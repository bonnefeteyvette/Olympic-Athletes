# Olympic Athletes Project – Data

## 📁 Repository Purpose

This repository stores the data files used in and generated by the Olympic Athletes scraping and analysis project.

It is structured into:

- `raw/`: Contains unprocessed, directly scraped data.
- `processed/`: Contains cleaned and transformed datasets ready for analysis.
- `README.md`: Describes the contents and data format.

## 📊 Datasets Included

1. **biographical-data.csv** – Raw scraped biographical information for athletes.
2. **EVENT RESULT DATA.csv** – Raw scraped performance data.
3. **biographical-data cleaned.csv** – Cleaned biographical dataset with structured fields (DOB, height, etc.).
4. **event result cleaned.csv** – Cleaned competition results with standardized columns (year, event, medal, etc.).

## 🧼 Data Cleaning Notes

- Bullet characters (•) have been replaced with spaces.
- `Measurements` column split into `Height (cm)` and `Weight (kg)`.
- `Pos` column cleaned to extract numeric rankings and tied status.
- `Games` split into `Year` and `Season`.

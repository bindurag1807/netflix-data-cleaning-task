# Netflix Dataset - Data Cleaning Task (Excel)

## 🔧 Tools Used:
- Microsoft Excel

## 🧹 Cleaning Steps Performed:
- Replaced missing values in `country`, `director`, and `cast` with "Unknown"
- Removed duplicate rows using "Remove Duplicates"
- Standardized:
  - `country` using TRIM + PROPER
  - `rating` using TRIM + UPPER
- Converted `date_added` to uniform `dd-mm-yyyy` format
- Used "Text to Columns" to split `duration` into:
  - `duration_value` (numeric)
  - `duration_unit` (min, Season, etc.)
- Renamed all column headers to lowercase with underscores


## 📄 Download the Cleaned Netflix Dataset

You can download the cleaned dataset using the link below:

[📥 Download netflix_titles_cleaned.xlsx](./netflix_titles_cleaned.xlsx)



# Data Cleaning Documentation
## Project: Law and Justice – IPC Crimes Dataset
This document describes all data cleaning steps performed on the Law and Justice dataset
before analysis and visualization.

---
## 1. Standardizing Column Names
Column names were standardized to ensure consistency and ease of use.
Actions taken:
- Removed special characters (/, &, etc.)
- Replaced spaces with underscores
- Converted headers to proper format
Example:
STATE/UT → State
UT
_
TOTAL IPC CRIMES → Total
_
Ipc
_
Crimes
Reason:
Standardized names simplify formulas and pivot table creation.
---
## 2. Find & Replace Values
Inconsistent or unclear values were corrected.
Actions:
- Replaced inconsistent state names (e.g., DELHI/UT Total → Delhi)
- Checked placeholder values
Note:
Numeric crime counts were kept as numbers (0 retained as valid data).
Reason:
Ensures consistency and prevents grouping errors.
---
## 3. Removing Duplicates
Duplicate records were identified and removed using Google Sheets’ Remove Duplicates tool.
Reason:
Prevents double counting and improves accuracy.

---
## 4. Datatype Correction
Columns were converted to appropriate formats.
Actions:
- Year column set to numeric
- Crime columns formatted as numbers
Reason:
Correct datatypes are required for calculations and charts.
---
## 5. Case Standardization
Uppercase text converted to Proper Case.
Example:
DELHI → Delhi
UTTAR PRADESH → Uttar Pradesh
Reason:
Improves readability and consistency.

---
## 6. Removing Rare Crime Columns
Columns with minimal or mostly zero values were dropped.
Examples:
- Importation of Girls
- Custodial Rape
Reason:
Low-variance columns added limited analytical value.
---
## 7. Total Crime Column Added
A total crime column was created using SUM across crime categories.
Reason:
Allows quick analysis of overall crime trends.

---
## 8. Sorting by State/UT
Dataset sorted by State and Year.
Reason:
Improves organization and readability.

---
## 9. Updating District Names
District names were updated from older names to current names where applicable.
Reason:
Ensures modern and recognizable naming.

---
## 10. Merging District Names
Split districts were merged by summing their values.
Example:
Kutch (East(G)) + Kutch (West-Bhuj) → Kutch
Reason:
Avoids fragmentation and ensures accurate totals.

---
## 11. State and District Name Consistency
Standardized naming across dataset.
Example:
A&N Islands → Andaman and Nicobar Islands
Reason:
Ensures proper grouping in analysis.

---
All cleaning was performed using Google Sheets tools and formulas.
## SEC - A , G - 2 

# 📊 Crime Trend & Risk Analysis Across Indian States (2001–2012)

## 🏛 Sector
Law & Justice

---

# 📌 Project Overview

This project analyzes district-wise IPC crime data across India from 2001 to 2012 to identify crime trends, hotspots, and growth patterns.  

The goal is to support **data-driven policing and resource allocation** by helping decision-makers detect high-crime regions and fast-growing crime areas.

Key stakeholders include:
- State Home Departments  
- Police Commissioners  
- District-level law enforcement  

The final output is an **interactive Google Sheets dashboard** for executive decision support.

---

# 📂 Dataset Information

**Source:** Kaggle – Crime in India Dataset  
**Time Period:** 2001–2012  
**Districts Covered:** 803  
**Rows:** 8,596  

---

# 📘 Data Dictionary

| Column | Description |
|--------|------------|
| Year | Reporting year |
| State/UT | State or Union Territory |
| District | District name |
| Murder | Murder cases reported |
| Rape | Rape cases reported |
| Robbery | Robbery cases |
| Theft | Theft cases |
| Hurt/Grievous Hurt | Physical injury crimes |
| Other IPC Crimes | Miscellaneous IPC crimes |
| Total Crimes | Sum of all IPC crimes |

---

# 🧹 Data Cleaning Notes

The dataset required preprocessing before analysis:

- Standardized column names  
- Corrected inconsistent casing  
- Removed duplicates  
- Fixed data types  
- Merged district naming variations  
- Dropped low-impact crime columns  
- Created Total Crimes KPI  
- Sorted dataset for consistency  

All cleaning was performed in Google Sheets.

---

# 🔍 Key Insights & Statistics

- Total IPC crimes increased from ~4.9M (2001) to ~6.3M (2012)  
- 4,02,543 murder cases recorded (2001–2012)  
- 2,39,137 rape cases recorded  
- Top 10 districts contribute disproportionately to total crimes  
- Property crimes form the largest share of total crimes  
- Crimes against women show steady growth  
- Some lower-volume states show high growth rates (early-warning signals)

---

# 📊 Dashboard Summary

The dashboard includes:

### Executive View
- KPI Cards (Murders, Rapes, YoY Growth)  
- National crime trend  
- Top crime-contributing states  

### Operational View
- Crime type comparisons  
- Offense mix by year  
- Fastest rising states  
- Top 10 district hotspots  

### Interactivity
- Year slicer  
- State/UT slicer  

---

# 🖼 Dataset Analysis Screenshots

*(Insert dashboard screenshots here)*

Examples:
- Dashboard Overview  
- KPI Section  
- Crime Trend Charts  
- Top 10 Districts Chart  

---

# ⚠ Limitations

- Data only till 2012  
- No population-adjusted crime rates  
- Possible reporting bias  
- No socio-economic variables  

---

# 🚀 Future Improvements

- Add recent data  
- Include population normalization  
- Use predictive modeling  
- Integrate real-time feeds  

---

# 👥 Team Members

- Samarth Sangtani  
- Vani Rudra  
- Kushal Sarkar  
- Aryan Yadav  
- Vriha Dholiya  
- Vaibhav  

---

# ✅ Conclusion

This project transforms historical crime records into a structured decision-support system.  

By combining trend, growth, and hotspot analysis, the dashboard enables **data-driven policing and targeted intervention planning.**
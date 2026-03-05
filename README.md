# BMW RPA Project

## Project Overview
This is a beginner-level RPA (Robotic Process Automation) project using Python and Pandas. 
The goal is to automate data processing and reporting for BMW global deliveries, premium segment share, EV penetration, and macroeconomic indicators from 2018–2025.

The project demonstrates:
- Reading and cleaning Excel/CSV datasets
- Performing basic data analysis
- Generating automated reports in Excel
- Optional: sending reports via email

---

## Dataset
The dataset used includes:
- **Year**: Calendar year of vehicle sales (2018–2025)
- **Month**: Month of sale (1–12)
- **Region**: Sales region (Europe, China, USA, RestOfWorld)
- **Model**: BMW model variant
- **Units_Sold**: Number of vehicles delivered
- **Avg_Price_EUR**: Average price per vehicle
- **Revenue_EUR**: Total revenue
- **BEV_Share**: Battery Electric Vehicle penetration
- **Premium_Share**: BMW’s share in the premium automotive segment
- **GDP_Growth**: Regional GDP growth (%)
- **Fuel_Price_Index**: Fuel price index

> Note: Only sample or anonymized data should be uploaded to GitHub to avoid large files or sensitive information.

---

## Project Workflow
1. Load dataset using Pandas
2. Clean and check missing data
3. Perform data analysis:
   - Total sales per region and year
   - Model-wise sales ranking
   - Average EV and Premium share per region
4. Generate Excel reports in the `reports/` folder

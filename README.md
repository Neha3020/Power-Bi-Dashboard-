# COVID-19 Report 
# 📊 Power BI Report Project on COVID-19 

This repository contains the resources and video walkthrough for a Power BI project where I cleaned raw CSV data and developed an interactive report to uncover insights.

🎥 **Video Walkthrough**: See `assets/Loom-Demo-2025.mp4`  
🗂️ **Data File**: `data/datafile.csv`  
📄 **Report File**: `report/PowerBI_Report.pbix`

---

## 🔧 Project Summary

- **Tool Used**: Power BI Desktop
- **Data Format**: `.csv` 
- **Key Tasks**:
  - Data import and transformation using **Power Query Editor**
  - Data cleaning (null removal, column renaming, data type correction)
  - Creating measures 
  - Designing an interactive **Power BI dashboard** with filters, charts, and cards

---

## 📌 Steps Performed in Power BI

1. **Data Import**:
   - Loaded the raw CSV file into Power BI.

2. **Data Cleaning with Power Query**:
   - Removed unnecessary columns and blank rows.
   - Renamed columns for better readability.
   - Converted data types to match analysis goals.
   - Handled missing/null values.

3. **Data Modeling** :
   - Established relationships .
   - Creating measures using DAX.

4. **Report Building**:
   - Used bar charts, pie charts, KPIs, and slicers.
   - Enabled interactivity with filters (e.g., region, category, date).
   - Applied themes for consistent styling.
  
   ![covid report post](https://github.com/user-attachments/assets/0c2fd3d0-f97d-40a3-9265-615032e3ad60)

###🟥 1. Population vs Total Cases by Country
China has the highest population at 1.15B, followed by India at 0.69B.

United States, Brazil, and Indonesia also have large populations but smaller blocks compared to China and India.

The size of each block suggests that the visual is a TreeMap representing population by country.

📌 Insight: Countries with high populations don't necessarily have proportionally higher case rates, indicating possible underreporting or effective control measures.

###📉 2. GDP per Capita vs COVID Impact (Bar + Line Chart)
Bar Chart shows GDP per Capita by country.

Line Chart overlays % of Total Cases per Million, showing the relative COVID burden.

📌 Key Observations:

Countries like USA, Switzerland, and Norway have higher GDP per capita and also show moderate to high infection rates per million.

Lower-GDP countries generally report fewer cases per million, possibly due to testing/reporting limitations.

###🌍 3. Total Cases by Continent (Map View)
North America, Asia, and Europe dominate in total case counts (large circles).

South America and Africa have smaller but still notable bubbles.

📌 Insight: Geographical spread correlates with global travel, healthcare access, and urban density. The global spread is dense in economically active regions.

###⚰️ 4. Total Deaths & Cases Summary
Total Deaths: 5.94M

Total Cases: 292M

📌 Death Rate:
≈2.03%
This is within expected global mortality estimates.

###🧪 5. Positive Test Rate by Continent
Europe: Highest at 2.85%

Asia: Close behind at 2.74%

Africa and South America: Around 1%

Oceania: Lowest at 0.01%

📌 Insight: Higher test positivity indicates possible undercounting or insufficient testing capacity in high-rate regions like Europe and Asia.

###📈 6. Population & Age Analysis by Continent
Asia has the largest population (~4.6B), followed by Africa and Europe.

Median Age peaks in Europe (high 40s) and dips in Africa (early 20s).

📌 Insight: Older continents (Europe, North America) are at higher risk of severe outcomes; this should inform healthcare and vaccination priorities.

###🧓 7. Aged Population Breakdown (Donut Chart)
Largest group: Population aged 65+ (5.73K units)

Smaller segments for 70+ and 80+

📌 Insight: Countries/regions with larger elderly populations are more vulnerable. This aligns with higher mortality rates in developed countries.






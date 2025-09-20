# NO2-Analysis-Ghana-2025  
Google Earth Engine script for monitoring NO₂ air pollution levels across Ghana (January 2025)  

Nitrogen Dioxide (NO₂) Trends over Ghana  
_A Google Earth Engine Script using Sentinel-5P TROPOMI Data_  

Overview  
This project analyzes atmospheric Nitrogen Dioxide (NO₂) concentration over Ghana using the Sentinel-5P (TROPOMI) dataset.  
The script extracts NO₂ data, converts it to micromole units, generates a **time-series trend chart, and visualizes the spatial distribution for January 2025.  

Dataset  
- Source: [COPERNICUS/S5P/OFFL/L3_NO2](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_OFFL_L3_NO2)  
- Sensor: Sentinel-5P (TROPOMI)  
- Variable: `NO2_column_number_density`  
- Temporal Coverage: January 1 – January 31, 2025  
- Spatial Coverage: Ghana (using USDOS/LSIB_SIMPLE boundaries)  

Methods  
1. Filter dataset by region (Ghana) and date (January 2025).  
2. Convert units from mol/m² to micromole/m².  
3. Generate time-series chart of mean NO₂ levels over Ghana.  
4. Compute mean spatial distribution of NO₂ during the study period.  
5. Visualize results using a custom color palette.  

Outputs  
- Time Series Chart: Daily mean NO₂ (micromole/m²) with linear trendline.  
- Map Visualization: Mean NO₂ concentration across Ghana for January 2025.  

Why This Matters  
Nitrogen Dioxide (NO₂) is a key air pollutant, mainly produced by fossil fuel combustion and industrial activities. Monitoring its trends helps in:  
- Assessing air quality  
- Identifying pollution hotspots 
- Supporting environmental policy and planning 

How to Use  
1. Open [Google Earth Engine Code Editor](https://code.earthengine.google.com/).  
2. Copy and paste the script (`GEE_code`) into the editor.  
3. Run the script to visualize results.  

License  
This project is released under the **MIT License**. You are free to use, modify, and distribute with attribution.  

---

✍️ Author: Emmanuel Boateng 
📅 Date: September 2025

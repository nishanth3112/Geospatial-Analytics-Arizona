# Geospatial Data Analysis and Interactive Visualization  

## 📌 Project Overview  
This project analyzes **51,000+ high-severity traffic crash records (2012–2024)** in **Tempe, Arizona**, leveraging **geospatial data science** and **interactive visualizations** to support transportation safety planning. Using advanced analytics, the project uncovers **crash hotspots, severity patterns, temporal trends, and weather-related risks**, empowering city planners and stakeholders to make **data-driven decisions** aligned with Tempe’s **Vision Zero** initiative.  

---

## 🚦 Objectives  
- Identify **high-risk corridors** and **traffic crash hotspots** across Tempe.  
- Explore **temporal crash dynamics** (seasonal patterns, peak hours, yearly/monthly shifts).  
- Examine **environmental & demographic correlations** (weather, road conditions, driver factors).  
- Build **interactive dashboards** for stakeholders to dynamically explore crash data.  
- Demonstrate the **impact of geospatial analytics** in urban safety and transportation policy.  

---

## 🛠️ Tools & Technologies  
- **Python Libraries:** Pandas, GeoPandas, Plotly, Scikit-learn, Shapely  
- **Clustering & ML:** DBSCAN for hotspot detection, density-based clustering  
- **Visualization:** Interactive dashboards (heatmaps, density maps, treemaps, animated timelines)  
- **Data Sources:** Arizona Department of Transportation (ADOT), City of Tempe Open Data Portal  
- **Deployment:** AWS S3 for hosting interactive web dashboards  

---

## 📊 Key Analyses & Visualizations  
1. **Crash Hotspots** – Identified high-severity clusters along **Southern Ave, Broadway Rd, and University Dr**.  
2. **Temporal Trends** – Evening peak (3–8 PM) identified as the riskiest window.  
3. **Weather Correlations** – Clear weather saw the majority of crashes, highlighting behavioral risk factors.  
4. **DBSCAN Clustering** – Automatically detected latent spatial crash patterns in central and southern Tempe.  
5. **Interactive Dashboards** –  
   - Animated heatmaps (monthly/yearly crash patterns)  
   - Dropdown filters for severity-based crash exploration  
   - Treemaps and bar charts showing **collision types and top 10 risky corridors**  
   - 3D hexbin maps for crash density intensity  

---

## 📊 Key Visualizations  

### 1. Crash Trends Over Time (Animated Heatmap)  
![Crash Trends Heatmap]  <img width="1697" height="892" alt="Screenshot 2025-09-22 at 1 17 42 PM" src="https://github.com/user-attachments/assets/2f0bc759-b777-4a40-a238-efc48724fcb1" />

*Visualizes monthly crash patterns across Tempe, highlighting seasonal and yearly fluctuations.*  

### 2. High-Risk Corridors (DBSCAN Hotspot Clusters)  
![Crash Hotspots](images/dbscan_hotspots.png)  
*DBSCAN clustering uncovers dense crash clusters along major arterial roads, guiding infrastructure improvements.*  

### 3. Peak Hour Crash Density  
![Crash Density by Time](images/crash_density_peak_hours.png)  
*Identifies evening peak (3–8 PM) as the riskiest period, helping allocate enforcement and safety measures.*  

---

## 🚀 Impact & Outcomes  
- Delivered an **interactive crash analysis dashboard** for **policy makers and city planners**.  
- Supported **Vision Zero** by providing **data-driven strategies** to reduce fatalities and serious injuries.  
- Improved transparency and public awareness with **accessible, interactive geospatial visualizations**.  
- Demonstrated how **geospatial analytics + ML clustering** can enhance urban safety interventions.  

---

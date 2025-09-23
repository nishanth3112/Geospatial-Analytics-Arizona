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
<img width="1697" height="892" alt="Screenshot 2025-09-22 at 1 17 42 PM" src="https://github.com/user-attachments/assets/2f0bc759-b777-4a40-a238-efc48724fcb1" />

*Visualizes monthly crash patterns across Tempe, highlighting seasonal and yearly fluctuations.*  

### 2. High-Risk Corridors (DBSCAN Hotspot Clusters)  
<img width="1698" height="867" alt="Screenshot 2025-09-22 at 1 21 03 PM" src="https://github.com/user-attachments/assets/734011a6-1da3-44f8-9f1c-7dc2caa45b23" />

*DBSCAN clustering uncovers dense crash clusters along major arterial roads, guiding infrastructure improvements.*  

### 3. Peak Hour Crash Density  
<img width="1696" height="846" alt="Screenshot 2025-09-22 at 1 19 34 PM" src="https://github.com/user-attachments/assets/432f35e0-9758-4d12-8e74-3809f6b26062" />

*Identifies evening peak (3–8 PM) as the riskiest period, helping allocate enforcement and safety measures.*  

### 4. Treemap — Collision Type × Injury Severity
<img width="1686" height="831" alt="Screenshot 2025-09-22 at 1 24 04 PM" src="https://github.com/user-attachments/assets/1f892b62-3370-4da8-87c0-34f168f5bccd" />

*Hierarchically shows how collision types (e.g., angle, rear-end) distribute across injury severity levels, helping prioritize high-impact crash modes.*

### 5. Bubble Map — Crash Count by Street
<img width="1695" height="847" alt="Screenshot 2025-09-22 at 1 24 57 PM" src="https://github.com/user-attachments/assets/bc45c283-c09e-4b21-ad72-9de5682b64ca" />

*Street-level concentration of crashes, sized by count and positioned geospatially to highlight corridors needing targeted interventions.*

---

## 🚀 Impact & Outcomes  
- Delivered an **interactive crash analysis dashboard** for **policy makers and city planners**.  
- Supported **Vision Zero** by providing **data-driven strategies** to reduce fatalities and serious injuries.  
- Improved transparency and public awareness with **accessible, interactive geospatial visualizations**.  
- Demonstrated how **geospatial analytics + ML clustering** can enhance urban safety interventions.  

---

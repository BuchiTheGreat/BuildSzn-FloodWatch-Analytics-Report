# 🌊 BuildSzn FloodWatch Analytics Report

A comprehensive Data Analytics project examining crowdsourced citizen flood reports, NASA weather severity metrics, and Lagos elevation datasets using Power BI to drive Product Design (PD) decisions.
---

## 📌 Executive Summary
* **Total Citizen Reports:** 78
* **High-Risk Hotspots Identified:** 12
* **Total Survey Respondents:** 37
* **User Retention / Willingness to Report:** 95%
* **Device Split:** 51.4% iOS vs. 48.6% Android

---

## 🛠️ Tool Stack & Methods
* **Power BI Desktop:** Multi-page interactive dashboard development.
* **DAX:** Dynamic measures, distinct counting, and hotspot threshold filtering.
* **Data Cleansing:** Categorical normalization and text-field standardization.

---
## 📊 Dashboard Overview

### Cover Page
Interactive landing portal featuring high-level core KPIs, custom app branding, and seamless multi-page navigation.

![Cover Page](images/Cover%20Page.png)

### Page 1: Flood Risk & Hotspots
Identifies physical hazard points, high-risk corridors (Lekki Phase 1, Surulere, Ajah), and regional residency breakdown.

![Flood Risk & Hotspots](images/Flood%20Risk%20%26%20Hotspots.png)

### Page 2: Weather & Report Correlation
Examines the direct correlation between precipitation spikes and citizen reporting surges using NASA weather telemetry.

![Weather & Report Correlation](images/Weather%20%26%20Report%20Correlation.png)

### Page 3: App Usability & Feedback
Translates connectivity bottlenecks during rain, verification methods, and requested features into product insights.

![App Usability & Feedback](images/App%20Usability%20%26%20Feedback.png)

### Page 4: Executive Summary & Strategic Takeaways
Synthesizes key hazard findings, usability signals, and concrete Product Design (PD) engineering directives.

![Summary & Takeaways](images/Summary%20%26%20Takeaways.png)

---

## 📂 Repository Structure & Datasets

```text
BuildSzn-FloodWatch-Analytics-Report/
│
├── 📁 dashboard/
│   └── 📄 Group 6 DA's BuildSzn Report (FloodWatch).pbix   # Interactive Power BI Dashboard
│
├── 📁 data/
│   ├── 📄 FloodWatch Community Transit & Weather Resilience Survey...csv  # Survey Responses
│   └── 📄 nasa_weather_data.csv                            # NASA Weather Severity Data
│
├── 📁 images/
│   ├── 📄 Cover Page.png                                   # Dashboard Page 1 Preview
│   ├── 📄 Flood Risk & Hotspots Overview.png              # Dashboard Page 2 Preview
│   ├── 📄 Weather & Report Correlation.png                 # Dashboard Page 3 Preview
│   ├── 📄 App Usability & Feedback.png                    # Dashboard Page 4 Preview
│   └── 📄 Summary & Takeaways.png                         # Dashboard Page 5 Preview
│
├── 📁 presentation/
│   ├── 📄 Data Analysis FloodWatch Story.pptx             # Stakeholder PowerPoint Deck
│   └── 📄 Data Analysis FloodWatch Story.pdf              # Slide Deck (PDF for web viewing)
│
├── 📁 python/
│   ├── 📄 extraction of lagos...                          # GIS / Spatial Extraction Script
│   ├── 📄 gis_osm_roads_fre...                            # OSM Road Network Processing
│   └── 📁 python scripts/                                 # Data Cleaning & Transformation
│
└── 📄 README.md                                           # Case Study Documentation
```
* 📌 **Lagos Elevation Dataset:** Due to GitHub's 25MB file size limit, the full `lagos_elevation.csv` dataset is hosted on [Google Drive](https://drive.google.com/file/d/10XRtgp46yk90CwwgxYDbgvJ7d8J4Cl8p/view?usp=sharing).


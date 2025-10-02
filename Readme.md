# 🌊 Urban Pluvial Flood Risk: A Data-Driven Analysis

## 📋 Project Overview
This project analyzes **urban pluvial flood risk** using geospatial, environmental, and infrastructure data.  
The goal is to uncover **key risk factors** and build an **interactive Power BI dashboard** to help city planners and stakeholders make informed decisions.

---

## 🎯 Objectives
- 🔎 **Analyze Key Factors** – Perform **Exploratory Data Analysis (EDA)** on the flood risk dataset.  
- 📊 **Uncover Insights** – Identify patterns in **land use, drainage density, and rainfall**.  
- 🌐 **Visualize the Risk** – Create an **interactive dashboard** for stakeholders.  

---

## 📊 Dataset
**Source:** `urban_pluvial_flood_risk_dataset.csv`  

### Key Features:
- **Geospatial:** Latitude, Longitude, Elevation (m)  
- **Infrastructure:** Land Use, Drainage Density (km/km²), Storm Drain Type  
- **Environmental:** Soil Group, DEM Source  
- **Meteorological:** Historical Rainfall Intensity (mm/hr), Return Period (Years)  
- **Target:** Risk Labels (ponding_hotspot, monitor, etc.)  

---

## 🔑 Key Insights
- 🏘️ **Residential areas dominate** → most vulnerable zones.  
- 💧 **Low drainage density strongly correlates** with high flood risk.  
- ⚠️ **Critical hotspots** combine low elevation, sparse drainage, and extreme rainfall history.  

---

## 📊 Dashboard Features
- 🗺️ **Interactive Map** → Visualize hotspots by city/ward.  
- 🎚️ **Dynamic Filters** → Explore by land use, drainage type, and risk level.  
- 📈 **KPIs & Charts** → Average rainfall, high-risk segments, land-use breakdown.  

---

## 📌 Impact
- 🏗️ **Urban Planning:** Prioritize drainage upgrades.  
- 🚨 **Preparedness:** Guide emergency resource allocation.  
- 📜 **Policy:** Evidence-based foundation for flood resilience planning.  

---

## 👥 Team
**Team ARYA**  
- Rudra Pratap Singh Rathore  
- Ayush Pratap Singh  
- Yashpal  

---

## ⚙️ Installation Instructions

### 1. Prerequisites
Make sure you have installed:
- 🐍 **Python 3.8+** → [Download Python](https://www.python.org/downloads/)  
- 🛠️ **Git** → [Download Git](https://git-scm.com/)  
- 📊 **Power BI Desktop** → [Download Power BI](https://powerbi.microsoft.com/desktop/)  

---

### 2. Clone the Repository
```bash
git clone https://github.com/USERNAME/urban-flood-risk-analysis.git
cd urban-flood-risk-analysis
````

---

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
# Activate environment
venv\Scripts\activate       # Windows
source venv/bin/activate    # Mac/Linux
```

---

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

*(Recommended packages: pandas, numpy, matplotlib, seaborn, plotly, scipy, jupyter)*

---

### 5. Run Jupyter Notebook for Analysis

```bash
jupyter notebook
```

Open the notebooks in the **`notebooks/`** folder to explore data cleaning, analysis, and insights.

---

### 6. Open Dashboard

* Open **`dashboard/FloodRiskDashboard.pbix`** in Power BI Desktop.
* Load the processed dataset: **`data/processed/flood_risk_cleaned.csv`**.
* Explore interactive maps, filters, KPIs, and charts.

---

## 📄 Project Structure

```
urban-flood-risk-analysis/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── processed/            # Cleaned and preprocessed dataset
│
├── notebooks/                # Jupyter notebooks for analysis
├── src/                      # Python scripts for preprocessing and visualizations
├── dashboard/                # Power BI dashboard and screenshots
├── outputs/                  # Figures, reports, and insights
├── presentation/             # PPT for stakeholders
├── requirements.txt          # Python dependencies
└── README.md                 # Project overview and instructions
```

---

## 📈 Usage

* Explore the EDA notebooks to understand patterns in flood risk.
* Use the dashboard for **decision-making** in urban planning.
* Reference insights for **policy recommendations** and **infrastructure improvements**.

---

## 🔐 Data Privacy & Ethics

* Dataset is **anonymized** for educational purposes.
* No individual-level personal data is included.
* Intended only for **policy analysis, urban planning, and academic study**.

---

## 📚 References

1. IPCC. (2021). *Climate Change and Urban Flooding*
2. World Bank. (2020). *Urban Flood Risk Management: A Toolkit*
3. UN-Habitat. (2022). *Cities and Climate Change Initiative*
4. Kaggle. Urban Flood Risk Data (Pratyush Puri)

---

## 🚀 Next Steps / Future Enhancements

* Implement a **machine learning model** for flood risk prediction.
* Conduct **time-series analysis** on rainfall events.
* Integrate **real-time monitoring** with IoT sensors.
* Develop a **mobile dashboard** for on-field city planners.

---

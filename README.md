## Project Overview

These two capstone projects completed during the Master of Data Science program at Deakin University. Each project focuses on analyzing and predicting transportation demand patterns using real-world urban data.

---

## 📁 Project Structure

```
capstone-projects/
├── Capstone_Project_1/              # Capstone Project 1: Travel Demand Prediction (2024)
│   ├── UC00079_Tourism_Impact_Analysis.ipynb    # Main analysis notebook
│   ├── UC00079_Tourism_Impact_Analysis.html     # HTML report
│   ├── UC00079_Tourism_Impact_Analysis.json     # Project metadata
│
├── Capstone_Project_2/              # Capstone Project 2: Public Transport Demand Analysis (2025)
│   ├── UC00132_Public_Transport_Demand (1).ipynb   # Main analysis notebook
│   ├── UC00132_Public_Transport_Demand.html        # HTML report
│   ├── UC00132_Public_Transport_Demand.json        # Project metadata
│
└── README.md                        # This file
```

---

## 🚀 Project 1: Travel Demand Prediction (2024)

### Project Overview
**Objective:** Estimate total tourism demand (domestic + international visitors) 
across Melbourne CBD using pedestrian sensor data and available domestic tourist statistics.

**Challenge:** While domestic tourist data was readily available, international 
visitor numbers were not directly accessible.

**Solution:** Leveraged the correlation between pedestrian counts and domestic 
tourist numbers to estimate international visitor demand, providing a complete 
picture of regional tourism patterns.

---

### 📊 Methodology & Key Visualizations

#### 1. Correlation Analysis (Foundation)
<p align="center">
  <img src="https://github.com/user-attachments/assets/b057b76d-8992-46e3-8c60-0c72c29fc638" width="700">

  <br>
  <em><strong>Core Analysis:</strong> Strong positive correlation (r=0.85) between 
  pedestrian sensor counts and domestic tourist numbers. This relationship enabled 
  estimation of total visitor demand including international tourists.</em>
</p>

**Key Insight:** The consistent ratio between pedestrian activity and domestic 
visitors allowed us to extrapolate total tourism demand with high confidence.

---

#### 2. Spatial Distribution - Sensor & Attraction Mapping
<p align="center">
  <img src="https://github.com/" width="700">
  <br>
  <em>Melbourne CBD showing pedestrian sensor locations (blue dots) and major 
  tourist attractions (green markers). Haversine distance used to map sensors 
  within 200m radius of attractions.</em>
</p>

---

#### 3. Tourist Concentration Zones (Results)
<p align="center">
  <img src="https://github.com/" width="700">
  <br>
  <em>K-means clustering identified four distinct tourist concentration zones 
  based on estimated total visitor demand. Cluster analysis revealed Swanston 
  Street and Flinders Street Station areas as primary tourist hotspots.</em>
</p>

---

### Key Features
- **Data Integration**: Combined regional pedestrian counts with domestic traveler statistics
- **Demand Prediction Model**: Developed machine learning models for tourism demand estimation
- **Clustering Analysis**: Identified tourist concentration patterns using K-means and other algorithms
- **Spatial Analysis**: Mapped tourist attractions to pedestrian sensors using Haversine distance

### Tech Stack
- **Languages**: Python
- **Key Libraries**: Pandas, Scikit-learn, Numpy
- **Analysis Techniques**: K-means Clustering, Haversine Distance
- **Data Sources**: Melbourne Open Data API
- **Visualization**: Matplotlib, Seaborn

### Key Results
- Identified regional clusters with high tourism demand
- Analyzed tourist flow patterns using pedestrian sensor data
- Built predictive models for regional tourism demand

---

## 🚌 Project 2: Public Transport Demand Analysis (2025)

### Project Goals
Analyze pedestrian sensor data and public transport infrastructure in Melbourne CBD to understand transport demand and identify key influencing factors.

### Key Features
- **Data Collection**: Collected Melbourne pedestrian sensor, train station, and bus stop data via APIs
- **Data Preprocessing**: Cleaned and transformed large-scale time-series data
- **Map Visualization**: Created interactive maps using Folium to visualize pedestrian flows
- **Pattern Analysis**: Analyzed pedestrian patterns by time and day using Random Forest
- **Factor Analysis**: Examined relationships between transport infrastructure and pedestrian flows

### Tech Stack
- **Languages**: Python
- **Key Libraries**: Pandas, Scikit-learn, Folium
- **Machine Learning**: Random Forest
- **Data Sources**: Melbourne Open Data API
- **Visualization**: Folium, Plotly

### Key Results
- Visualized pedestrian movement patterns by time and day of week
- Analyzed the impact of public transport infrastructure on pedestrian flows
- Identified key influencing factors using Random Forest models

---

## 📊 Data Sources

### Project 1
- Regional pedestrian sensor data
- Domestic traveler statistics
- Tourist attraction location data

### Project 2
- Melbourne Pedestrian Counting System(https://data.melbourne.vic.gov.au/)
- Melbourne train station and bus stop location data
- Public Transport Victoria (PTV) API

---

## 🔍 Key Analysis Techniques

### Machine Learning Models
- **K-means Clustering**: Analysis of tourist concentration patterns
- **Random Forest**: Pedestrian pattern and factor analysis

### Spatial Analysis
- **Haversine Distance**: Geographic distance calculations
- **Folium Mapping**: Interactive map visualization

### Time Series Analysis
- Pedestrian trend analysis by time of day and day of week
- Seasonality and cyclical pattern detection

---

## 📈 Project Achievements

- ✅ Conducted practical analysis using real-world urban data
- ✅ Gained experience in large-scale data collection and preprocessing via APIs
- ✅ Applied various machine learning techniques for pattern analysis
- ✅ Generated insights through map visualization
- ✅ Predicted transport demand and analyzed infrastructure impact

---

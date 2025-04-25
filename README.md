# 🌊 Coral Reef Decline in the Florida Keys: A Data Science Approach

![Coral Image](https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Coral_reef_in_the_Red_Sea.jpg/640px-Coral_reef_in_the_Red_Sea.jpg)

## 📌 Project Overview

This solo data science project by **Prithivraj** investigates the alarming decline in coral reef health across the Florida Keys using ecological monitoring data. With a focus on identifying trends and forecasting future conditions, the project applies statistical and machine learning techniques to support reef restoration and conservation planning.

---

## 🔍 Key Objectives

- Analyze historical coral reef monitoring data from NOAA.
- Visualize spatial and temporal trends in coral cover, species richness, and disease prevalence.
- Use predictive models to forecast future reef conditions.
- Identify reef sites in critical need of conservation efforts.
- Provide region-specific recommendations for ecosystem restoration.

---

## 📊 Dataset

- Source: [NOAA Coral Reef Monitoring Program](https://www.fisheries.noaa.gov/topic/coral-reefs)
- Format: Cleaned CSVs used for station-wise and regional analysis
- Key Features:
  - `year`
  - `station_code`, `region`, `sub_region`
  - `percent_live_coral_cover`
  - `species_richness`
  - `octocoral_density`
  - `disease_prevalence`
  - And other biological/ecological indicators

---

## 🧪 Tools & Technologies

- Python
  - `pandas`, `numpy`, `seaborn`, `matplotlib`
  - `statsmodels` for regression and trend analysis
- Jupyter Notebook
- Markdown + Visual Reporting

---

## 📈 Project Highlights

- 🔻 **Declining Coral Cover** in the Upper Keys across multiple monitoring stations.
- 🌱 **Increase in Octocoral Density** observed in select locations, indicating resilience in non-hard coral types.
- 🧬 **Disease Prevalence Trends** vary by station, revealing key hotspots of stress.
- 📉 **Predictive Modeling** shows further decline in species richness unless mitigated.

---

## 📍 Notable Insights

| Region | Trend Summary |
|--------|----------------|
| Upper Keys | Sharp coral decline; restoration needed urgently |
| Lower Keys | Slight improvements in some zones |
| Western Sambo Deep | Stable coral recovery; potential benchmark site |

---

## 🛠️ Usage

To explore the notebook:

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/florida-reef-health-analysis.git
   cd florida-reef-health-analysis

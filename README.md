# SCT_DS_4
explored the US Accidents dataset to uncover patterns in traffic incidents, identified key accident hotspots, and analyzed how road, weather, and time factors influence accidents.
# US Accidents – Hotspot Analysis with Kernel Density Estimate

Visualize and analyze accident hotspots across the United States using the US Accidents dataset.

## 📖 Overview
Every dataset tells a story 📊.  
In this project, I explored the **US Accidents dataset** to identify regions with a high concentration of accidents.  
Using Python and Seaborn’s Kernel Density Estimate (KDE) plotting, I created a heatmap to reveal geographic accident hotspots.

## 🚀 Key Steps
- **Data Preprocessing**:  
  - Loaded and cleaned the US Accidents dataset.  
  - Selected relevant geographic features: `Start_Lat` and `Start_Lng`.

- **Visualization**:  
  - Implemented Seaborn’s `kdeplot` to display accident density across the U.S.  
  - Optimized performance by sampling the dataset for faster rendering.

- **Insights**:  
  - Identified areas with higher accident probabilities to aid in traffic safety analysis.

## 🛠️ Tech Stack
- Python  
- pandas, numpy  
- seaborn, matplotlib  
- Jupyter Notebook


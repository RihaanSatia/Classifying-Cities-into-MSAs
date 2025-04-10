# Classifying Cities into Metropolitan Statistical Areas (MSAs) via Clustering

## Project Overview

This project applies unsupervised clustering techniques to classify U.S. cities into **Metropolitan Statistical Areas (MSAs)** based on geospatial and socioeconomic features. By leveraging clustering algorithms, the project aims to uncover regional similarities and enhance urban classification systems beyond traditional boundaries.

## Objectives

- Group cities based on proximity, economic interaction, and demographic features.
- Use clustering to create functional MSAs, revealing hidden geographic and behavioral patterns.
- Provide a reproducible pipeline for exploratory spatial data analysis.

## Notebook

The core of the project is implemented in the Jupyter Notebook:

- `ClusteringMSA.ipynb` – Contains:
  - Data preprocessing
  - Initial EDA
  - Clustering via algorithms like K-Means and DBSCAN
  - Geographic visualizations of cluster assignments
  - Alternative method to create dynamic MSA Boundaries with POI data and H3 hexagons

## 🛠️ Tools & Libraries

- `pandas`, `numpy` — data manipulation
- `scikit-learn` — clustering algorithms
- `matplotlib`, `seaborn`, `plotly` — data visualization
- `geopandas`, `shapely` — geospatial operations
- `folium`  — geographic mapping

## 🔍 Methods

- **Distance and Density-Based Clustering:** 
  - K-Means
  - DBSCAN
  - H3 hexagonal grid for dynamic MSA boundaries

- **Geospatial Visualization:**
  - Mapping clustered MSAs on U.S. maps for interpretability

## Outputs

- Clustered city groups visualized on a U.S. map
- Insights into spatial distribution, economic interdependence, and urban structure

## Future Work

- Integrate temporal mobility data to make clustering dynamic
- Identify population distribution patterns and utilize GMM models for classification
- Refine H3 techniques

## 🧑‍💻 Author

**Rihaan Satia**  
[LinkedIn](https://www.linkedin.com/in/rihaansatia) • [GitHub](https://github.com/RihaanSatia)

---

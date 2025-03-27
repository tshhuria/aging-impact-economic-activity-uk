

# 👵📊 Visual Analytics of Aging Population and Economic Activity in the UK (2011–2021)

This project explores the socio-economic impact of an aging population across various regions of the UK using advanced visual analytics techniques and interactive dashboards. It combines data from the UK census (Nomis) for 2011 and 2021, focusing on changes in employment, economic inactivity, and household composition over the decade.

---
## 🍱 Data Description
Data is sourced from **Nomis** and includes:

- **Household Composition Data**:
  - One-person households aged 65+
  - Lone parent households
  - Households where all members are over 65
- **Economic Activity Data**:
  - Number of retired individuals
  - Employment/unemployment counts
  - Long-term sick/disabled individuals

All data was cleaned, merged, and aligned by **geographic codes** for comparative analysis.

---

## 🎯 Objective

To analyze how the rise in the retired population correlates with the decline in economically active individuals using:

- Dimensionality reduction (PCA & t-SNE)
- K-Means clustering
- Tableau dashboards
- UK census datasets from [Nomis](https://www.nomisweb.co.uk/sources)

---

## 🛠️ Tools & Technologies

- **Python**: pandas, sklearn (PCA, t-SNE, KMeans), numpy
- **Jupyter Notebooks**: for preprocessing, projections, and feature engineering
- **Tableau**: for dashboard development and visual storytelling
- **Nomis**: Open UK census and labor market data

----

## 🔎 Visual Highlights

- 🗺️ **Heatmaps** for regional employment and retirement change
- 📈 **Side-by-side bar charts** for comparing 2011 vs 2021 stats
- 🧬 **Scatter plots** for PCA/t-SNE clusters
- 🫧 **Bubble charts** for highlighting economic shift hotspots

Each visualization was built using principles of human perception, pre-attentive processing, and Munzner’s visualization taxonomy to optimize readability and clarity.

---

## 📓 Notebooks Overview

### 1. `AnalysingDataAndManupulation.ipynb`
- Loads raw census CSVs
- Cleans column names, fills missing values
- Removes unnecessary rows
- Creates structured dataframe for further processing

### 2. `VA-ProjectionMatrix.ipynb`
- Merges 2011 and 2021 household and economic datasets
- Applies:
  - **PCA** (linear projection to 2D)
  - **t-SNE** (non-linear dimensionality reduction)
- Saves projection results as `.csv` for Tableau
- Adds `RowID` to assist in merging with metadata

### 3. `VisualAnalytics.ipynb`
- Final data cleanup from `FinalVA2021.xlsx`
- Filters invalid or placeholder values
- Prepares clean dataset for visual storytelling

---

## 📊 Tableau Dashboards

The visualizations capture 4 perspectives:

1. **Dashboard 1**: Overview of aging population vs. economic inactivity
2. **Dashboard 2 & 3**: PCA & t-SNE projections for 2011 and 2021
3. **Dashboard 4**: Change in employment rates, heatmaps, treemaps, and bubble charts

## 🔐 Data Privacy

- All data used is from publicly available UK census datasets
- No personal or sensitive information is included

---

## 🧠 Methods Summary

| Technique | Purpose |
|----------|---------|
| **PCA** | Visualize largest variance in household/economic indicators |
| **t-SNE** | Capture non-linear clustering of socio-economic profiles |
| **K-Means** | Identify regions with similar patterns |
| **EDA** | Understand spread, distributions, and anomalies |
| **Tableau** | Communicate trends to stakeholders via dashboards |

---

## 🔐 Data

Data is sourced from [Nomis Official Census and Labour Market Stats](https://www.nomisweb.co.uk/sources). Only cleaned, derived data is shared.

---


## 📝 References

- [Nomis Official Census Data](https://www.nomisweb.co.uk/)
- PCA: Jolliffe (2002), sklearn.decomposition
- t-SNE: van der Maaten & Hinton (2008)
- K-Means: MacQueen (1967), sklearn.cluster
- Tableau: [tableau.com](https://www.tableau.com)
- Visualization theory: Munzner (2014), Tufte (2001)

---

## 📌 Notes

This project was developed as part of an academic data visualization module, with a strong focus on communicating meaningful patterns and changes using ethical data visualization practices.

---

## 📩 Contact

Feel free to raise an issue or connect with me on [LinkedIn](https://www.linkedin.com/in/tanmaysagarhuria/) if you have questions or would like to collaborate!

---

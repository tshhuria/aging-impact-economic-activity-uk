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

## 🧠 Methods Used

### 1. 📉 Principal Component Analysis (PCA)
- Linear dimensionality reduction
- Used to highlight variation across economic and household attributes

### 2. 🌐 t-SNE
- Non-linear dimensionality reduction
- Helped visualize local clusters of economic behavior in a 2D space

### 3. 🔍 K-Means Clustering
- Applied to PCA/t-SNE projections
- Revealed distinct regional clusters by economic inactivity and age demographics

### 4. 📊 Tableau Dashboards
- 4 interactive dashboards created:
  - **Dashboard 1**: Aging population overview
  - **Dashboard 2/3**: Socio-economic trends in 2011 vs 2021
  - **Dashboard 4**: Change in employment vs retirement

---

## 🔎 Visual Highlights

- 🗺️ **Heatmaps** for regional employment and retirement change
- 📈 **Side-by-side bar charts** for comparing 2011 vs 2021 stats
- 🧬 **Scatter plots** for PCA/t-SNE clusters
- 🫧 **Bubble charts** for highlighting economic shift hotspots

Each visualization was built using principles of human perception, pre-attentive processing, and Munzner’s visualization taxonomy to optimize readability and clarity.

---

## 🔐 Data Privacy

- All data used is from publicly available UK census datasets
- No personal or sensitive information is included

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

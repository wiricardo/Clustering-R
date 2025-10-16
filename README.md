# 📊 Hierarchical Clustering Analysis in R

**Personal project by Wiricardo** for practicing hierarchical clustering techniques and customer segmentation in R.  
This repository contains a comprehensive analysis comparing agglomerative and divisive clustering methods on customer personality data using tidymodels and factoextra.

---

## Project Structure

```
Clustering-R/
├── clustering-code-R.qmd    # Main analysis document (Quarto)
└── README.md
```

---

## 🎯 Analysis Overview

**Dataset:** Customer Personality Analysis  
**Methods:** Agglomerative (AGNES) and Divisive (DIANA) hierarchical clustering  
**Variables:** Total spending, age, and total purchase quantity  
**Result:** 3 customer segments identified

---

## 📈 Key Findings

- **Divisive clustering (0.42 silhouette)** outperformed agglomerative (0.35 silhouette)
- **Cluster 1:** High-value mature customers (avg. age 64 years, spending $1,094)
- **Cluster 2:** Low-value occasional buyers (avg. spending $147)
- **Cluster 3:** Premium young buyers (avg. age 44 years, spending $1,238)

---

## 🚀 Technologies

- **R & Quarto** - Reproducible analysis
- **tidyverse & tidymodels** - Data manipulation and modeling
- **cluster** - AGNES and DIANA algorithms
- **factoextra** - Dendrograms and silhouette plots
- **plotly** - Interactive 3D visualizations

---

## Data Source

- **Customer Personality Analysis Dataset** - Demographic data, purchase history, and marketing campaign responses

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

## Contact

For questions or collaboration:  
**GitHub profile** → [wiricardo](https://github.com/wiricardo)
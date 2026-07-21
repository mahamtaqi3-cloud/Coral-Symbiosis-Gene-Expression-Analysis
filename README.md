# 🧬 Coral Symbiosis Gene Expression Analysis 

### Project Overview

This repository contains the bioinformatic workflow used to analyze gene expression patterns in *Aiptasia* larvae in response to infection with *M. gaditana*. By leveraging TMM-normalized count data, this project identifies differential expression patterns to better understand the molecular mechanisms of coral symbiosis.

---

### 📊 Key Visualizations

Included in this project is an **Expression Heatmap** highlighting the top variably expressed genes across treated and non-treated conditions.


---

### 🚀 Workflow

The analysis follows a reproducible R workflow:

1. **Data Import**: Loading TMM-normalized expression data.
2. **Preprocessing**: Conversion to matrix format and removal of non-finite values to ensure high-quality clustering.
3. **Quality Control**: Filtering rows with zero variance to allow for accurate hierarchical clustering.
4. **Visualization**: Generation of a row-scaled heatmap to visualize expression trends.

---

### 🛠️ Technical Stack

* **Language**: R (v4.6.1)
* **Key Libraries**: `pheatmap`, `readxl`
* **Environment**: RStudio

---

### 💡 How to Run

To reproduce this analysis:

1. Ensure you have the `GSE141133_TMM_Mg.xlsx` data file in your project directory.
2. Open the project in RStudio.
3. Run the provided script to process the data and generate the heatmap.

---

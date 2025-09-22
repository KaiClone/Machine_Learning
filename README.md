



# 🧬 Tumor Tissue Image Metadata Explorer

A machine learning project for analyzing tumor tissue metadata, identifying top predictive features, and visualizing results using SHAP, PCA, and t-SNE.  
The project evaluates multiple models (Logistic Regression, Random Forest, XGBoost) and optimizes decision thresholds using **F1**, **F2**, and **Youden’s J statistic**.

---

## 🚀 Features
- Data preprocessing and feature analysis
- Exploratory histograms for top 10 predictive features
- Dimensionality reduction with **PCA** and **t-SNE**
- Model training & evaluation (Logistic Regression, Random Forest, XGBoost)
- Threshold optimization with **F1, F2, Youden**
- Explainability with **SHAP**:
  - Global feature importance
  - Summary plots
  - Waterfall plots for individual predictions
  - Feature interaction heatmaps
- Automated **Word report generation** (tables + plots)

---

## 📂 Project Structure
Tumor_Tissue_Image_Metadata_Explorer/
│
├── tumor_tissue_image_metadata_explorer_final.ipynb # Main pipeline
├── results/ # Generated plots & tables
│ ├── plots/
│ └── tables/
└── README.md


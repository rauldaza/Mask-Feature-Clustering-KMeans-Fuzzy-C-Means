# Clustering of Morphological and Textural Features from Masks

This repository contains a complete project focused on unsupervised clustering of morphological and textural features extracted from mask data. The goal is to identify hidden patterns and structures using algorithms such as **KMeans** and **Fuzzy C-Means**. The analysis is performed entirely using Python’s scientific stack, with clear visualizations and metric-based evaluation.

## 🗂 Repository Structure

- **clustering.ipynb**  
  Main notebook containing the full analysis pipeline: loading the dataset, preprocessing, applying clustering algorithms, visualizing the results, and evaluating the clusters.

- **CaracteristicasExtraidasdeMascaras.xlsx**  
  Excel file containing the extracted features used as input for the clustering algorithms. Includes fields like `Texture`, `Perimeter`, `Cx`, `Cy`, `Concave`, `Concave_Points`, `Smoothness`, and `Label`.

- **readme.md**  
  This documentation file, providing project overview, structure, skills demonstrated, and usage instructions.

## 💡 Demonstrated Skills

- Manual application and comparison of unsupervised clustering techniques (KMeans and Fuzzy C-Means).
- Data preprocessing including feature selection and normalization.
- Exploratory Data Analysis (EDA) using pandas, seaborn, and matplotlib.
- Visualization of clustering results with insightful plots and dimensionality reduction.
- Evaluation of clustering quality using silhouette score and visual interpretation.
- Efficient use of Python libraries for scientific computing and machine learning:
  - `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scikit-fuzzy`, and `tqdm`.
- Clear documentation and well-organized notebook for reproducibility and recruitment-readiness.

## ▶️ How to Run

1. Install the required dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn scikit-fuzzy tqdm

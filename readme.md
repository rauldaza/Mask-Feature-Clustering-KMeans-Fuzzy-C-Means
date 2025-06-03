# Clustering of Features Extracted from Masks 🧬

This project applies clustering techniques to analyze and group morphological and textural features extracted from masks. The goal is to identify underlying patterns using unsupervised machine learning methods such as KMeans and fuzzy c-means.

## 📁 Project Structure

- **CaracteristicasExtraidasdeMascaras.xlsx**  
  Excel file containing extracted features such as `Texture`, `Perimeter`, `Cx`, `Cy`, `Concave`, `Concave_Points`, `Smoothness`, and `Label`. This is the dataset used for clustering.

- **clustering.ipynb**  
  Jupyter Notebook that contains the full analysis workflow:
  - Data loading and exploratory analysis
  - Data preprocessing (feature selection and normalization)
  - Application of KMeans and fuzzy c-means clustering
  - Cluster evaluation and visualization
  - Metric analysis and interpretation of results

## 🧪 Technologies and Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- scikit-fuzzy
- tqdm

## ▶️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

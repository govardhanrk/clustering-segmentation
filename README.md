# Clustering and Segmentation Project

## Overview
This repository contains a project focused on clustering and segmentation using advanced data analysis techniques. The project includes:

- **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
- **Feature Analysis**: Exploring and visualizing key features.
- **Dimensionality Reduction**: Implementing PCA and Autoencoders to reduce data dimensions.
- **Clustering**: Applying K-Means and DBSCAN algorithms to identify meaningful clusters.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - tensorflow

### Running the Notebook
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd clustering-segmentation
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook src/stepwiseprocess.ipynb
   ```
4. Execute the cells sequentially to reproduce the analysis.

## Project Highlights
- **Dimensionality Reduction**: PCA and Autoencoders were used to simplify the dataset while retaining critical information.
- **Clustering**: K-Means and DBSCAN algorithms were applied to identify customer segments.
- **Visualization**: Comprehensive visualizations were created to interpret the results effectively.

## Results
- Identified three distinct customer segments: Balanced, Budget, and High-Value.
- Autoencoder-based clustering outperformed PCA-based clustering in terms of Silhouette Score and Davies-Bouldin Index.

## License
This project is licensed under the terms of the LICENSE file.

## Acknowledgments
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow
- Dataset: https://www.kaggle.com/datasets/kyanyoga/sample-sales-data

---

For any questions or contributions, feel free to open an issue or submit a pull request.

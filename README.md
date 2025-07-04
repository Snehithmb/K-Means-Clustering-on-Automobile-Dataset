# K-Means Clustering on Automobile Dataset 🚗

Google colab link -- https://colab.research.google.com/drive/1Gs52JuNQ8L45EryRlJmCeFpepnc_764o

This project demonstrates unsupervised machine learning using **K-Means clustering** to segment data from an automobile dataset.

## Tools & Libraries

- Python
- Scikit-learn
- Pandas
- Matplotlib
- PCA (for dimensionality reduction)

## Dataset

Use the provided `Automobile.csv` dataset. Ensure it's placed in your working directory or uploaded to Colab.

## Steps Performed

1. **Data Loading & Cleaning**: Numeric-only columns are used and missing values removed.
2. **Feature Scaling**: Standardized using `StandardScaler`.
3. **Optimal K Selection**: Elbow method used to find the best number of clusters.
4. **Clustering**: K-Means applied with chosen K (e.g., 3).
5. **Visualization**: PCA used to reduce features to 2D for plotting clusters.
6. **Evaluation**: Clustering evaluated using **Silhouette Score**.

## Output Example

- Elbow Curve
- PCA Scatter Plot with cluster color
- Silhouette Score in console





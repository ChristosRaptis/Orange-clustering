# Orange-clustering

## Objective: clustering of a multidimensional dataset provided by Orange and interpretation of resulting clusters.

## Disclaimer: due to NDA restrictions this repo contains no data, only the code logic.

### Feature selection:
Removal of features deemed irrelevant or redundant.

### Encoding:
Use of OrdinalEncoder to encode categorical features to numerical

### Imputing:
Use of SimpleImputer to deal with missing values in numerical features

### Normalization:
Use of StandardScaler to normalize the data

### Feature reduction:
Use of UMAP to reduce the features

### Clustering:
Use of Kmeans for clustering, after failed attempt with DBSCAN due to it being resource demanding

### Clusters interpretation:
Use of means comparison for clusters interpretation, after dropped attempt at using SHAP due to it being time consuming

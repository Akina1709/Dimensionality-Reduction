# Preprocessing Time Series Data:
**1. Utilizing Masking and Padding:**
- **Masking**: Ignore certain timesteps in the input sequence during model training.
- **Padding**: Add zeros or a specific value to sequences to make them uniform in length.
**2. Feature Extraction Methods:**
Extract statistical features from the time series data such as mean, standard deviation, maximum, minimum, skewness, kurtosis, etc.

# Dimensionality Reduction:
**1. Principal Component Analysis (PCA):**
Linear technique aiming to find directions (principal components) that maximize data variance.

**2. Kernel PCA (KPCA):**
Non-linear extension of PCA using kernel methods to map data into a higher-dimensional space.

**3. t-distributed Stochastic Neighbor Embedding (t-SNE):**
Non-linear technique preserving local structure of data in lower-dimensional space.

**4. Autoencoder:**
Neural network architecture learning to reconstruct input data from a compressed representation.

**5. Independent Component Analysis (ICA):**
Statistical technique separating multivariate signal into additive, independent components.

# Analyzing Activities of Daily Living (ADL) using K-means:
## K-means Algorithm:
Clustering algorithm partitioning data into 'k' clusters based on similarity of features.
Assigns each data point to the cluster whose mean is nearest.
Useful for identifying patterns and grouping similar activities based on extracted features or reduced representations.

By employing these techniques, you can effectively preprocess and analyze time series data related to ADL, revealing meaningful patterns and insights into different activities.

**Dataset:** [Link](https://archive.ics.uci.edu/ml/datasets/Dataset+for+ADL+Recognition+with+Wrist-worn+Accelerometer?fbclid=IwAR1ZVJaj_S0W3yB8D1-XSzCrkU1B1n0VF_EKT5K3MO84BErkCv1dCu6rt4A).

**Report:** Read details [here](https://drive.google.com/file/d/1vIoDc4ewXNfHj_y3Mtm9xMpVsbzFqZMU/view?usp=drive_link).

# BlueCastML

# Preprocessing steps - standard
 # QA
   * Remove duplicate column names
   * Reset index
   * Fill infinite
   * Fill NULL values (multiple methods)
   * Delete columns with high percentage of NULLs
   * Sorting column names
 # Numerical features
   * Binning of numerical columns
   * Handle target skewness
   * Numerical binarizer (with and without PCA)
   * Clustering (Kmeans, Gaussian Mixture, DBSCAN)
 # Categorical features
   * Encodings (target, onehot + PCA and more)
   * TD-IDF vectorizer (with and without PCA)
   * Categorical embeddings
 # Datetime features
   * Ordinal encoding
   * Cyclic encoding
 # General applications
   * Test-train split
   * Memory footprint reduction
   * Outlier detection (Isolation forest, SVM)
   * Outlier removal
   * Feature type detection
   * Feature selection (early & last layer) via Boostaroota and/or SHAP
   * Weak training rows removal
   * Data scaling (various methods)
 # Class imbalance
   * SMOTE
   * Autoencoder based oversampling
 # Special
   * Random trees embeddings
   * GAN based synthetic data replacement or over/undersampling
   

# Preprocessing steps - NLP
 * Regex based data cleaning
 * POS tagging
 * Sentiment scoring (optional)
 * Oversampling

# Processing recipes

proposed folder structure:
Bluecast/packages/package_x/
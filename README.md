# ESC_using_AFX
Environmental Sound Classification (ESC) using [AFX (Audio Feature Extraction) module](https://github.com/danilodsp/AFX)

**01_load_ESC50.ipynb**: Loads and analyzes the ESC-50 dataset, verifies integrity, explores class distribution, and visualizes audio samples and features.

**02_pca_melspectrogram.ipynb**: Extracts mel spectrogram features, applies PCA for dimensionality reduction, and visualizes class separability using different aggregation strategies.

**03_aggregated_feature_analysis.ipynb**: Performs multi-feature extraction and aggregation, compares statistical properties, analyzes feature discriminability, and applies PCA for feature variability.

**04_temporal_aggregation_analysis.ipynb**: Investigates temporal aggregation strategies (frame-wise, sliding window, global), analyzes their impact on feature/class separability, and compares classification performance.

**05_classwise_discriminability.ipynb**: Analyzes which features best separate each class using statistical tests and information theory, providing class-wise discriminability rankings and visualizations.

**06_class_similarity_clustering.ipynb**: Computes inter-class similarity using feature embeddings, performs clustering analysis, and visualizes class groupings to identify acoustically similar classes.

**07_CNN_backbone.ipynb**: Implements and evaluates a CNN backbone for ESC-50 classification, including feature extraction, model training, performance analysis, and architectural insights.

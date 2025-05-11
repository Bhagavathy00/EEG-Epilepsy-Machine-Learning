***EEG-Based Seizure Detection Using Machine Learning:***

This project implements a machine learning pipeline for detecting epileptic seizures from EEG signals. The goal is to develop a system that can classify EEG signals into seizure or non-seizure events with high accuracy. The system uses the AD8232 sensor for EEG signal acquisition, followed by various data preprocessing, feature extraction, dimensionality reduction, clustering, and classification techniques.

**Key Components:**

1. Dataset Preprocessing:
The EEG data is cleaned and normalized to remove noise and artifacts.

Missing or corrupted data points are handled to ensure reliable input for feature extraction.

2. Feature Extraction:
Discrete Wavelet Transform (DWT) is used to extract time-frequency domain features from the raw EEG signals. These features capture both spatial and temporal information about brain activity.

3. Dimensionality Reduction:
Principal Component Analysis (PCA) is used to reduce the dimensionality of the extracted features while retaining important information.

t-SNE is used for further visualization and exploration of the data.

**4. Clustering:**

K-Means clustering is applied to group similar EEG signals together, helping to better understand the patterns in the data before classification.

**5. Classification:**

Multiple machine learning classifiers are used to classify the EEG data:

XGBoost

K-Nearest Neighbors (K-NN)

Decision Tree

Random Forest

Multi-Layer Perceptron (MLP)

6. Evaluation:
The system is evaluated based on its ability to correctly classify seizure events from non-seizure events using various performance metrics.

# EEG-Signal-Classification-Using-Machine-Learning
This project presents a clean and simple workflow for analyzing EEG data and generating topographic brain maps using MNE-Python. The notebook demonstrates how to load PSD (Power Spectral Density) values, map them to electrode positions, and visualize the distribution of different EEG frequency bands across the scalp.
## Dataset Availability
The dataset used in this project is not included in this repository because it is proprietary / private / unavailable.
To run the notebook, replace the dataset path with your own EEG dataset.
Expected format:
- CSV or MAT file containing EEG signals
- Channels: Fp1, Fp2, etc.
- Labels (optional): stress, seizure, emotion class, etc.
### Techniques Used
Data Preprocessing
Handling missing values
Channel selection
Scaling & normalization
Signal smoothing (optional)
Filtering (if implemented: bandpass, notch)
Feature Extraction
Mean, variance
Standard deviation
Skewness / kurtosis
Peak-to-peak amplitude
Frequency domain features (if applied)
### Models Applied
Random Forest
SVM
Logistic Regression
KNN
XGBoost
Evaluation Metrics
Accuracy
Precision, Recall, F1-score
Confusion Matrix

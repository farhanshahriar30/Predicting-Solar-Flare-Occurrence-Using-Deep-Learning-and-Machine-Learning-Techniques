# Predicting-Solar-Flare-Occurrence-Using-Deep-Learning-and-Machine-Learning-Techniques

## Project Overview

This project aims to develop advanced predictive models to forecast solar flare occurrences using a combination of deep learning and machine learning techniques. Solar flares are sudden eruptions of electromagnetic radiation from the Sun's surface, and predicting their occurrence is crucial for space weather forecasting.

## Dataset

The dataset used in this project contains features derived from solar magnetic field measurements and physical parameters of active regions on the Sun. The key features include:
- TOTUSJH: Total unsigned current helicity
- USFLUX: Total unsigned flux
- TOTPOT: Total photospheric magnetic free energy density
- Various other magnetic and physical parameters

## Data Preprocessing

Data preprocessing steps include:
- Handling missing values
- Filtering out noisy records
- Normalizing features
- Addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)
- Splitting data into training and testing sets

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the distribution and relationships of various features within the dataset. Key visualizations include:
- Histograms
- Correlation heatmap
- Scatter plots for feature pairs

## Modeling

### LSTM Model

An LSTM (Long Short-Term Memory) network was implemented to handle the sequential nature of the data. The model architecture includes:
- Two LSTM layers
- Dropout layers to prevent overfitting
- A dense layer with a sigmoid activation function

### Random Forest

A Random Forest classifier was used for its robustness and ability to handle high-dimensional data. Hyperparameter tuning was performed using RandomizedSearchCV.

### XGBoost

XGBoost, a powerful gradient boosting framework, was used to enhance predictive performance. Hyperparameters were optimized using RandomizedSearchCV.

## Model Evaluation

Models were evaluated using various metrics:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix

Cross-validation was performed to ensure model robustness, and ROC curves were plotted to visualize model performance.

## Conclusion

The project demonstrated the potential of deep learning and machine learning techniques in predicting solar flare occurrences. The LSTM model, in particular, showed strong performance in handling sequential data, while Random Forest and XGBoost provided robust predictive capabilities.

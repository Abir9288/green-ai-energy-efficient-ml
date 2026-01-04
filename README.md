🌱 Green AI: Energy-Efficient Machine Learning for Air Quality






This project uses energy-efficient machine learning (Green AI) to predict air quality using global weather and pollution datasets. It includes processed datasets, Python scripts, and Jupyter notebooks for data preparation, feature engineering, model training, and evaluation.

📁 What's in this project?

data/processed/features_final.csv → main processed dataset (tracked with Git LFS)

notebooks/data_preparation.ipynb → data cleaning and preprocessing steps

notebooks/model_training.ipynb → training Random Forest, Logistic Regression, and other ML models

notebooks/evaluation.ipynb → evaluation of model accuracy, F1-score, and CO₂ emission tracking

.gitignore → files/folders ignored by Git

requirements.txt → Python dependencies

README.md → this file

submissionReadyThesis.docx → full thesis report

📊 Dataset & Feature Overview

The dataset contains global air quality and weather data, including:

Temperature, humidity, wind speed, etc.

Air Quality US EPA Index (target variable)

Engineered features for machine learning models

Note: Large datasets are stored using Git LFS to ensure repository efficiency.

📊 ModelPerformance: Accuracy and Macro F1

<img width="989" height="790" alt="image" src="https://github.com/user-attachments/assets/a5008398-095d-4188-814a-9a8ed720b3b3" />

📊 Accuracy vs Inference Time vs CO2 Emission

![model_diagram.png](attachment:model_diagram.png)


# Asteroid Hazard Classification

## Description
A machine learning and deep learning project analyzing NASA's asteroid dataset to predict hazardous asteroids. This project combines classical machine learning models and modern deep learning architectures to address class imbalance and optimize predictive performance.

## Features
- Implemented multiple models: Decision Tree, Random Forest, LightGBM, RNN, and CNN.
- Addressed class imbalance using SMOTE, achieving a **96% AUC-ROC** with Random Forest.
- Optimized models through hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
- Preprocessed 338,000+ data points, including handling missing values, outlier removal, and feature selection.

## Technologies Used
- **Programming Language**: Python  
- **Libraries**: 
  - pandas, numpy, scikit-learn, tensorflow, LightGBM
- **Visualization Tools**: 
  - Matplotlib, Seaborn, SHAP

## Dataset
The dataset used in this project is publicly available on Kaggle:  
[Nearest Earth Objects Dataset (Kaggle)](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)

## Results
- **Random Forest**: Achieved **96% AUC-ROC** and strong performance across metrics.
- **LightGBM**: Delivered **94% AUC-ROC** with exceptional efficiency.
- **Deep Learning Models (RNN, CNN)**: Enhanced minority class F1-Score from **24% to 86%** using SMOTE.  

### Key Visualizations:
- Feature importance plots
- AUC-ROC curves
- Confusion matrices

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Asteroid-Hazard-Classification.git
   cd Asteroid-Hazard-Classification
## Install the required dependencies:
   - pip install -r requirements.txt
   - Download the dataset from Kaggle and place it in the data/ directory.
   - Open the Jupyter notebooks in the notebooks/ folder to explore and run the models.


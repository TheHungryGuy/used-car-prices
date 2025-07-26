# Used Car Price Predictor

This project uses a Kaggle dataset of used car listings from Craigslist to predict car prices based on their features.

## Overview

- Cleaned and preprocessed real-world data
- Trained a machine learning model to predict car prices
- Evaluated model accuracy using common regression metrics

## Dataset

Source: [Kaggle - Used Cars Dataset](https://www.kaggle.com/)  
(The actual link should be updated based on the dataset you used.)

## Model

- Features were extracted from the dataset and cleaned
- `PolynomialFeatures` and `StandardScaler` were used in a pipeline
- Model: `DecisionTreeRegressor`
- Data split: 67% training / 33% testing

## Evaluation

Model performance:
- **MAE**: 2760.41  
- **MSE**: 26,880,290.85  
- **RMSE**: 5184.62  
- **R²**: 0.81

## Visualization

The plot below shows predicted vs actual car prices:

![scatter plot](your-image-path-if-you-have-one.png)

## Requirements

- Python
- pandas, numpy, matplotlib, scikit-learn

## How to Run

1. Clone the repo  
2. Run the notebook in JupyterLab or any Python notebook environment  
3. Install required packages if needed:
   ```bash
   pip install pandas numpy matplotlib scikit-learn

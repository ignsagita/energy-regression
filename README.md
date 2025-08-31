# Heating_Loss and Cooling_Loss Regression Analysis for Energy Efficiency
## Overview
This project performs regression analysis on the [Energy Efficiency Dataset](https://archive.ics.uci.edu/dataset/242/energy+efficiency) from the UCI Machine Learning Repository. The goal is to predict **Heating Load** and **Cooling Load** of buildings based on architectural and structural features using various regression models.

## Description
The workflow includes:
- Regression Models:
  - *Linear Regression*
  - *Lasso Regression*
  - *Ridge Regression*
- For the model evaluation, cross_validate and RepeatedKFold are both performed.
- Model evaluation using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score  - Visual interpretation:

## Dataset
The dataset contains 768 building samples with 8 input features and 2 target variables:
**Input Features**:
- `Relative_Compactness`
- `Surface_Area`
- `Wall_Area`
- `Roof_Area`
- `Overall_Height`
- `Orientation`
- `Glazing_Area`
- `Glazing_Area_Distribution`

**Target Variables**:
- `Heating_Load`
- `Cooling_Load`

> Note: The dataset is **not included in this repository**. The notebook downloads the dataset automatically from Kaggle using the Kaggle API.

## Quick Start
- Clone this repository: git clone https://github.com/ignsagita/energy-regression.git cd energy-regression
- Install dependencies pip install -r requirements.txt
- Run the notebook: jupyter notebook energy-regression.ipynb

---

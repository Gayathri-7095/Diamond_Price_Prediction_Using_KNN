# Diamond Price Prediction Using K-Nearest Neighbors (KNN)

## Project Overview

This project predicts diamond prices using the K-Nearest Neighbors (KNN) Regression algorithm. By analyzing various characteristics of diamonds such as carat, cut, color, clarity, and dimensions, the model estimates the price of a diamond based on similarities with existing data.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

---

## Objective

The primary objective of this project is to build a machine learning model that can accurately predict diamond prices based on their physical and quality-related attributes.

---

## Dataset

The dataset contains information about diamonds and their corresponding prices.

### Features

| Feature | Description |
|----------|-------------|
| Carat | Weight of the diamond |
| Cut | Quality of the cut |
| Color | Diamond color grade |
| Clarity | Measure of diamond clarity |
| Depth | Total depth percentage |
| Table | Width of the diamond's top relative to its widest point |
| X | Length (mm) |
| Y | Width (mm) |
| Z | Depth (mm) |
| Price | Target variable |

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Exploratory Data Analysis

The following analyses were performed:

- Data inspection and cleaning
- Missing value analysis
- Statistical summary
- Correlation analysis
- Feature distribution visualization
- Outlier detection

---

## Machine Learning Model

### Algorithm

K-Nearest Neighbors (KNN) Regression

KNN predicts the price of a diamond by finding the K nearest diamonds in the dataset and using their prices to estimate the value of a new diamond.

### Workflow

1. Data Preprocessing
2. Feature Encoding
3. Train-Test Split
4. Feature Scaling
5. Model Training
6. Model Evaluation
7. Prediction

---

## Model Evaluation

The model performance was evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess the accuracy and reliability of the prediction model.

---

## Project Structure

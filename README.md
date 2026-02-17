# Gold Price Prediction using Machine Learning

This project implements a **Machine Learning** system to predict gold prices based on various financial indicators such as the S&P 500 index, silver prices, oil prices, and currency exchange rates. The model is built using Python and the **Random Forest Regressor** algorithm.

## 📌 Project Overview

Gold prices are influenced by a variety of economic factors. This project utilizes historical data (spanning 10 years) to analyze correlations between gold and other assets to build a predictive model.

* **Objective**: Predict the gold price (`GLD`) for a given set of financial indicators.
* **Model**: Random Forest Regressor.
* **Dataset**: Historical stock and commodity prices including SPX, GLD, USO, SLV, and EUR/USD.

## 📊 Workflow

The project follows a structured machine learning pipeline:

1. **Data Collection**: Loading the 10-year gold price dataset.
2. **Data Preprocessing**: Handling missing values and removing unnecessary columns like 'Date'.
3. **Data Analysis**: Finding correlations between features using a **Heatmap** and analyzing price distribution.
4. **Train-Test Split**: Dividing the data into training (80%) and testing (20%) sets.
5. **Model Training**: Implementing the **Random Forest Regressor**.
6. **Evaluation**: Comparing actual vs. predicted prices using R-squared error and data visualization.

## 🛠️ Technologies Used

* **Python** (Google Colab environment)
* **Pandas**: Data manipulation and analysis.
* **NumPy**: Numerical operations.
* **Matplotlib & Seaborn**: Data visualization and heatmaps.
* **Scikit-learn**: Machine learning model and evaluation metrics.

## 📈 Key Insights from Data

* **Correlation**: The analysis revealed a strong positive correlation (0.9) between Gold (`GLD`) and Silver (`SLV`) prices.
* **Distribution**: Most gold price points in the dataset fall within the ~120 range.
* **Model Accuracy**: The Random Forest Regressor achieved an **R-squared error score of 0.98**, indicating high precision.

## 📊 Results Visualization

The model's performance is visualized by plotting the **Actual Prices vs. Predicted Prices**. The overlapping lines in the plot demonstrate the model's high accuracy in tracking gold price trends.


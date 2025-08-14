# Health and Data Analysis Projects

This repository contains three tasks focused on data analysis, prediction modeling, and health-related insights. Each task aims to enhance skills in data handling, visualization, and machine learning.

## Task 1: Exploring and Visualizing a Simple Dataset

### Objective
Learn how to load, inspect, and visualize a dataset to understand data trends and distributions.

### Dataset Used
- **Iris Dataset**: A well-known dataset in the field of machine learning, available in CSV format. It can be loaded via the `seaborn` library or downloaded directly.

### Models Applied
- **Data Inspection**: Utilized pandas for loading and inspecting the dataset.
- **Visualization**: Employed `matplotlib` and `seaborn` for creating various plots.

### Key Results and Findings
- The dataset was successfully loaded and inspected, revealing its shape, column names, and summary statistics.
- Visualizations included:
  - A scatter plot showing relationships between features.
  - Histograms displaying value distributions for each feature.
  - Box plots identifying potential outliers in the dataset.

---

## Task 2: Predict Future Stock Prices (Short-Term)

### Objective
Use historical stock data to predict the next day's closing price.

### Dataset Used
- **Stock Market Data**: Historical stock data retrieved from Yahoo Finance using the `yfinance` Python library. The example used is for Apple Inc. (AAPL).

### Models Applied
- **Regression Modeling**: Trained a Linear Regression model to predict the next closing price based on features such as Open, High, Low, and Volume.

### Key Results and Findings
- The model was trained and evaluated, achieving a certain level of accuracy.
- A plot comparing actual vs. predicted closing prices was generated, illustrating the model's performance.
- The Mean Squared Error (MSE) was calculated to assess prediction accuracy.

---

## Task 3: Heart Disease Prediction

### Objective
Build a model to predict whether a person is at risk of heart disease based on their health data.

### Dataset Used
- **Heart Disease UCI Dataset**: Available on Kaggle, this dataset contains various health-related features for individuals.

### Models Applied
- **Classification Modeling**: Trained a Logistic Regression model (or Decision Tree) to classify individuals based on their risk of heart disease.

### Key Results and Findings
- The dataset was cleaned and preprocessed, handling any missing values.
- Exploratory Data Analysis (EDA) was performed to understand trends and relationships within the data.
- The model was evaluated using metrics such as accuracy, ROC curve, and confusion matrix.
- Important features affecting the prediction were highlighted, providing insights into factors contributing to heart disease risk.

---

## Conclusion
These tasks collectively enhance understanding of data analysis, predictive modeling, and health-related insights. They provide a foundation for further exploration in data science and machine learning applications in healthcare.

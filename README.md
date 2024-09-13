# Bitcoin Price Movement Prediction

This project focuses on predicting Bitcoin price movements or performing clustering based on historical data. Using various machine learning models and data visualization techniques, it aims to provide insights into Bitcoin price trends.

## Dataset

The dataset contains the following features:

- **Date**: The date of the record.
- **Open**: Opening price of Bitcoin.
- **High**: Highest price of Bitcoin for the day.
- **Low**: Lowest price of Bitcoin for the day.
- **Close**: Closing price of Bitcoin.
- **Volume**: The amount of Bitcoin traded.
- **Currency**: The currency used for trading.
- **Price Movement**: Indicator of price movement like Increase or Decrease.

## Project Workflow

1. **Data Preprocessing**: 
    - Data is loaded and cleaned using `pandas`.
    - Missing values are handled.
    - Features are scaled using `StandardScaler` for model input.

2. **Exploratory Data Analysis (EDA)**: 
    - Visualizations are created using `seaborn` and `plotly` to understand trends in the data.

3. **Modeling**:
    - Models used for prediction:
      - **RandomForestClassifier** for classification tasks (e.g., predicting price movement).
      - **SVM (Support Vector Machine)** for classification.
      - **LinearRegression** for predicting continuous values.
    - The dataset is split into training and testing sets using `train_test_split`.
    - Feature scaling is applied with `StandardScaler`.

4. **Model Evaluation**: 
    - The performance of models is evaluated using metrics like:
      - **Confusion Matrix**
      - **Accuracy Score**

5. **Visualization**:
    - Additional visualizations created using `plotly.express` and `plotly.graph_objects` to display interactive charts of Bitcoin price trends.

## Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `plotly.express`
- `plotly.graph_objects`
- `scikit-learn` (RandomForestClassifier, SVC, LinearRegression, train_test_split, StandardScaler, accuracy_score, confusion_matrix)


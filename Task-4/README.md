# 🎬 Netflix Trend Prediction Analysis

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-success)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

---

# 📌 Overview

This project analyzes historical Netflix content release trends and predicts future content growth using Machine Learning–based Time Series Forecasting techniques.

The project was developed as **Task 4 (Medium) – Trend Prediction Analysis** during my **Data Scientist Internship at Auspify Technologies**.

It demonstrates an end-to-end predictive analytics workflow including:

* Data Preparation
* Trend Analysis
* Feature Engineering
* Forecasting
* Machine Learning Model Comparison
* Business Insights
* Professional Data Visualization

---

# 🎯 Project Objective

The primary objective is to analyze how Netflix's content library has evolved over time and forecast future content growth using lightweight machine learning regression models.

---

# ❓ Problem Statement

Netflix has continuously expanded its content catalog over the years. Understanding historical release patterns enables organizations to:

* Analyze growth trends
* Forecast future content additions
* Support strategic planning
* Identify peak production years
* Understand long-term growth behavior

---

# 📂 Dataset Information

| Attribute  | Value                             |
| ---------- | --------------------------------- |
| Dataset    | Netflix Titles Dataset            |
| Records    | 8,790                             |
| Features   | 10                                |
| Time Range | 1925–2021                         |
| Source     | Netflix Movies & TV Shows Dataset |

---

# 🔄 Project Workflow

1. Load Dataset
2. Initial Exploration
3. Data Cleaning
4. Release Year Preparation
5. Trend Analysis
6. Moving Average Analysis
7. Growth Analysis
8. Feature Engineering
9. Model Training
10. Model Comparison
11. Future Forecasting
12. Business Insights
13. Save Results

---

# 📈 Time Series Analysis

The project performs:

* Historical yearly trend analysis
* Year-over-Year Growth
* Growth Percentage
* Moving Average (3-Year)
* Moving Average (5-Year)
* Trend Visualization

---

# ⚙️ Feature Engineering

The following predictive features are created:

* Year Index
* Lag-1
* Lag-2
* Rolling Mean
* Rolling Standard Deviation
* Trend Indicator

These engineered features improve forecasting performance.

---

# 🤖 Forecasting Models

The following machine learning models are trained and evaluated:

| Model                   | Purpose               |
| ----------------------- | --------------------- |
| Linear Regression       | Baseline Forecast     |
| Polynomial Regression   | Non-linear Trend      |
| Decision Tree Regressor | Rule-based Prediction |
| Random Forest Regressor | Ensemble Learning     |

The notebook automatically selects the best-performing model based on evaluation metrics.

---

# 📊 Model Evaluation

Evaluation metrics include:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The best model is automatically identified based on the lowest RMSE.

---

# 🔮 Future Predictions

The project forecasts Netflix content growth for the next **10 years** using the best-performing model.

Outputs include:

* Future Year
* Predicted Content Count
* Forecast Trend

---

# 💼 Business Insights

The notebook automatically generates insights such as:

* Peak Content Year
* Lowest Content Year
* Average Annual Growth
* Highest Growth
* Lowest Growth
* Historical Growth Pattern
* Future Growth Projection
* Forecast Interpretation
* Strategic Recommendations
* Machine Learning Summary

---

# 📊 Visualizations

The project includes publication-quality visualizations:

* Historical Trend Line
* Area Plot
* Bar Chart
* Moving Average Analysis
* Growth Percentage Analysis
* Forecast Curve
* Actual vs Predicted Comparison
* Feature Importance (Random Forest)

---

# 🛠️ Technologies Used

| Category         | Tools               |
| ---------------- | ------------------- |
| Programming      | Python              |
| Data Processing  | Pandas, NumPy       |
| Machine Learning | Scikit-Learn        |
| Visualization    | Matplotlib, Seaborn |
| Environment      | Jupyter Notebook    |

---

# 📁 Project Structure

```text
Auspify/
│
├── Dataset/
│   └── Dataset.csv
│
├── Task_4_Trend_Prediction_Analysis.ipynb
│
├── historical_trend.csv
├── future_forecast.csv
├── prediction_results.csv
├── model_evaluation.csv
│
└── README.md
```

---

# 📄 Output Files

| File                   | Description                |
| ---------------------- | -------------------------- |
| historical_trend.csv   | Historical yearly trend    |
| future_forecast.csv    | Next 10-year forecast      |
| prediction_results.csv | Actual vs predicted values |
| model_evaluation.csv   | Performance metrics        |

---

# ▶️ How to Run

1. Clone the repository.
2. Install the required Python packages.
3. Place `Dataset.csv` inside the `Dataset/` directory.
4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run all cells from top to bottom.

Example:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

# ✅ Expected Results

* Historical Netflix content trends
* Forecast for the next 10 years
* Machine learning model comparison
* Evaluation metrics
* Business insights
* Publication-quality visualizations
* Exported CSV reports

---

# 🚀 Future Improvements

* ARIMA and SARIMA forecasting
* Facebook Prophet
* XGBoost Regressor
* LightGBM
* Hyperparameter tuning
* Interactive dashboards with Plotly
* Streamlit deployment
* Model persistence with Joblib

---

# 💡 Skills Demonstrated

* Python Programming
* Data Cleaning
* Exploratory Data Analysis
* Time Series Analysis
* Feature Engineering
* Machine Learning
* Predictive Analytics
* Forecasting Techniques
* Model Evaluation
* Data Visualization
* Business Intelligence
* Technical Documentation

---

# 🖼️ Screenshots

> *Add screenshots of your notebook outputs and visualizations here.*

* Historical Trend
* Moving Average
* Model Comparison
* Forecast Curve
* Business Insights

---

# 👨‍💻 Author

**Aarush Tyagi**

**Data Scientist Intern**

**Auspify Technologies**

GitHub: https://github.com/aarush2557/Auspify

---

# 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ If you found this project useful, consider giving the repository a star!

If you'd like, I can also Create a premium GitHub README with a banner, centered badges, KPI cards, workflow diagram, and a more polished portfolio-style layout.

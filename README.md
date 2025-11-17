# Machine-Learning-Based-CO-Emission-Prediction-and-Industry-Classification-for-Malaysia
This repository contains all materials related to my Final Year Project (FYP) titled Machine Learning-Based CO₂ Emission Prediction and Industry Classification for Malaysia, including datasets, Power BI visualizations, and the full dissertation.

The project aims to support Malaysia’s transition toward Net Zero Carbon Emissions (NZCE) 2050 by providing data-driven forecasting and industry-level CO₂ emissions insights.

##🌍 Project Overview

Malaysia faces growing environmental challenges due to industrial expansion and increasing energy demand. This project develops a machine learning framework to:

1️⃣ Predict Malaysia’s future CO₂ emissions

Using:
ARIMA (1,1,1) & (2,1,1)
LSTM
Prophet

2️⃣ Classify industries by emission level (High/Medium/Low)

Using:
Decision Tree
Random Forest
k-Nearest Neighbors (kNN)

3️⃣ Provide visual and actionable insights

Through:
Power BI Dashboard
Time-series charts
Feature importance analysis
Industry comparison

This model supports policy-making, sustainability planning, and industry benchmarking.

# 📁 Repository Contents

File
- Power BI --> Power BI interactive dashboard with forecasting, industry comparison & insights
- Dataset Industry Classification --> Cleaned dataset used for industry-level ML classification
- Forecasting Dataset --> Used for time-series forecasting
- Dissertation --> Full project dissertation (methodology, results, literature review, conclusion)

# 🔧 Tools & Technologies

Programming & ML
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Prophet
- Statsmodels (ARIMA)

Visualization
- Power BI
- Matplotlib
- Seaborn
- Streamlit (optional extension)

Data Handling
- CSV / Excel
- Our World in Data (OWID) API sources
- DOE & Energy Commission reference materials

# 📊 Machine Learning Models Used
| Model             | Purpose                          |
| ----------------- | -------------------------------- |
| **ARIMA (1,1,1)** | Baseline linear forecasting      |
| **ARIMA (2,1,1)** | Captures more complex patterns   |
| **LSTM**          | Long-term nonlinear dependencies |
| **Prophet**       | Trend + seasonality modelling    |

| Model             | Purpose                                  |
| ----------------- | ---------------------------------------- |
| **Decision Tree** | Rule-based classification                |
| **Random Forest** | Handles nonlinearity & improves accuracy |
| **kNN**           | Simple distance-based classification     |

📈 Key Findings (Summary)

- CO₂ emissions in Malaysia show a rising long-term trend, influenced by energy consumption and industrial activity.
- Random Forest achieved the best performance for industry classification with higher accuracy and robustness.

The Power BI dashboard provides interactive insights for:
- High-emission industries
- Forecast trends
- Year-over-year comparisons

(You can update this section with exact numbers once your analysis is finalized.)

▶️ How to Use This Repository
To explore the dashboard
- Download and open the .pbix file using Power BI Desktop.

To run machine learning models
- Place the dataset files in your project directory and run your Jupyter Notebook / Python scripts.

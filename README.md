# 🛣️ Road Accident Analysis & Prediction Dashboard

An interactive dashboard analyzing road accidents across **Tamil Nadu, Kerala, and Karnataka** using historical data from **2021–2023**, with predictions for **2024–2025**. The project explores accident patterns, district-level hotspots, weather conditions, and accident severity to support data-driven road safety planning.

## 📊 Dashboard Preview

![State-wise Accident Comparison](https://github.com/hannejenifer/Accident-Analysis-Dashboard/blob/2afd92a0db3d3386d2e65882558bbbaafad0b4bf/STATE%20WISE%20COMPARISON.png)

![Weather-wise Accident Comparison](https://github.com/hannejenifer/Accident-Analysis-Dashboard/blob/2afd92a0db3d3386d2e65882558bbbaafad0b4bf/WEATHER%20WISE%20ACCIDENT%20COMPARISON.png)

## 🎯 Business Problem

Road accidents vary across regions, time periods, weather conditions, and severity levels. Understanding these patterns can help identify high-risk areas and support proactive road safety planning.

This project focuses on:

- Identifying high-risk districts and states
- Analyzing accident trends from 2021–2023
- Examining the relationship between weather and accidents
- Understanding accident severity patterns
- Predicting accident trends for 2024–2025

## 📁 Dataset

The project uses road accident data covering:

- **States:** Tamil Nadu, Kerala, and Karnataka
- **Historical Period:** 2021–2023
- **Prediction Period:** 2024–2025
- **Key Dimensions:** State, District, Year, Weather Condition, and Accident Severity

The dataset was cleaned and transformed before analysis and predictive modeling.

## 🔍 Approach

The project follows an end-to-end data analytics and predictive modeling workflow:

**Data Collection → Data Cleaning → Exploratory Data Analysis → Feature Engineering → Predictive Modeling → Dashboard Development → Insights → Recommendations**

### Data Preparation

- Handled missing and inconsistent values
- Standardized relevant data fields
- Transformed accident severity into a numerical representation
- Prepared data for district-, state-, and weather-level analysis

### Exploratory Data Analysis

The analysis examines:

- Year-wise accident trends
- State-wise accident distribution
- District-level accident patterns
- Weather-wise accident occurrence
- Accident severity patterns
- High-risk districts and recurring trends

## 🤖 Predictive Modeling

The project explores two machine learning approaches for accident prediction:

- **XGBoost**
- **LSTM**

The models were evaluated using classification metrics including:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

The prediction component is used to extend historical accident patterns into the **2024–2025** period.

## 🖥️ Dashboard

The interactive dashboard was developed using **Streamlit** to bring the analysis and predictions together in a single interface.

It provides:

- State-wise accident comparisons
- District-level analysis
- Weather-wise accident analysis
- Accident severity analysis
- Historical trend visualization
- Prediction results
- Interactive filtering and visual exploration

## 💡 Key Insights

The analysis highlights differences in accident patterns across states, districts, weather conditions, and severity levels.

Key findings include:

- Certain districts show consistently higher accident volumes.
- Accident patterns differ across Tamil Nadu, Kerala, and Karnataka.
- Weather conditions show variation in accident occurrence.
- Accident severity varies across locations and weather conditions.
- Historical accident patterns provide a basis for forecasting future trends.

## 📌 Recommendations

Based on the analysis:

- Prioritize road safety interventions in identified high-risk districts.
- Strengthen preventive measures during weather conditions associated with higher accident occurrence.
- Use district-level accident patterns to support emergency-response planning.
- Incorporate historical and predicted trends into road safety planning.
- Consider additional contextual factors to improve future prediction models.

## ⚠️ Limitations

- The analysis is based primarily on historical accident patterns from 2021–2023.
- Factors such as traffic volume, road conditions, and demographic characteristics are not currently incorporated.
- Future predictions may be affected by external conditions not represented in the historical dataset.
- Prediction reliability depends on the quality, completeness, and representativeness of the available data.

## 🚀 Future Improvements

- Incorporate traffic density, road conditions, and demographic factors.
- Explore additional forecasting and deep learning approaches.
- Add geospatial analysis for accident hotspot identification.
- Integrate real-time traffic and accident data.
- Develop automated alerts for emerging high-risk areas.

## 🗂️ Project Structure

```text
Road-Accident-Analysis-Prediction/
│
├── .devcontainer/
├── README.md
├── app.py
├── Updated_Data.xlsx
├── STATE WISE COMPARISON.png
├── WEATHER WISE ACCIDENT COMPARISON.png
├── logo.jpg
└── requirements.txt
```

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LSTM
- Plotly
- Matplotlib
- Seaborn
- Streamlit

## 👩‍💻 Author

**Hanne Jenifer R**

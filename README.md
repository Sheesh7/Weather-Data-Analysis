# 🌦️ Weather Data Analysis & Rain Prediction

This project explores hourly weather data, aggregates it into daily trends, and builds a logistic regression model to predict whether it will rain tomorrow.

---

## 🗂️ Project Overview

**Goal**: Use real hourly weather data to:

- Analyze temperature and rainfall patterns
- Visualize monthly trends in heat and rain
- Explore relationships between weather variables
- Predict if it will rain tomorrow using logistic regression

---

## 📊 Key Features

### ✅ Data Wrangling
- Aggregated **hourly data** into daily summaries
- Extracted hot days (`>18°C`) and rainy days from weather conditions
- Created `rain_tomorrow` column as the model target

### ✅ Visualizations
- Bar plots of **hot days by month** and **rainy days by month**
- Correlation matrix between temperature, humidity, pressure, wind, and visibility

### ✅ Modeling
- Built a **logistic regression model** using:
  - Temperature
  - Humidity
  - Pressure
  - Visibility
- Evaluated accuracy and interpreted coefficients

---

## 🧠 Dataset

- Format: Hourly weather data for one full year
- Sample columns:
  - `datetime`, `temperature`, `humidity`, `wind`, `pressure`, `visibility`, `condition`
- Created columns:
  - `hot_day`, `rainy_day`, `rain_tomorrow`

> If data is too large to include, use a small sample or mention the original source.

---

## 🧪 Libraries Used

- `pandas`, `numpy`
- `plotnine` for ggplot-style plotting
- `statsmodels` for logistic regression

---

## 🔍 Future Improvements

- Add more models (e.g., decision trees or random forests)
- Build an interactive dashboard with Streamlit
- Try hourly-level prediction instead of daily

---

## 📁 Files

| File | Description |
|------|-------------|
| `weather_analysis.ipynb` | Full analysis and model notebook |
| `weather_data.csv`       | Raw or sample data |
| `README.md`              | This project description |

---

## ✍️ Author

**Yashish R. Eriki**  
Data Science Student

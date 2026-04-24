# AIR-QUALITY-PREDICTION-AND-ANALYSIS
## 📌 Overview

Mandi Gobindgarh is one of Punjab's most industrially dense cities, home to hundreds of steel re-rolling mills. This project builds and benchmarks multiple time-series forecasting models to predict PM2.5 concentration (µg/m³) from historical air quality and weather data — contributing to early warning systems and pollution management.

**Dataset:** `mandi_Gobindgarh_15min_cleaned_2017_2024.csv`  
**Time span:** January 2017 – December 2024  
**Granularity:** 15-minute intervals (~105,000 readings)  
**Target variable:** PM2.5 (µg/m³)

---

## 🏆 Results

| Rank | Model | R² | RMSE | MAE |
|------|-------|----|------|-----|
| 🥇 1 | **GRU** | **0.9386** | **14.70** | **7.05** |
| 🥈 2 | LSTM | 0.9372 | 14.87 | 7.24 |
| 🥉 3 | CNN-LSTM | 0.9224 | 16.53 | 8.95 |
| 4 | XGBoost | 0.9072 | 16.75 | 6.77 |
| 5 | KNN | 0.9041 | 17.63 | 9.89 |

# 🚦 Traffic Volume Prediction

Machine learning project that predicts hourly traffic volume from weather and time data, deployed as a Streamlit web app.

## What it does
Forecasts the number of vehicles per hour using features like temperature, humidity, rain, pollution, and time (hour, day, holidays, weekends) — helping with signal timing, delivery planning, and traffic management.

## Results

| Model | R² | MAE |
|---|---|---|
| Linear Regression | 0.75 | 762 |
| Random Forest | 0.93 | 321 |
| **XGBoost (best)** | **0.94** | **308** |

## Tech Stack
Python, pandas, scikit-learn, XGBoost, Streamlit

## Run it
```bash
pip install -r requirements.txt
streamlit run app/app.py
```



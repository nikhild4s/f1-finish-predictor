# 🏎️ F1 Race Finish Predictor

> A data-driven web application that predicts a driver's finishing position in a Formula 1 race based on team performance and starting grid position.

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit&logoColor=white)
![Models](https://img.shields.io/badge/Models-ML%20Classification-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🔗 Live App
**[f1-predictor-pro.streamlit.app](https://f1-predictor-pro.streamlit.app/)**

---

## 🚀 Overview

This project explores how machine learning can be applied to motorsport analytics.  
Using historical race data, the app estimates a driver's final race position based on simple but impactful inputs like team and starting grid.

The focus is on building an interactive and lightweight prediction tool rather than a highly complex racing simulator.

---

## 🕹️ How it Works

- **Driver & Constructor Selection:** Choose a driver and their team  
- **Grid Position Input:** Set the starting position using a slider  
- **Prediction Output:** The model predicts the most likely finishing position  

---

## 📊 Data & Approach

- **Dataset:** Formula 1 World Championship dataset (filtered for modern-era races)  
- **Features used:** Constructor and grid position  
- **Models explored:** Multiple classification models were tested to evaluate performance  
- **Evaluation metrics:** Accuracy, classification metrics, and general prediction consistency  

💡 *Insight:* Team performance (constructor) combined with starting position plays a major role in predicting race outcomes.

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|------|
| `Pandas` | Data handling and preprocessing |
| `Scikit-learn` | Model building and evaluation |
| `XGBoost` | Gradient boosting model |
| `Matplotlib / Seaborn` | Visualizations |
| `Streamlit` | Frontend interface |

---

## 🚀 Run Locally

```bash
git clone https://github.com/nikhild4s/f1-finish-predictor.git
cd f1-finish-predictor
pip install -r requirements.txt
streamlit run app.py
```
## 📁 Project Structure

```
f1-finish-predictor/
├── app.py
├── f1_position_predictor_.py
├── model.css
├── requirements.txt
└── data/
    ├── constructors.csv
    ├── driver_standings.csv
    ├── drivers.csv
    ├── qualifying.csv
    ├── races.csv
    └── results.csv
```
---

## 🙌 Notes

- This project is built for learning and experimentation in ML + web deployment  
- Focus is on simplicity, usability, and understanding patterns in racing data  

---

## ⚠️ Disclaimer

This project is unofficial and not affiliated with Formula 1, FIA, or any official organization.

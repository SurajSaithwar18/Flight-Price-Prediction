# ✈️ Flight Price Prediction – Machine Learning Model

## 📌 Overview

This project focuses on building a machine learning model to **predict flight ticket prices** based on features such as airline, source, destination, duration, stops, and more.
This repository contains **only the model training notebook and the saved model file** (no web app).

---

## 📁 Project Structure

```
Flight-Price-Prediction/
│
├── Flight Price Prediction.ipynb
├── FlightPricePredection_model1.joblib
└── README.md
```

---

## 🧠 Features

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Handling categorical & numerical features
* Machine Learning model training
* Evaluation & metrics
* Model saved using joblib

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib / Seaborn
* Joblib

---

## 📦 Installation

```bash
git clone https://github.com/your-username/flight-price-prediction.git
cd flight-price-prediction
pip install -r requirements.txt
```

---

## ▶️ Run the Notebook

```bash
jupyter notebook "Flight Price Prediction.ipynb"
```

---

## 📂 Using the Saved Model

```python
import joblib
model = joblib.load("FlightPricePredection_model1.joblib")
prediction = model.predict(input_df)
print(prediction)
```

---

## 📊 Results

The notebook includes:

* Visualizations
* Model performance
* Feature importance
* Preprocessing steps

---

## 🚀 Future Work

* Add web interface (Flask / FastAPI)
* Deploy model online
* Improve accuracy with tuning



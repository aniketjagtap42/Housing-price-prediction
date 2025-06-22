
# 🏠 Housing Price Prediction App

This is a machine learning web application that predicts **housing prices** using real-world data from the USA housing market. The app is built with **Flask** and allows users to input area-specific features and get predicted house prices in real-time.

![Housing Price Prediction UI](ss/housing_ui_input.png)

---

## 📌 Project Overview

- **Dataset:** `USA_Housing.csv`
- **Models:** 13 Regression Models including Linear Regression, Random Forest, XGBoost, etc.
- **Frameworks:** Python, scikit-learn, pandas, Flask
- **Target Variable:** `Price`
- **Evaluation Metrics:** MAE, MSE, R²

---

## 🧠 Features Used for Prediction

- `Average Area Income`
- `Average Area House Age`
- `Average Area Number of Rooms`
- `Average Area Number of Bedrooms`
- `Area Population`

---
## requirements.txt

- 'flask'
- 'pandas'
- 'scikit-learn'
- 'xgboost'
- 'lightgbm'



## 🚀 How to Run the App Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/aniketjagtap42/housing-price-prediction.git
    cd housing-price-prediction
    ```

2. (Optional) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    source venv/bin/activate  # On Mac/Linux
    ```

3. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Train the models (if not already done):
    ```bash
    python model.py
    ```

5. Run the Flask app:
    ```bash
    python app.py
    ```

6. Open your browser and go to:
    [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧾 Files Included

| File Name                     | Description                                   |
|------------------------------|-----------------------------------------------|
| `app.py`                     | Flask web app script                          |
| `model.py`                   | Model training and evaluation code            |
| `model_evaluation_results.csv`| Evaluation results for all models            |
| `*.pkl`                      | Pickle files for all trained models           |
| `USA_Housing.csv`            | Dataset used for model training               |
| `templates/`                 | HTML templates for UI                         |
| `ss/`                        | Screenshots folder for README display         |

---

## 📷 App Preview

> Below is a working preview of the app:
![Prediction Result](ss/housing_prediction_result.png)
![Model Evaluation Table](ss/housing_model_evaluation.png)

---

## 💡 Future Improvements

- Add feature normalization & outlier detection
- Allow model comparison visually with plots
- Deploy the project on cloud (Render/Heroku/Vercel)

---

## 🔗 Connect With Me

- [LinkedIn](https://www.linkedin.com/in/aniket-jagtap-27b21835b)
- [GitHub](https://github.com/aniketjagtap42)

---


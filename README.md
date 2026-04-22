# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project predicts house prices using the California Housing dataset. It demonstrates a complete machine learning workflow including data preprocessing, model training, evaluation, and prediction.

---

## 📊 Dataset

* California Housing Dataset (housing.csv)
* Features include:

  * longitude, latitude
  * housing_median_age
  * total_rooms, total_bedrooms
  * population, households
  * median_income
  * ocean_proximity (categorical)
* Target:

  * median_house_value

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Joblib

---

## 🔄 Workflow

1. Data Loading
2. Data Cleaning (handling missing values)
3. Feature Engineering
4. Encoding categorical data
5. Train-Test Split
6. Model Training (Linear Regression)
7. Model Evaluation (RMSE & R² Score)
8. Model Saving
9. Prediction

---

## 📈 Model Performance

* RMSE: ~70,000
* R² Score: ~0.62

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/Sahillaghave/Syntecxhub_House_Price_Prediction.git
cd Syntecxhub_House_Price_Prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Train Model

```bash
python src/House_Prediction.ipynb
```

### 4. Run Prediction

```bash
python src/predict.ipynb
```

---

## 💡 Example Prediction

The model predicts house price based on input features such as location, income, and number of rooms.

---

## 🔮 Future Improvements

* Use Random Forest / XGBoost
* Hyperparameter tuning
* Deploy using Streamlit
* Add interactive dashboard

---

## 👨‍💻 Author

Sahil Laghave

---

## ⭐ If you like this project

Give it a star on GitHub!

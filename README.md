# car-ml-model-first
# 🚗 Ford Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of Ford cars using **Linear Regression**. It demonstrates the complete machine learning pipeline, from data preprocessing and feature engineering to model training, evaluation, and prediction.

The project uses the **Ford Car Price Dataset** and applies preprocessing techniques such as **One-Hot Encoding** and **StandardScaler** to improve prediction accuracy.

---

## 🎯 Features

* Data preprocessing and cleaning
* One-Hot Encoding for categorical variables
* Feature Scaling using StandardScaler
* Train-Test Split
* Linear Regression model
* Model evaluation using:

  * R² Score
  * Mean Absolute Error (MAE)
* Predicts the estimated selling price of a Ford car

---

## 📊 Dataset Features

| Feature      | Description                  |
| ------------ | ---------------------------- |
| Model        | Ford car model               |
| Year         | Manufacturing year           |
| Transmission | Manual, Automatic, Semi-Auto |
| Mileage      | Total distance driven        |
| Fuel Type    | Petrol, Diesel, Hybrid, etc. |
| Tax          | Road tax                     |
| MPG          | Miles per gallon             |
| Engine Size  | Engine capacity (L)          |
| Price        | Target variable              |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Kaggle Notebook

---

## ⚙️ Machine Learning Workflow

1. Load the dataset
2. Perform data preprocessing
3. Apply One-Hot Encoding to categorical features
4. Scale numerical features using StandardScaler
5. Split the dataset into training and testing sets
6. Train a Linear Regression model
7. Evaluate model performance
8. Predict car prices for new data

---

## 📈 Model Performance

**Algorithm:** Linear Regression

**Evaluation Metrics**

* Mean Absolute Error (MAE)
* R² Score

After applying **One-Hot Encoding**, the model achieved an **R² score of approximately 0.84**, which performed significantly better than Label Encoding.

---

## 📂 Project Structure

```text
Ford-Car-Price-Prediction/
│
├── Ford Car Price Prediction.ipynb
├── ford.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Ford-Car-Price-Prediction.git
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* Train advanced regression models (Random Forest, XGBoost, Gradient Boosting)
* Hyperparameter tuning
* Feature engineering
* Build a Streamlit web application
* Deploy the model online

---

## 📚 What I Learned

* Data preprocessing techniques
* Feature encoding methods
* Feature scaling
* Regression algorithms
* Model evaluation
* Building an end-to-end machine learning pipeline

---

## ⭐ If you found this project helpful, consider giving it a star!

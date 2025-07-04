# 💻 Laptop Price Prediction

A comprehensive *Machine Learning-based Web Application* that predicts laptop prices based on various specifications such as brand, processor, RAM, storage, and other technical features. This project aims to help users make informed decisions while comparing and understanding laptop prices.

---

## 🔍 Features

- *Custom Dataset*: Created by scraping publicly available laptop listings, cleaned and preprocessed for optimal model training.
- *Machine Learning Model*: Utilizes a regression model to predict laptop prices based on input features.
- *User-Friendly Interface*: Developed using HTML, CSS, and JavaScript for a responsive and interactive user experience.
- *Backend*: Powered by Django to manage model integration, data handling, and secure user interaction.
- *SQLite Database*: Stores user inputs and prediction results efficiently.
- *Data Visualization*: Integrated visualizations help users gain insights from data and model performance.
- *Dynamic Prediction Form*: Users can enter laptop specifications and get a predicted price in real-time.

---

## ⚙ How It Works

1. Users enter specifications (brand, RAM, storage, processor, etc.) in a simple web form.
2. Input data is processed and passed to a trained regression model.
3. The model returns the predicted price, displayed in a user-friendly format.
4. Users can also explore insights via visual dashboards.

---

## 🛠 Technology Stack

### ✅ Frontend:
- HTML, CSS, JavaScript  
- (Optional) Bootstrap 5.x for responsive design

### ✅ Backend:
- Django Framework

### ✅ Database:
- SQLite

### ✅ Machine Learning:
- Regression Model (Trained using Scikit-learn)

---

## 📦 Requirements

### 🐍 Software:
- *Python*: 3.10 or higher  
- *Django*: 4.x or higher

### 📚 Libraries:
- numpy >= 1.21.0 – for numerical computations  
- pandas >= 1.3.0 – for data handling and preprocessing  
- scikit-learn >= 0.24.0 – for model training and prediction  
- matplotlib >= 3.4.0 / seaborn >= 0.11.0 – for data visualization  
- joblib >= 1.2.0 – for model serialization

---

## 🚀 Steps to Run the Project Locally

1. *Download or Clone* this repository.
2. *Extract* the ZIP file if downloaded.
3. Open the project folder in *Visual Studio Code* or any preferred editor.
4. Open the *terminal* and navigate to the project directory:


cd laptop_price_prediction
cd laptop

python manage.py runserver

5. Open the web application in your browser by visiting
   http://127.0.0.1:8000/.

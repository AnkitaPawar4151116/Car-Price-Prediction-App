# Car-Price-Prediction-App
Car Price Prediction App

# 🚗 Car Price Prediction App

A simple and intuitive **machine learning web application** that predicts the fair resale price of a used car based on its specifications. Built using **Streamlit** and a trained regression model.

---

## 📌 Features

- Predicts used car prices based on:
  - Car company
  - Model name
  - Year of manufacture
  - Kilometers driven
  - Fuel type
- Easy-to-use web interface with **Streamlit**
- Trained using **Multiple Linear Regression** and real-world data
- Handles user input errors gracefully

---

## 🧠 Machine Learning Model

- **Model type**: Multiple Linear Regression
- **Data source**: Cleaned dataset of used cars
- **Preprocessing**:
  - One-hot encoding of categorical features (`company`, `name`, `fuel_type`)
  - Numerical features (`year`, `kms_driven`) passed through
- **Trained pipeline** is saved as: `CarProject.pkl`

---

## 🚀 How to Run Locally

### 1️⃣ Clone the repository or download files

```bash
git clone https://github.com/your-username/car-price-prediction-app.git
cd car-price-prediction-app
2️⃣ Install the required packages
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Streamlit app
bash
Copy
Edit
streamlit run app.py
📂 Files Included
File Name	Description
app.py	Main Streamlit app interface
CarProject.pkl	Trained machine learning pipeline
new_cleaned_data.xls	Cleaned dataset used during training
01-Data_Cleaning.ipynb	Data preprocessing notebook
02-EDA - Analysis.ipynb	Exploratory Data Analysis (EDA)
03 - model selection- MLR algorithm.ipynb	Model training notebook
Decision Tree Regression.ipynb	Alternative ML experiment
Random Forest Regression.ipynb	Alternative ML experiment
README.md	Project overview and instructions (this file)

🌐 Web UI Example
Once the app is running, you will see input fields like:

Company: Maruti

Model: Swift

Year: 2018

KMs Driven: 25000

Fuel Type: Petrol

After filling the form and clicking "Predict Price", the app will display:

✅ You should buy it for ~ ₹4,30,000 lakhs

📦 Requirements
Python 3.8+

pandas

streamlit

scikit-learn

numpy

pickle

Create a requirements.txt:

txt
Copy
Edit
streamlit
pandas
scikit-learn
numpy

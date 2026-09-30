# Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project predicts whether a person is likely to have diabetes based on medical and personal health-related information.

A Machine Learning model is trained using the **Pima Indians Diabetes Dataset**. The project includes data preprocessing, handling missing values, model training, prediction, and a Flask-based web application for making predictions.

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can predict diabetes based on different health parameters.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Flask
* HTML
* CSS
* Jupyter Notebook / PyCharm

## 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**.

The dataset contains medical information such as:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age
* Diabetes Outcome

The target variable indicates whether the person has diabetes or not.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Handling Missing Values
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Prediction
   ↓
Flask Web Application
```

## 🧹 Data Preprocessing

Some columns in the dataset contain zero values where a medical measurement would normally be expected.

Missing or invalid values are handled using **SimpleImputer** before training the model.

The data is then divided into:

* Training data
* Testing data

## 🤖 Machine Learning Model

The project uses the **Gaussian Naive Bayes (GaussianNB)** algorithm for diabetes prediction.

The model learns patterns from the training data and uses those patterns to predict whether new input data indicates diabetes.

## 🌐 Web Application

A Flask web application is used to provide a simple interface where users can enter the required health information.

The application sends the input values to the trained Machine Learning model and displays the prediction.

Example:

```text
User enters health information
          ↓
      Flask App
          ↓
   Trained ML Model
          ↓
      Prediction
          ↓
Diabetes / No Diabetes
```

## 📁 Project Structure

```text
Diabetes-Prediction/
│
├── app.py
├── diabetes.csv
├── model.pkl
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

> Adjust the filenames above according to the actual files in your project.

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Open the project folder

```bash
cd Diabetes-Prediction
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Flask application

```bash
python app.py
```

### 5. Open the application

Open the local Flask URL shown in the terminal, for example:

```text
http://127.0.0.1:5000/
```

## 💡 Example Prediction

The user provides values such as:

```text
Pregnancies: 2
Glucose: 120
Blood Pressure: 70
Skin Thickness: 25
Insulin: 80
BMI: 28.5
Age: 35
```

The trained model processes the input and provides a diabetes prediction.

## 📚 What I Learned

Through this project, I learned:

* How to load and explore a dataset using Pandas
* Data cleaning and preprocessing
* Handling missing values
* Splitting data into training and testing sets
* Training a Machine Learning model
* Making predictions using a trained model
* Saving and loading a Machine Learning model
* Connecting Machine Learning with Flask
* Creating a basic web interface for ML predictions

## ⚠️ Disclaimer

This project is created for **educational and demonstration purposes only**. It is not intended to provide medical diagnosis or replace professional medical advice.

## 👨‍💻 Author

**Venkatesh Dummala**

B.Tech - Computer Science and Engineering

Skills: Python | SQL | Pandas | NumPy | Machine Learning | Flask

# 🌊 Flood Prediction System using Machine Learning

## 📌 Project Overview

Floods are one of the most devastating natural disasters, causing loss of life, damage to infrastructure, and economic disruption. This project aims to predict the possibility of flood occurrence using Machine Learning techniques based on rainfall data.

The system analyzes monthly and seasonal rainfall values and predicts whether there is a likelihood of flooding. The trained Machine Learning model is integrated into a Flask web application that allows users to enter rainfall values and receive instant flood predictions.

---

## 🎯 Objectives

- Predict flood risk using rainfall data.
- Compare multiple Machine Learning algorithms.
- Select the best-performing model.
- Deploy the trained model using Flask.
- Provide an easy-to-use web interface for prediction.

---

## 🛠 Technologies Used

### Programming Language

- Python 3.8+

### Machine Learning Libraries

- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib

### Data Visualization

- Matplotlib

### Web Development

- Flask
- HTML5
- CSS3

---

## 📂 Dataset

**Dataset Name**

Rainfall in India (1901–2015)

The dataset contains rainfall records including:

- Monthly rainfall (January–December)
- Seasonal rainfall
- Annual rainfall
- State
- Year

Missing values were handled using Mean Imputation.

A Flood target column was created based on annual rainfall threshold for model training.

---

## 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Handling
4. Feature Engineering
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Best Model Selection
10. Model Deployment

---

## 🤖 Machine Learning Models Used

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- XGBoost

---

## 📈 Model Performance

| Model | Accuracy |
|--------|-----------|
| Decision Tree | 97.94% |
| Random Forest | **99.03%** |
| KNN | 97.69% |
| XGBoost | 98.91% |

🏆 **Best Model:** Random Forest Classifier

---

## 📁 Project Structure

```
Flood-Prediction/
│
├── app.py
├── requirements.txt
├── README.md
│
├── datasets/
│   └── rainfall_in_india_1901_2015.xlsx
│
├── model/
│   ├── model.pkl
│   └── scaler.pkl
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Model_Training.ipynb
│   └── 03_Flood_Prediction_Model.ipynb
│
├── static/
│   ├── css/
│   ├── images/
│   └── js/
│
└── templates/
    ├── base.html
    ├── index.html
    ├── about.html
    ├── predict.html
    └── result.html
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Flood-Prediction.git
```

### 2. Open the Project

```bash
cd Flood-Prediction
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Flask Application

```bash
python app.py
```

### 5. Open Browser

```
http://127.0.0.1:5000
```

---

## 💻 Features

- Rainfall-based Flood Prediction
- Interactive Flask Web Interface
- Multiple Machine Learning Models
- Automatic Model Selection
- Fast Prediction
- Easy-to-use User Interface

---

## 📸 Screenshots

Add screenshots here after completing the project.

### Home Page

(Add Screenshot)

### Prediction Page

(Add Screenshot)

### Result Page

(Add Screenshot)

---

## 📌 Future Enhancements

- Real-time weather API integration
- Live rainfall monitoring
- District-wise flood prediction
- Interactive rainfall visualization
- IBM Cloud deployment
- Mobile-friendly interface

---

## 👨‍💻 Team Members

- **Patan Irfan Khan** (Team Lead)
- Sharina Kovvuru
- **Jasmine Supraja Korrapati** (Team Member)
- Nallabathuni Pallavi
- Divya Sree Yedirinti Chittem Reddy

---

## 📚 Internship Project

This project was developed as part of a Machine Learning Internship focusing on flood prediction using rainfall data and Flask web application deployment.

---

## 📄 License

This project is developed for educational and internship purposes.
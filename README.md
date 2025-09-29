# 📊 Customer Churn Prediction

A machine learning project to predict customer churn in the telecom sector using the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn). The project involves data preprocessing, model training, evaluation, and deployment as an interactive web app using Streamlit.

🚀 **Live Demo**: [Streamlit App](https://customerchurnprediction1318.streamlit.app)

---

## 📌 Project Features

- ✅ Data Cleaning and Preprocessing  
- 📈 Exploratory Data Analysis (EDA)  
- 🧠 Model Training using Random Forest  
- 📊 Model Evaluation (Accuracy, Precision, Recall, ROC-AUC)  
- 🌐 Streamlit Web App for Real-Time Predictions  
- 💾 Serialized Model and Preprocessing Pipeline

---

## 🗂️ Project Structure

├── app.py # Streamlit app for prediction
├── ChurnPrediction.ipynb # Jupyter Notebook with EDA, preprocessing, model training
├── Churn_model.pkl # Trained Random Forest model
├── Preprocessor.pkl # Preprocessing pipeline (encoder, scaler, etc.)
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## 🧪 Model Performance

- **Model**: Random Forest Classifier  
- **Accuracy**: 78.78%  
- **Precision**: 63.70%  
- **Recall**: 46.11%  
- **ROC-AUC**: 68.33%  

### 🔑 Top Predictors:
- `TotalCharges`
- `tenure`
- `MonthlyCharges`
- `Contract`
- `PaymentMethod`

---

## 🛠️ Tech Stack

- Python, Pandas, Scikit-learn
- Streamlit (for web app)
- Joblib (for model serialization)
- Matplotlib & Seaborn (for visualization)

---

## 🚀 How to Run the Project Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```
### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Install Dependencies
```bash
streamlit run app.py
```

### 🌐 Access the Web App
👉 https://customer-churn-prediction-1318.streamlit.app/

### 🙋‍♂️ About the Author
Mehmood Ahmed
Python Developer | Data Analyst | Cybersecurity Enthusiast
    • 📧 mehmood3980350@gmail.com 
    • 🌐 https://www.linkedin.com/in/MehmoodAhmed-ds 
    • 🐙 https://github.com/mehmoodahmed-0303/

### 📜 License
This project is licensed under the MIT License - feel free to use, modify, and distribute it.

# 🧠 Teen Mental Health Analysis & Depression Prediction

An AI-powered Streamlit dashboard that analyzes teen mental health patterns and predicts depression risk using Machine Learning.

The project combines data visualization, mental health analytics, and predictive modeling to help identify factors associated with depression among teenagers.

---

## 📌 Features

- Interactive Streamlit Dashboard
- Teen Mental Health Data Analysis
- Depression Risk Prediction
- Real-Time User Input Prediction
- Beautiful and Responsive UI
- Interactive Charts and Visualizations
- Machine Learning Classification Model
- Model Evaluation Metrics

---

## 📸 Screenshots

Create a folder named `screenshots` and add your application images.

### Overview<img width="1468" height="841" alt="Screenshot 2026-06-02 at 5 45 13 PM" src="https://github.com/user-attachments/assets/b0434548-c40b-46d3-991a-d054be0ba779" />

### Correlations analysis
<img width="1467" height="838" alt="Screenshot 2026-06-02 at 5 46 03 PM" src="https://github.com/user-attachments/assets/f8ef3772-77da-4313-941a-9c2761d64e79" />

### Demographics
<img width="1470" height="835" alt="Screenshot 2026-06-02 at 5 46 24 PM" src="https://github.com/user-attachments/assets/a229650d-60f9-43c7-a85e-dd62c57210b2" />


### Depression
<img width="1467" height="831" alt="Screenshot 2026-06-02 at 5 46 47 PM" src="https://github.com/user-attachments/assets/667605c9-3f35-4ec3-84c7-eabae472f408" />

### Prediction
<img width="1467" height="832" alt="Screenshot 2026-06-02 at 5 47 23 PM" src="https://github.com/user-attachments/assets/a6a954aa-cd8e-4400-8478-2bd109e978a4" />


---

## 🏗️ Project Structure

```bash
Teen-Mental-Health-Analysis/
│
├── app.py
├── train.py
├── Teen_Mental_Health_Dataset.csv
├── teen_mental_health_model.pkl
├── screenshots/
│   ├── dashboard.png
│   ├── analysis.png
│   ├── prediction.png
│   └── performance.png
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Information

The dataset contains various factors affecting teen mental health, including:

- Age
- Gender
- Social Media Usage
- Screen Time
- Sleep Duration
- Stress Level
- Anxiety Level
- Academic Performance
- Physical Activity
- Social Interaction
- Addiction Level

### Target Variable

- `depression_label`

The model predicts whether a teenager is at risk of depression based on behavioral and lifestyle attributes.

---

## 🤖 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Handling
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Model Training
8. Prediction
9. Evaluation
10. Deployment with Streamlit

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-Learn
- Random Forest Classifier

### Data Processing

- Pandas
- NumPy

### Visualization

- Plotly Express
- Plotly Graph Objects

### Deployment

- Streamlit

### Model Storage

- Joblib

---

## ⚙️ Model Details

### Algorithm

Random Forest Classifier

### Preprocessing Techniques

- Missing Value Imputation
- Standard Scaling
- One-Hot Encoding
- Column Transformer Pipeline

### Evaluation Metrics

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/teen-mental-health-analysis.git
cd teen-mental-health-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Train the Model

```bash
python train.py
```

This generates:

```bash
teen_mental_health_model.pkl
```

---

## ▶️ Run Streamlit Application

```bash
streamlit run app.py
```

---

## 📈 Dashboard Modules

### Overview

Provides summary statistics and mental health insights.

### Analytics

Interactive visualizations showing relationships between:

- Social Media Usage
- Stress Levels
- Anxiety Levels
- Sleep Duration
- Academic Performance

### Prediction

Users can enter mental health and lifestyle information to predict depression risk.

### Evaluation

Displays machine learning performance metrics.

---

## 🔮 Future Enhancements

- Deep Learning Models
- Mental Health Recommendation System
- Real-Time Monitoring
- Cloud Deployment
- User Authentication
- Report Generation

---



## ⭐ Acknowledgements

This project was developed for educational and research purposes to explore the impact of behavioral and lifestyle factors on teen mental health using Machine Learning.

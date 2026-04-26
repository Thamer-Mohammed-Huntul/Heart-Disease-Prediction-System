<img width="1899" height="1074" alt="image" src="https://github.com/user-attachments/assets/1d3ce409-11c0-495c-bddc-ae85b990c770" /># Heart Disease Prediction System

A machine learning web application that predicts the likelihood of heart disease based on clinical patient data.

---

## Overview

This project implements an end-to-end machine learning pipeline including:

* Data preprocessing
* Model training and evaluation
* Deployment as a web application

The system allows users to input medical data and receive:

* Prediction (Healthy / Disease)
* Risk probability
* Smart analysis based on input values
* Personalized recommendations

---

## Models Used

* Random Forest (best performing)
* TabNet
* KNN
* Decision Tree

Random Forest achieved the best performance.

---

## Model Performance

* Accuracy: ~82–85%
* Cross-validation score: ~0.82
* Evaluation Metrics:

  * Accuracy
  * Recall
  * F1-score
  * ROC-AUC
  * Confusion Matrix

---

## Dataset

* 303 samples
* 13 clinical features including:

  * Age
  * Cholesterol
  * Blood Pressure
  * Heart Rate
  * And more

---

## Web Application

Built using Flask with an interactive dashboard.

### Features:

* Clean UI with structured input fields
* Real-time prediction
* Risk visualization (Disease vs No Disease)
* Smart analysis based on patient values
* Recommendations system

---

## Technologies

* Python
* Pandas
* Scikit-learn
* Flask
* HTML / CSS
* Joblib

---

## How to Run

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction-System.git
cd Heart-Disease-Prediction-System
pip install -r requirements.txt
python app.py
```

Then open:

```
http://127.0.0.1:5000
```

---

## Screenshot

<img width="1899" height="1074" alt="image" src="https://github.com/user-attachments/assets/4be4f055-6062-4c60-9995-08c0c686b83e" />


---

## Future Improvements

* Add more medical datasets
* Improve model accuracy
* Deploy on cloud with scaling
* Add more explainable AI features

---

## Author

Thamer Mohammed Hantool

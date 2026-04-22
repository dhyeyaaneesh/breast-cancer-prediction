# MammoPredict AI — Breast Cancer Prediction & Explainability

An interactive web-based ML simulation that predicts whether a breast tumor is **benign or malignant** using clinical-style inputs, with **real-time explainability and visual insights**.

---

## Overview

MammoPredict AI is a **frontend-driven ML application** that simulates a clinical decision-support system.

Instead of requiring complex medical measurements, users answer a short questionnaire (size, shape, texture, etc.), which is internally mapped to computational features used in machine learning models.

The system then provides:
- Prediction (Benign / Malignant)
- Confidence score
- Feature-level explanation (SHAP-style)
- Visual analytics dashboard

---

## Key Features

- **Clinical Questionnaire Interface**  
  Converts simple medical observations into ML-compatible features  

- **Model Simulation (JS-based)**  
  Logistic Regression, Decision Tree, Random Forest logic implemented in-browser  

- **Interactive Dashboard**  
  Dataset insights, charts, and feature comparisons using Chart.js  

- **Explainable AI (SHAP-style)**  
  Shows how each feature contributes to the final prediction  

- **Model Evaluation UI**  
  Confusion matrix, ROC curves, and performance metrics  

- **Prediction History Tracking**  
  Stores session-based predictions  

---

## How It Works

1. User answers 5 clinical questions:
   - Lump size  
   - Shape  
   - Texture  
   - Margin  
   - Concavities  

2. Inputs are mapped to **30 numerical features** (simulating real ML datasets)

3. A selected model computes:
   - Prediction (Benign / Malignant)  
   - Probability score  

4. System displays:
   - Prediction result  
   - Confidence  
   - Feature importance breakdown  

---

## Dataset (Simulated)

- Based on **Breast Cancer Wisconsin Dataset (UCI)**
- 569 samples  
- 30 numerical features  
- No missing values  

Note:  
This app **does not directly train models in real-time**. Instead, it simulates model behavior using predefined feature ranges and logic derived from the dataset. :contentReference[oaicite:0]{index=0}

---

## Tech Stack

- **HTML5 / CSS3**
- **JavaScript (Vanilla)**
- **Chart.js** (data visualization)
- UI/UX design with responsive layout

---

## Disclaimer

This application is for **educational and demonstration purposes only**.

It is **not a medical diagnostic tool** and should not be used for real-world healthcare decisions.

---

## Author

Dhyeya Aneesh

---

## License

MIT

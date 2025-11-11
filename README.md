# HealthForecast

HealthForecast is an AI-powered health prediction and lifestyle guidance system. It analyzes user health inputs to estimate potential health risks and provides personalized recommendations to improve overall wellness. The aim is to help users take preventive actions early and make informed decisions regarding their health.

### Live Demo
https://Bhavana-1128-healthforest.hf.space

---

## Features
- Predicts potential health risks based on user inputs.
- Provides personalized lifestyle and diet recommendations.
- Simple and interactive user interface.
- Uses machine learning for accurate predictions.
- Runs directly in the browser via Hugging Face Spaces.

---

## Tech Stack

| Component       | Technology Used          |
|----------------|--------------------------|
| Programming    | Python                   |
| Machine Learning Model | Random Forest / Logistic Regression |
| Frontend UI    | Gradio                   |
| Deployment     | Hugging Face Spaces      |

---

## Dataset
The dataset contains health-related attributes such as:
- Age  
- BMI  
- Glucose levels  
- Blood pressure  
- Other health parameters

The model is trained to analyze these parameters and identify health risk patterns.

---

## How It Works
1. The user enters basic health metrics.
2. The trained machine learning model processes these inputs.
3. The system predicts the probability of potential health risks.
4. The user receives lifestyle recommendations tailored to their profile.

---

## Run Locally

```bash
git clone https://github.com/Bhavana244-blip/healthforecast.git
cd healthforecast
pip install -r requirements.txt
python app.py

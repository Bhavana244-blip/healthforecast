HealthForecast

HealthForecast is an AI-powered health prediction and lifestyle guidance system. It analyzes user health inputs to estimate potential health risks and provides personalized recommendations to improve overall wellness. The goal is to help users take preventive actions early and make informed lifestyle decisions.

Live Demo

Access the running application here:
https://Bhavana-1128-healthforest.hf.space

Features

Predicts disease risk based on user-provided health data.

Provides personalized lifestyle & diet recommendations.

Easy-to-use interface for quick analysis.

Built with Machine Learning & interactive UI.

Tech Stack
Component	Technology
Backend	Python
Machine Learning	Random Forest / Logistic Regression (as configured in model)
Interface	Gradio
Deployment	Hugging Face Spaces
Dataset

The dataset used includes health-related metrics such as:

Age

BMI / Weight & Height

Glucose Levels

Blood Pressure

Other medical indicators depending on model type.

This data is processed to train a predictive model that outputs health risk probabilities.

How It Works

User enters health parameters.

Model processes inputs and predicts risk.

Personalized recommendation suggestions are displayed.

The user can adjust lifestyle habits based on feedback.

Installation (If running locally)
git clone https://github.com/Bhavana244-blip/healthforecast.git
cd healthforecast
pip install -r requirements.txt
python app.py

Future Enhancements

Expand predictions to more health conditions.

Add medical report upload and automatic parameter extraction.

Include doctor-assisted chatbot guidance.

Mobile-friendly UI.

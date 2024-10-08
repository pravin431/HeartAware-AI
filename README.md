# Cardiovascular Disease Predictor App

A web application built using Flask and machine learning that predicts the likelihood of cardiovascular disease based on user inputs such as age, gender, cholesterol levels, blood pressure, and more.

## 🚀 Features

- **Machine Learning Powered**: Utilizes a pre-trained machine learning model to make accurate predictions.
- **User-Friendly Interface**: Simple and responsive web interface to collect user inputs and display results.
- **Comprehensive Inputs**: Considers multiple factors like age, gender, blood pressure, cholesterol levels, glucose, smoking habits, alcohol consumption, and physical activity.
- **Real-time Prediction**: Provides real-time results after processing user data.
- **Scalable**: Designed using Flask, making it easy to extend and scale.
- **Interactive Health Tips**: Based on the prediction, users are provided with relevant health tips and resources.

## 📐 Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/pravin431/HeartAware-AI.git
    cd HeartAware-AI
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python app.py
    ```

## Usage

1. **Input Your Information**: Enter your age, gender, height, weight, blood pressure (systolic and diastolic), cholesterol level, glucose level, and lifestyle habits (smoking, alcohol consumption, physical activity).
2. **Get Your Prediction**: Submit the form, and the app will predict whether you are at risk for cardiovascular disease.
3. **View Results**: Based on the prediction, the app will provide additional health resources and tips to either maintain a healthy lifestyle or take preventive measures.

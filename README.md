# Heart Disease Prediction

A machine learning web application built using Python and Streamlit to predict the likelihood of heart disease based on user-provided health parameters.

## Features

- Interactive web interface built with Streamlit
- Predicts heart disease risk using a trained machine learning model
- Accepts inputs such as age, sex, chest pain type, resting blood pressure, cholesterol, and maximum heart rate
- Uses saved model and preprocessing files for predictions
- Displays predictions in real time

## Tech Stack

- **Python** — Core programming language
- **Streamlit** — Web application interface
- **Pandas & NumPy** — Data handling
- **Scikit-learn** — Machine learning and preprocessing
- **Joblib** — Loading saved model files

## Project Structure

```text
Heart-Disease-Prediction/
├── app.py
├── logistic_heart_disease.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── requirements.txt
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/vaibhavarora1205/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

Replace `vaibhavarora1205` with your GitHub username.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run app.py
```

The application will open in your browser, usually at `http://localhost:8501`.

## How It Works

1. Enter the required health parameters in the application.
2. Click the prediction button.
3. The application preprocesses the inputs and passes them to the trained machine learning model.
4. The model returns a prediction that is displayed on the webpage.

## Deployment

This application can be deployed using [Streamlit Community Cloud](https://share.streamlit.io/).

## Disclaimer

This project is developed for educational and learning purposes only. Its predictions are not a medical diagnosis and should not be used as a substitute for professional medical advice.

## Author

**Vaibhav Arora**

GitHub: [@vaibhavarora1205](https://github.com/vaibhavarora1205)
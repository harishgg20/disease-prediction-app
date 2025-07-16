# Disease Prediction Application

This project is a web application that uses various machine learning models to predict the likelihood of several diseases. The application is built with Streamlit and provides a user-friendly interface for users to input their health data and get a prediction.

The application can predict the following diseases:
- Diabetes
- Heart Disease
- Parkinson's Disease
- Lung Cancer
- Hypothyroidism

## Features

- **Multi-Disease Prediction:** The application supports the prediction of five different diseases.
- **User-Friendly Interface:** The application has a simple and intuitive interface built with Streamlit.
- **Easy to Use:** Users can easily input their health data and get a prediction with the click of a button.
- **Pre-trained Models:** The application uses pre-trained machine learning models to make predictions.

## Setup and Running the Application

To run this application locally, you will need to have Python installed.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/disease-prediction-app.git
   ```
2. **Navigate to the project directory:**
    ```bash
    cd disease-prediction-app
    ```
3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the application:**
    ```bash
    streamlit run app.py
    ```

## Project Structure

```
.
├── .devcontainer
│   └── devcontainer.json
├── Models
│   ├── Thyroid_model.sav
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── lungs_disease_model.sav
│   └── parkinsons_model.sav
├── Heart_Disease_Prediction.ipynb
├── Lung_Cancer.ipynb
├── Parkinson's_Disease_Detection.ipynb
├── Thyroid.ipynb
├── app.py
├── requirements.txt
└── README.md
```

## Models

The application uses the following machine learning models:

- **Diabetes Prediction:** `diabetes_model.sav`
- **Heart Disease Prediction:** `heart_disease_model.sav`
- **Parkinson's Disease Prediction:** `parkinsons_model.sav`
- **Lung Cancer Prediction:** `lungs_disease_model.sav`
- **Hypo-Thyroid Prediction:** `Thyroid_model.sav`

## Usage

1. **Select a disease:** Choose a disease from the dropdown menu.
2. **Enter the required information:** Fill in the input fields with the required health data.
3. **Get a prediction:** Click the "Test Result" button to get a prediction.

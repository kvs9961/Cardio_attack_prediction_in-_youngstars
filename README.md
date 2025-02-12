# Cardio Attack Prediction in Youngstars

## Problem Statement
Predict heart attack likelihood in individuals aged 18–35 using demographics, lifestyle, medical history, and clinical test data to enable early diagnosis and prevention.

## About the Dataset

### **Demographics**
- **Age:** Captures the age range of individuals (18–35 years).
- **Gender:** Distribution among males, females, and others.
- **Region:** Geographical zones (e.g., North, South, East, West, etc.).
- **Urban/Rural:** Differentiates between urban and rural populations.
- **Socioeconomic Status (SES):** Low, middle, or high economic tiers.

### **Lifestyle Factors**
- **Smoking and Alcohol Consumption:** Frequency categories (e.g., never, occasionally, regularly).
- **Dietary Preferences:** Vegetarian, non-vegetarian, and vegan choices.
- **Physical Activity:** Levels (sedentary, moderate, high).
- **Screen Time:** Hours spent on screens per day (digital exposure).
- **Sleep Duration:** Average sleep hours per night.

### **Medical History**
- **Family History of Heart Disease:** Presence of hereditary risk.
- **Diabetes and Hypertension:** Binary indicators of chronic conditions.
- **Cholesterol Levels:** Total cholesterol in mg/dL.
- **BMI:** Body mass index as an obesity metric.
- **Stress Levels:** Low, medium, or high.

### **Clinical and Test Results**
- **Blood Pressure (Sys/Dia):** Systolic/diastolic pressure in mmHg.
- **Resting Heart Rate:** Beats per minute at rest.
- **ECG Results:** Normal or abnormal heart electrical activity.
- **Chest Pain Type:** Categories of pain experienced (typical, atypical, etc.).
- **Maximum Heart Rate Achieved:** During stress or exercise.
- **Exercise-Induced Angina:** Whether angina is triggered by exertion.
- **Blood Oxygen Levels (SpO2%):** Oxygen saturation in the bloodstream.
- **Triglyceride Levels:** Fat content in the blood (mg/dL).

### **Target Variable**
- **Heart Attack Likelihood:** Binary target indicating the presence (Yes) or absence (No) of heart attack risk.

## Project Structure
```
|-- .gradio/flagged  # Directory for Gradio flagged data
|-- .ipynb_checkpoints  # Jupyter Notebook checkpoints
|-- .gitattributes  # Git metadata
|-- Heart_Attack_Prediction_model.pkl  # Trained prediction model
|-- ML_final_Project.ipynb  # Final machine learning model notebook
|-- app.ipynb  # Application notebook
|-- heart_attack_youngsters_india.csv  # Dataset used for prediction
|-- projet.ipynb  # Project notebook
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/kvs9961/Cardio_attack_prediction_in-_youngstars.git
   cd Cardio_attack_prediction_in-_youngstars
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and execute `ML_final_Project.ipynb` or `app.ipynb`.

## Technologies Used
- **Python**
- **Pandas & NumPy**
- **scikit-learn**
- **Matplotlib & Seaborn**
- **Machine Learning**
- **Gradio**
- **Machine Learning Algorithms**

## Usage
- Load the dataset (`heart_attack_youngsters_india.csv`).
- Train and save the model (`Heart_Attack_Prediction_model.pkl`).
- Use `app.ipynb` to test predictions.
- Analyze results using `ML_final_Project.ipynb`.

## Future Enhancements
- Improve model accuracy with deep learning techniques.
- Deploy the model as a web application.
- Integrate real-time data collection.
- Enhance dataset with additional medical parameters.

## Contributors
- **Kvs9961** - Project Developer

## License
This project is licensed under the MIT License


# Heart Disease Prediction

A machine learning web app that predicts the likelihood of heart disease from a patient's clinical data. The model is built with Python and scikit-learn, and the user interface is built with Streamlit.

⚠️ Disclaimer: This project is for educational purposes only. It is not a medical device and must not be used for real diagnosis or treatment decisions. Always consult a qualified doctor.

Features
Enter patient details through a simple web form
Get an instant prediction: heart disease risk or no risk
Trained on a well-known heart disease dataset
Lightweight and easy to run locally
Tech Stack
Language: Python 3.x
ML: scikit-learn, pandas, NumPy
UI: Streamlit
Model: [e.g. Logistic Regression / Random Forest]
Dataset

The model is trained on the Heart Disease dataset (UCI). Input features include:

Feature	Description
age	Age in years
sex	Sex (1 = male, 0 = female)
cp	Chest pain type
trestbps	Resting blood pressure (mm Hg)
chol	Serum cholesterol (mg/dl)
fbs	Fasting blood sugar > 120 mg/dl
restecg	Resting ECG results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression induced by exercise
slope	Slope of the peak exercise ST segment
ca	Number of major vessels (0-3)
thal	Thalassemia type

Target: presence (1) or absence (0) of heart disease.

Project Structure
Heart_Disease_Prediction/
├── app.py                # Streamlit app
├── model.pkl             # Trained model
├── heart.csv             # Dataset
├── notebook.ipynb        # Training and analysis
├── requirements.txt      # Dependencies
└── README.md
Installation and Usage
Clone the repository
bash
   git clone https://github.com/navaneethb620-art/Heart_Disease_Prediction.git
   cd Heart_Disease_Prediction
Create a virtual environment (optional but recommended)
bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
Install dependencies
bash
   pip install -r requirements.txt
Run the app
bash
   streamlit run app.py
Open the URL shown in the terminal (usually http://localhost:8501).
Model Performance
Metric	Score
Accuracy	[xx%]
Precision	[xx%]
Recall	[xx%]
F1-score	[xx%]
Future Improvements
Try more models and hyperparameter tuning
Add feature importance and explanation of predictions
Deploy on Streamlit Community Cloud
Author

Navaneeth B - GitHub

License

This project is licensed under the MIT License.

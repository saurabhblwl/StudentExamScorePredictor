A Machine Learning-based web application that predicts student exam scores based on academic and lifestyle factors such as study hours, attendance, sleep duration, mental health, and part-time job status.

Features
Predicts exam scores using a trained regression model
Real-time prediction with interactive UI
Uses machine learning for pattern recognition
Displays accurate results based on user input
Simple and user-friendly interface

How It Works
User inputs:
Study Hours
Attendance
Sleep Hours
Mental Health
Part-time Job
Data is preprocessed and passed to the trained model
Model predicts exam score
Result is displayed instantly

 Tech Stack
Python
NumPy
Scikit-learn
Streamlit


Model Performance
R² Score: ~0.82
Mean Absolute Error (MAE): ~4.5

Note: Performance may vary depending on dataset and training.

Project Structure
ExamScorePredictor/
│
├── app.py                 # Streamlit frontend
├── model.pkl             # Trained ML model
├── dataset.csv           # Dataset used
├── train_model.py        # Model training script
└── README.md             # Project documentation

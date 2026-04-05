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

<img width="1272" height="828" alt="Screenshot 2026-04-05 100838" src="https://github.com/user-attachments/assets/e3c20f5c-aceb-4558-b275-de3949e99349" />

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

# End To  End Machine Learning Project

## Student Performance Prediction

This project aims to predict students' math scores based on various demographic and educational factors using machine learning. The model is built in Python, and the application is deployed using Flask. Key techniques include data preprocessing with one-hot encoding, standard scaling, and pipelines. Additionally, logging and custom exception handling are implemented to enhance robustness.

### Use model

link : https://student-performance-prediction-62zc.onrender.com

![alt text](<Screenshot (69).png>)

### Project Overview

Educational performance prediction can help identify students who may need additional support. This project focuses on predicting the math scores of students based on features like gender, race/ethnicity, parental education level, lunch type, test preparation course completion, reading score, and writing score.

### project structure

Student Performance Prediction/ ├── artifact # Model artifacts and output files ├── logs # Logs for monitoring and debugging ├── notebook # Jupyter notebooks for experimentation ├── src # Source code for the application ├── Student_Performance_prediction.egg-info # Metadata for the package ├── templates # HTML templates for the web interface ├── venv # Virtual environment for dependencies ├── .gitignore # Specifies files to ignore in version control ├── app.py # Main application file ├── README.md # Project documentation ├── requirements.txt # List of dependencies ├── Screenshot (69).png # Screenshot of model deployment └── setup.py # Setup script for packaging

### Features

- **Gender**: Student's gender.
- **Race/Ethnicity**: Student's race or ethnicity.
- **Parental Level of Education**: Highest education level attained by a student's parent(s).
- **Lunch**: Type of lunch received by the student (standard/reduced).
- **Test Preparation Course**: Whether the student completed a test preparation course.
- **Reading Score**: Student's score in reading.
- **Writing Score**: Student's score in writing.
  
**Target Variable**
- **Math Score**: The score to be predicted.


### Data Preprocessing

- **One-Hot Encoding**: Applied to categorical features (gender, race/ethnicity, parental level of    education, lunch, test preparation course) to convert them into numerical format.
- **Standard Scaling**: Used to normalize numerical features (reading score, writing score).
- **Pipeline**: Created a pipeline for streamlined data preprocessing and model training.

### Model Building
- **Machine Learning Model**: A best regression algorithm was selected and trained to predict the math score.
- **Custom Exception Handling**: Implemented custom exception handling to improve code reliability.
- **Logging**: Logging is set up to monitor key steps and identify potential issues.

### API Deployment
- **Flask**: Used Flask to build and deploy an API that allows users to make predictions on new student data.


### Hosting
- **Render Cloud**: The application is hosted on Render Cloud, which provides a reliable and scalable solution for deploying web applications.

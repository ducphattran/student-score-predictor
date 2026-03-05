# 🎓 Student Exam Score Predictor

An interactive Machine Learning application built with **Streamlit** that predicts a student's final exam score based on their daily habits and lifestyle factors.

## 🔗 Quick Links
* **[Live Demo](https://studentscorepredictor-f8qn5kfgccagvv9gts43aw.streamlit.app/)** ← *Click here to use the app immediately!*
* **Deploy Your Own:** [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/deploy?repository=ducphattran/student-score-predictor&main_file=app.py)

## 🚀 Overview
This project uses a Linear Regression model trained on student performance data to analyze how variables like study hours, attendance, and mental health impact academic outcomes. The app provides a user-friendly interface where anyone can adjust sliders to see real-time score predictions.

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Framework:** [Streamlit](https://streamlit.io/)
* **ML Library:** Scikit-learn
* **Data Handling:** Pandas & NumPy
* **Model Persistence:** Joblib

## 📁 Project Structure
* `app.py`: The main Streamlit application script.
* `best_model.pkl`: The pre-trained Linear Regression model.
* `requirements.txt`: Configuration file for cloud deployment (Linux compatible).
* `notebook.ipynb`: The Jupyter Notebook containing data cleaning and model training.
* `student_habits_performance.csv`: The raw dataset.

## 🔧 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ducphattran/student-score-predictor.git](https://github.com/ducphattran/student-score-predictor.git)
   cd student-score-predictor
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
3. **Run the app**
   ```bash
   streamlit run app.py

📊 Model Features
The predictor analyzes the following inputs to generate a score:

**Study Hours: Daily time spent studying.**

**Attendance: Percentage of classes attended.**

**Mental Health: Self-reported rating on a scale of 1-10.**

**Sleep: Average hours of sleep per night.**

**Exercise: Number of days per week spent exercising.**

**Diet Quality: Categorical input (Poor, Fair, Good).**

**Part-time Job: Whether the student is currently employed.**

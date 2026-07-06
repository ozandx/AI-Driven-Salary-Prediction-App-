# 💼 AI-Driven Salary Prediction App 

A simple machine learning web application built with **Streamlit** that predicts an employee's salary based on the number of years at the company and their job rating.

## 🚀 Features

- Predict employee salary instantly
- Simple and interactive Streamlit interface
- Machine Learning model trained using Linear Regression
- Fast and lightweight deployment

---

## 📂 Project Structure

```
.
├── app.py                  # Streamlit application
├── linearmodel.pkl         # Trained Linear Regression model
├── Employees.xlsx          # Dataset
├── AI_Powered_Job_Salary_Prediction.ipynb   # Model training notebook
├── requirements.txt
└── README.md
```

---

## 📊 Input Features

The application requires two inputs:

| Feature | Description |
|----------|-------------|
| Years at Company | Number of years the employee has worked at the company |
| Job Rate | Employee performance/job rating |

---

## 🧠 Machine Learning Model

The salary prediction model was trained using **Linear Regression** from Scikit-learn.

Workflow:

1. Load employee dataset
2. Train Linear Regression model
3. Save the trained model using Joblib
4. Load the model inside the Streamlit app
5. Predict salary from user inputs

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Powered-Job-Salary-Prediction.git
cd AI-Powered-Job-Salary-Prediction
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app:

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📷 Application Preview

The application allows users to:

- Enter Years at Company
- Enter Job Rate
- Click **"Press the button for salary prediction"**
- View the predicted salary

---

## 📦 Requirements

- Python 3.9+
- Streamlit
- NumPy
- Joblib
- Scikit-learn

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📈 Example

Input:

```
Years at Company: 5
Job Rate: 4.5
```

Output:

```
Salary Prediction is $XX,XXX.XX
```

---

## 🛠️ Technologies Used

- Python
- Streamlit
- NumPy
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

Created as an AI-Powered Job Salary Prediction project using Machine Learning and Streamlit.

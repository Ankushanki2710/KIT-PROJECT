# 🎓 Student Performance Prediction & Analysis using Machine Learning



## 📌 Overview

This project predicts student academic performance using Machine Learning.
It analyzes key factors like study hours, attendance, previous grades, and parental education to estimate final grades.

---

## 🚀 Features

* 📊 Data preprocessing and cleaning
* 🤖 Machine Learning model training
* 📈 Model evaluation (MSE, R² Score)
* 🌐 REST API using Flask
* 📉 Data visualization

---

## 🧠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikit-learn)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge\&logo=flask)

---

## 📂 Project Structure

```bash
student-performance-ml/
│
├── data/
│   └── student_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train_model.py
│   ├── evaluate.py
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset Features

* Gender
* Study Hours
* Attendance
* Previous Grades
* Parent Education
* Final Grade (Target)

---

## ⚙️ Installation

```bash
git clone https://github.com/Ankushanki2710/student-performance-ml.git
cd student-performance-ml
pip install -r requirements.txt
```

---

## ▶️ Usage

### 1️⃣ Train Model

```bash
python src/train_model.py
```

### 2️⃣ Evaluate Model

```bash
python src/evaluate.py
```

### 3️⃣ Run API

```bash
python app.py
```

---

## 📡 API Example

### Endpoint:

`POST /predict`

### Request:

```bash
curl -X POST http://127.0.0.1:5000/predict \
-H "Content-Type: application/json" \
-d '{
  "gender": 1,
  "study_hours": 5,
  "attendance": 90,
  "previous_grade": 80,
  "parent_education": 2
}'
```

### Response:

```json
{
  "predicted_grade": 85.4
}
```

---

## 📈 Model Performance

* Mean Squared Error (MSE)
* R² Score

*(Varies based on dataset size and quality)*

---

## 🎥 Demo

*Add your demo GIF or screenshots here*

---

## 🔮 Future Improvements

* 📱 Frontend UI (React / Streamlit)
* 🤖 Multiple model comparison
* 📊 Advanced dashboards
* ☁️ Deployment (AWS / Render / Vercel)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the MIT License.

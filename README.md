##summary
# 🎓 Student Performance Predictor using AI

This project is a machine learning-based solution designed to predict student academic performance levels — such as *Excellent*, *Good*, *Average*, or *At Risk* — using minimal input features like **attendance**, **internal assessment scores**, and **weekly study hours**.

The model helps in early identification of underperforming students to assist educators with timely interventions and academic planning.

---

## 📌 Features

- Uses a **Random Forest Classifier** for multi-class prediction  
- Trained on a sample academic dataset  
- Input features: Attendance %, Internal Score, Study Hours  
- Output categories: Excellent, Good, Average, At Risk  
- Executed in **Google Colab** for cloud accessibility  
- Simple prediction function for new data

---

## 🛠️ Technologies Used

- **Python**  
- **Google Colab**  
- **Scikit-learn** – ML modeling  
- **Pandas & NumPy** – Data handling  
- **Joblib** – Model saving/loading  
- **Matplotlib/Seaborn** – Visualization (optional)

---

## 📁 Project Structure

Student-Performance-Predictor-using-AI/
│
├── student_performance_dataset.csv # Sample dataset
├── student_performance_model.pkl # Trained Random Forest model
├── label_encoder.pkl # Label encoder for decoding predictions
├── app.py # Optional Streamlit app file
├── requirements.txt # Python dependencies
└── README.md # Project description

---

## 🚀 How It Works

1. Load dataset (CSV with attendance, scores, and hours)
2. Encode performance labels using LabelEncoder
3. Train a Random Forest model on 70% of the data
4. Predict student performance category
5. Evaluate model using accuracy score and confusion matrix

---

## 📊 Model Accuracy

- Achieved **~89% accuracy** on test data  
- Feature importance ranking:
  1. Internal Score
  2. Attendance
  3. Study Hours

---

## 🔗 Live Demo & Source Code

- 🧠 **Google Colab Notebook**:  
  [Click here to run in Colab](https://colab.research.google.com/drive/1CHXA2a6-uRgAy_vTcx5kQma-FsjL1WcE?usp=sharing)

- 💻 **GitHub Repository**:  
  [https://github.com/AdilBasha18/Student-Performance-Predictor-using-AI](https://github.com/AdilBasha18/Student-Performance-Predictor-using-AI)

---

## 💡 Future Improvements

- Add behavioral and psychological inputs (e.g., engagement, stress levels)  
- Integrate with LMS platforms for real-time data  
- Deploy as a web app (Streamlit/Flask)  
- Expand dataset to improve model generalization

---

## 👨‍💻 Author

**Adil Basha**  
[GITAM UINVERSITY BANGLORE]
AICTE Microsoft Internship – AI/ML Track  

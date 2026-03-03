# 📚 Exam Paper Predictor

A Django-based web application that predicts frequently repeated exam questions 
using TF-IDF vectorization and cosine similarity.

---

## 🚀 Features
- Semester-wise subject filtering
- Question similarity detection
- PDF generation of predicted paper
- Clean UI using Django templates

---

## 🛠 Tech Stack
- Django
- Pandas
- Scikit-learn
- TF-IDF
- Cosine Similarity
- HTML/CSS

---

## 🧠 How It Works
The system analyzes past exam papers, converts questions into vector format 
using TF-IDF, then groups similar questions using cosine similarity.

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
# 🧠 HealthCoach AI – Stress Prediction & AI Assistant

A full-stack AI-powered web application that predicts stress levels using Machine Learning (XGBoost) and provides intelligent chatbot-based guidance.

---

## 🚀 Features

* 📊 Stress Prediction using ML (XGBoost)
* 📈 Dashboard with analytics (sleep, mood, steps, activity)
* 🤖 AI Chatbot (OpenRouter / HuggingFace API)
* 🔐 User Authentication (Firebase)
* 📉 Graph visualization (Chart.js)
* 🌐 Flask Backend + HTML/CSS/JS Frontend

---

## 📁 Project Structure

```
HealthCoach-AI/
│
├── app.py
├── requirements.txt
├── .env                # API keys (not shared publicly)
├── model.pkl           # Trained ML model
├── hf_client.py        
│
├── static/
│   ├── style.css
│   ├── dashboard.js
│   ├── predictions.js
│   └── firebase-config.js
│
├── templates/
    ├── index.html
    ├── dashboard.html
    └── predictions.html

```

---

## ⚙️ Setup Instructions

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 2️⃣ Create `.env` File

Create a `.env` file in the root directory and add:

```
HF_API_KEY=your_huggingface_key
OPENROUTER_API_KEY=your_openrouter_key
```

⚠️ Without this, AI chatbot will not work.

---

### 3️⃣ Run the Application

```bash
python app.py
```

---

### 4️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🧪 How It Works

### 🔹 Stress Prediction

* Inputs: Sleep, Steps, Mood, Activity, Screen Time
* Model: XGBoost
* Output:

  * Low → 0
  * Stable → 1
  * High → 2

---

### 🔹 Chatbot

* Uses external AI APIs (OpenRouter / HuggingFace)
* Responds to user queries in real-time

---

## ⚠️ Important Notes

* Internet connection is required for AI chatbot
* `.env` file must be configured properly
* Python version recommended: **3.10 / 3.11**
* Ensure `model.pkl` file is present

---

## 🧑‍💻 Tech Stack

* Backend: Flask
* ML Model: XGBoost
* Frontend: HTML, CSS, JavaScript
* Charts: Chart.js
* Auth & DB: Firebase
* APIs: OpenRouter / HuggingFace

---

## 🎯 Presentation Tip

> “This project combines Machine Learning with real-time AI APIs to provide personalized mental health insights and recommendations.”

---

## 📌 Future Improvements

* Personalized stress recommendations
* Voice assistant integration
* Mobile app version
* Advanced ML models (Deep Learning)

---

## 👨‍🎓 Developed By

**Yuvraj Jaiswal**
B.Tech CSE – Data Science

---


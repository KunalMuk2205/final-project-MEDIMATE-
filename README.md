# 🏥 MEDIMATE – AI Powered Healthcare Assistant

MEDIMATE is a **web-based healthcare assistant** that uses **Machine Learning** to analyze user-selected symptoms and predict possible diseases with probability scores.  
The project aims to provide **fast, accessible, and intelligent preliminary health insights**, helping users make informed decisions before consulting medical professionals.

🎥 **Visual Demonstration:**  
👉 [Click here to watch the demo](https://youtu.be/1eKOlDx5W1g)

---

## 🌟 Key Features

### 🔍 Disease Prediction
- Users select symptoms from a predefined list  
- The system predicts possible diseases with **confidence percentages** using a trained ML model  

### ⚡ Fast & Interactive UI
- Smooth animations and modern UI/UX  
- Instant results with loading indicators  

### 🧠 Machine Learning Powered
- Symptom–disease mapping based on medical datasets  
- Probabilistic predictions instead of single rigid outputs  

### 🔐 Privacy Focused
- No personal data storage  
- Works entirely on symptom inputs  

### 📱 Responsive Design
- Works seamlessly across desktop, tablet, and mobile devices  

---

## 🖼️ Project Preview

The platform focuses on:
- Personalized Medicine  
- Medical Chatbot Interaction  
- Medical Forecasting  

> **Note:**  
> *This tool does not replace doctors but helps users understand possible conditions early.*

---

## 🛠️ Tech Stack

### Frontend
- HTML5  
- CSS3 (Modern UI with animations)  
- JavaScript (Vanilla JS)  

### Backend
- Python  
- Flask  
- Machine Learning Model  
- REST API  

### Dataset
- Symptom–Disease dataset (CSV-based medical data)

---

## 📂 Project Structure

```text
final-project-MEDIMATE-
│
├── html.html              # Main frontend file
├── ft.css                 # Styling and UI animations
├── img.jpg                # Hero image
│
├── backend/
│   ├── app.py             # Flask backend
│   ├── model.pkl          # Trained ML model
│   └── requirements.txt
│
├── dataset/
│   └── Testing.csv
│
└── README.md
```

---

### 🚀 How It Works

- User selects symptoms from the dropdown list
- Selected symptoms are sent to the backend via REST API
- Machine Learning model analyzes symptom patterns
- Possible diseases are returned with probability scores
- Results are displayed on the UI with a medical disclaimer

---

### ⚙️ Installation & Setup
Clone the Repository
```bash
git clone https://github.com/KunalMuk2205/final-project-MEDIMATE-.git
cd final-project-MEDIMATE-
```

Backend Setup
```bash
cd backend
pip install -r requirements.txt
python app.py
```
Frontend Setup

Open ```html.html ``` in browser

OR

Use Live Server (VS Code)

📊 Sample Output
Viral Fever – 72%
Dengue – 18%
Malaria – 10%


⚠️ This is not a medical diagnosis.

---

### 📌 Future Enhancements

User login & health history

Doctor recommendation system

AI medical chatbot

Cloud deployment

Mobile app

---

### 🤝 Contributor

Kunal Mukherjee
Computer Science Student

GitHub:
```
 https://github.com/KunalMuk2205
```

---

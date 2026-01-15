🏥 MEDIMATE – AI Powered Healthcare Assistant

MEDIMATE is a web-based healthcare assistant that uses Machine Learning to analyze user-selected symptoms and predict possible diseases with probability scores.
The project aims to provide fast, accessible, and intelligent preliminary health insights, helping users make informed decisions before consulting medical professionals.

Here is a visual demonstration of the project -
CLICK HERE -  https://youtu.be/1eKOlDx5W1g

🌟 Key Features
🔍 Disease Prediction

Users select symptoms from a predefined list.

The system predicts possible diseases with confidence percentages using a trained ML model.

⚡ Fast & Interactive UI

Smooth animations and modern UI/UX.

Instant results with loading indicators.

🧠 Machine Learning Powered

Symptom–disease mapping based on medical datasets.

Probabilistic predictions instead of single rigid outputs.

🔐 Privacy Focused

No personal data storage.

Works entirely on symptom inputs.

📱 Responsive Design

Works seamlessly across desktop, tablet, and mobile devices.

🖼️ Project Preview

The platform focuses on:

Personalized Medicine

Medical Chatbot Interaction

Medical Forecasting

“This tool does not replace doctors but helps users understand possible conditions early.”

🛠️ Tech Stack
Frontend

HTML5

CSS3 (Modern UI with animations)

JavaScript (Vanilla JS)

Font Awesome Icons

Google Fonts (Outfit)

Backend

Python

Flask

Machine Learning Model

REST API

Dataset

Symptom–Disease dataset (CSV based medical data)

📂 Project Structure
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

🚀 How It Works

User selects symptoms from the dropdown list.

Selected symptoms are sent to the backend via REST API.

Machine Learning model analyzes symptom patterns.

Possible diseases are returned with probability scores.

Results are displayed on the UI with a disclaimer.

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/KunalMuk2205/final-project-MEDIMATE-.git
cd final-project-MEDIMATE-

2️⃣ Backend Setup
cd backend
pip install -r requirements.txt
python app.py

3️⃣ Frontend Setup

Open html.html in your browser
OR

Use Live Server (VS Code recommended)

4️⃣ API Endpoint
POST http://127.0.0.1:5000/users


Request Body (JSON):

{
  "symptoms": ["headache", "fever", "fatigue"]
}

📊 Sample Output
1. Viral Fever – 72%
2. Dengue – 18%
3. Malaria – 10%


⚠️ Disclaimer: This is not a medical diagnosis.

📌 Future Enhancements

✅ User login & health history

✅ Doctor recommendation system

✅ Chatbot integration

✅ Cloud deployment

✅ Mobile application version

🎓 Academic Relevance

Final Year Project

Demonstrates:

Machine Learning

REST APIs

Frontend–Backend Integration

Healthcare Applications

🤝 Contributors

Kunal Mukherjee
📌 Computer Science Student
📌 Passionate about AI, ML & Healthcare Tech

# AI-Agri-ChatBot

**AI-Agri-ChatBot** is an AI-powered agricultural assistant built with **Flask**. It helps farmers with crop guidance, pest control, fertilizers, and plant health via chat and leaf image analysis.

---

## 🚀 Key Features

- Interactive chatbot for agricultural queries  
- User profiles with preferred crop, region, language  
- Admin dashboard to manage users, chat history, KB  
- Leaf image analysis (healthy / stressed / diseased)  
- Multilingual support: English, Hindi, Tamil  

---

## 💻 Tech Stack

- **Backend**: Python, Flask, Flask-Login  
- **Database**: SQLite  
- **Frontend**: HTML, CSS, Bootstrap  
- **Image Processing**: Pillow  
- **Deployment**: Docker (optional)  

---
📂 Project Structure</br></br>


AI-Agri-ChatBot/<br>
├── app.py  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;             # Main Flask application<br>
├── database.py   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    # Database models and initialization<br>
├── chatbot_model.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   # Chatbot logic & message processing<br>
├── requirements.txt &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    # Python dependencies<br>
├── Dockerfile  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            # Docker configuration<br>
├── docker-compose.yml &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Docker Compose (optional)<br>
├── templates/  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            # HTML templates<br>
├── static/  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               # CSS, JavaScript, images<br>
├── utils/   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               # Helper utilities (safety, sanitization)<br>
├── .gitignore   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          # Git ignored files<br>
├── README.md   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;        # Project documentation<br>
└── kb.sample.json




> **Note:** `instance/`, `uploads/`, `.db`, and full KB files are excluded for security and cleanliness. Use `kb.sample.json` to create your own knowledge base.

---

## ⚙️ Setup Instructions

### 1. ** Clone the repository:**

&nbsp;&nbsp;&nbsp;&nbsp;git clone https://github.com/DhanasriSiramdasu/AI-Agri-ChatBot.git</br>
    
&nbsp;&nbsp;&nbsp;&nbsp;cd AI-Agri-ChatBot

### 2. **Create a virtual environment (recommended):**

&nbsp;&nbsp;&nbsp;&nbsp;python -m venv venv</br>
&nbsp;&nbsp;&nbsp;&nbsp;<u>Windows</u></br>
&nbsp;&nbsp;&nbsp;&nbsp;venv\Scripts\activate</br>
&nbsp;&nbsp;&nbsp;&nbsp;<u>macOS</u>/Linux</br>
&nbsp;&nbsp;&nbsp;&nbsp;source venv/bin/activate</br>

### 3. **Install dependencies:**

&nbsp;&nbsp;&nbsp;&nbsp;pip install -r requirements.txt

### 4. **Run the app locally:**

&nbsp;&nbsp;&nbsp;&nbsp;python app.py

### 5. **Access in browser:**

&nbsp;&nbsp;&nbsp;&nbsp;http://127.0.0.1:5000

## 🛠 Usage

- Register/Login as a user

- Chat in the chatbot interface

- Admin Dashboard (admin role only):

- View recent users

- Edit or upload knowledge base

- Clear chat history

- Upload leaf images to check plant health

## 📷 Leaf Image Analysis

- The chatbot can analyze leaf images using basic color heuristics:

- Healthy → Mostly green

- Partial damage / early symptoms → Moderate green

- Severe discoloration / disease → Low green

- Optional: Install Pillow (pip install Pillow) for local image processing.

## 📄 Knowledge Base

- Stored in kb.sample.json

- Use JSON or CSV to add new questions/answers

Each entry format:

{
  "keywords": ["fertilizer", "wheat"],</br>
  "answer_en": "Use NPK fertilizer in March...",</br>
  "answer_hi": "मार्च में एनपीके उर्वरक का उपयोग करें...",</br>
  "answer_ta": "மார்ச் மாதத்தில் NPK உரம் பயன்படுத்தவும்..."</br>
}

## 🌐 Future Enhancements

- Integrate ML model for crop disease detection

- Support more languages

- Deploy cloud version for remote access

- Improve chatbot NLP using pre-trained models

## 📌 License

&nbsp; MIT License – free to use and modify for learning or personal projects.

## 👤 Author

Dhanasri Siramdasu

GitHub: https://github.com/DhanasriSiramdasu

LinkedIn: https://www.linkedin.com/in/dhanasrisiramdasu/

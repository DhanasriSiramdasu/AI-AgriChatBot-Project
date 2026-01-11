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
📂 Project Structure</br>
AI-Agri-ChatBot/<br>
├── app.py  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;             # Main Flask application<br>
├── database.py   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    # Database models and initialization<br>
├── chatbot_model.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   # Chatbot logic & message processing<br>
├── requirements.txt &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    # Python dependencies<br>
├── Dockerfile  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            # Docker configuration<br>
├── docker-compose.yml &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Docker Compose (optional)<br>
├── templates/  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            # HTML templates<br>
├── static/  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               # CSS, JavaScript, images<br>
├── utils/   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;               # Helper utilities (safety, sanitization)<br>
├── .gitignore   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          # Git ignored files<br>
├── README.md   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         # Project documentation<br>
└── kb.sample.json




> **Note:** `instance/`, `uploads/`, `.db`, and full KB files are excluded for security and cleanliness. Use `kb.sample.json` to create your own knowledge base.

---

## ⚙️ Setup Instructions

1. **Clone the repository:**

git clone https://github.com/DhanasriSiramdasu/AI-Agri-ChatBot.git
cd AI-Agri-ChatBot

2.Create a virtual environment (recommended):

python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

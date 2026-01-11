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

## 📂 Project Structure
AI-Agri-ChatBot/
├── app.py                 # Main Flask application
├── database.py            # Database models and initialization
├── chatbot_model.py       # Chatbot logic & message processing
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker configuration
├── docker-compose.yml     # Docker Compose (optional)
├── templates/             # HTML templates
├── static/                # CSS, JavaScript, images
├── utils/                 # Helper utilities (safety, sanitization)
├── .gitignore             # Git ignored files
├── README.md              # Project documentation
└── kb.sample.json         # Sample knowledge base



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

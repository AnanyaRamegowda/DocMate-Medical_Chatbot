# 🩺 DocMate – Your AI Doctor, Anytime, Anywhere

DocMate is an AI-powered medical chatbot that provides basic healthcare guidance using both voice and text-based interaction across multiple Indian languages. It supports common medical conditions like fever, asthma, PCOS, anxiety, diabetes, and more – all through a user-friendly and accessible interface.

## 🌟 Features
- 🗣️ Voice & Text Support – Users can speak or type their symptoms  
- 🌐 Multilingual Responses – Supports English, Kannada, Hindi, Tamil, and Telugu  
- 🧠 Predefined Condition Support – Covers 100+ common health concerns  
- 💬 **Command Handling** – Use `/help`, `/info`, or `list` to explore available topics  
- ⚠️ **Safe & Transparent** – Built-in disclaimers to remind users to consult professionals when needed  
- 🔊 **Speech Engine Integration** – Uses Web Speech API for speech-to-text and text-to-speech functionality

## 🧰 Tech Stack Overview
-  Frontend – HTML, CSS, JavaScript (for UI and interaction)  
-  Backend – Python (Flask-ready architecture)  
-  Voice Features – Web Speech API for STT (Speech-to-Text) and TTS (Text-to-Speech)  
-  Bot Logic – Rule-based flows and condition mapping  
-  Multilingual Support – Custom prompts and language mappings  
-  Hosting – Browser-based / local or cloud-hosted deployment

## 📁 Folder Structure
```
DocMate/
├── frontend/                # UI files (HTML, CSS, JS)
├── backend/                 # Flask backend files
├── voice_support/           # Speech input/output scripts
├── multilingual_support/    # Language prompt files
├── bot_logic/               # Condition logic and intent mapping
├── docs/                    # README and disclaimers
```

## 🚀 Getting Started
1. Clone the repository
```bash
git clone https://github.com/yourusername/DocMate.git
```

2. Install backend dependencies
```bash
cd backend
pip install -r requirements.txt
```

3. Open the chatbot
- Open `index.html` in a browser
- Start typing or use voice input
- To run the backend (if needed):
```bash
python app.py
```

## 👥 Target Audience
- Individuals in rural and semi-urban areas 
- Users who prefer regional languages over English  
- Elderly, caregivers, and students seeking basic health guidance

## 🔮 Future Plans
- Add more languages and regional dialects  
- Integrate with Gemini/GPT for richer health conversations  
- Deploy on mobile apps and WhatsApp 
- Support voice call–based interaction for low-literacy users  
- Connect to real-time telemedicine platforms

## 🔗 Live Demo
- Try to go live to explore the DocMate – Your AI Doctor, Anytime, Anywhere 
👉 https://delightful-zuccutto-fdf23f.netlify.app/

## ⭐ GitHub Repository
[https://github.com/yourusername/DocMate](https://github.com/yourusername/DocMate)





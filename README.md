# 🚨 RAKHA X — Intelligent Safety & Support Platform

![Status](https://img.shields.io/badge/Status-Operational-success?style=for-the-badge&logo=activity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**Rakha X** is a full-stack, end-to-end safety ecosystem designed to protect users in high-risk environments.  
Unlike standard CRUD applications, this platform integrates **real-time audio machine learning**, **automated emergency response**, and **AI-driven psychological support** into a single cohesive system.

---

## ⚡ Tech Stack

### Backend & Core
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### AI, ML & Audio Processing
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Librosa](https://img.shields.io/badge/Librosa-Audio_Analysis-blue?style=for-the-badge)
![Vosk](https://img.shields.io/badge/Vosk-Speech_to_Text-lightgrey?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

### APIs & Communication
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

### Frontend & Visualization
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## 🎯 Key Features

### 🎧 Real-Time Audio Threat Detection
A continuous surveillance module that listens for danger signals.
- **YAMNet (TensorFlow):** Detects environmental threats like gunshots, glass breaking, and explosions.
- **Vosk STT:** Analyzes live speech for panic keywords (e.g., *“help”*, *“stop”*).
- **Automated Logic:** Triggers SOS when threat probability crosses a defined threshold.

---

### 🚨 Smart SOS System
Automated crisis-response pipeline.
- **Twilio Integration:** Sends instant WhatsApp alerts to emergency contacts.
- **Alert Payload Includes:**
  - Live location
  - Custom emergency message
  - Audio evidence clip

---

### 🧠 AI Mental Health Assistant
AI-powered emotional and psychological support.
- **Powered by Gemini Pro**
- Provides:
  - Emotional first aid
  - Crisis de-escalation
  - Context-aware safety guidance

---

### 🕹️ Street Safety Simulator
Gamified safety education.
- Interactive **HTML5 Canvas** game
- Teaches identification of:
  - Safe zones
  - Caution zones
  - High-risk areas in urban environments

---

## 📂 Project Structure

```text
rakha-x/
├── models/              # Pre-trained TensorFlow / YAMNet models
├── static/              # CSS, JS, game assets, audio files
├── templates/           # HTML (Jinja2 templates)
├── app.py               # Main Flask application
├── audio_processor.py   # Librosa & Vosk processing logic
├── requirements.txt     # Python dependencies
└── README.md            # Documentation

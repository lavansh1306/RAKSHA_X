# 🚨 RAKHA X — Intelligent Safety & Support Platform

![Status](https://img.shields.io/badge/Status-Operational-success?style=for-the-badge&logo=activity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**Rakha X** is a full-stack, end-to-end safety ecosystem designed to protect users in high-risk environments. Unlike standard CRUD applications, this platform integrates real-time audio machine learning, automated emergency response systems, and AI-driven psychological support into a single, cohesive web application.

---

## ⚡ Tech Stack

### **Backend & Core**
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### **AI, ML & Audio Processing**
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Librosa](https://img.shields.io/badge/Librosa-Audio_Analysis-blue?style=for-the-badge)
![Vosk](https://img.shields.io/badge/Vosk-Speech_to_Text-lightgrey?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

### **APIs & Communication**
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

### **Frontend & Visualization**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## 🎯 Key Features

### 1. 🎧 Real-Time Audio Threat Detection
A sophisticated surveillance module that listens for danger.
* **YAMNet (TensorFlow):** Identifies environmental sounds like **gunshots, glass breaking, and explosions**.
* **Vosk STT:** Analyzes speech for panic keywords (e.g., "Help", "Stop").
* **Logic:** Automatically triggers the SOS protocol if the threat probability threshold is breached.

### 2. 🚨 Smart SOS System
Automated crisis response connecting the user to the outside world.
* **Twilio Integration:** Sends instant WhatsApp alerts to emergency contacts.
* **Data Payload:** Includes precise location data, a customized alert message, and an audio clip of the event for evidence.

### 3. 🧠 AI Mental-Health Assistant
An intelligent companion for post-trauma support or anxiety management.
* **Powered by Gemini Pro:** Offers emotional first-aid, crisis de-escalation, and safety recommendations.
* **Context Aware:** Detects distress levels in user text and responds with empathy and actionable advice.

### 4. 🕹️ Street Safety Simulator
A gamified educational module.
* **Interactive Canvas:** A browser-based game that teaches users how to identify Safe, Caution, and Danger zones in urban environments.

---

## 📂 Project Structure

```text
rakha-x/
├── models/              # Pre-trained TensorFlow/YAMNet models
├── static/              # CSS, JS, Game Assets, Audio files
├── templates/           # HTML Jinja2 Templates
├── app.py               # Main Flask Application (Routes & Logic)
├── audio_processor.py   # Librosa & Vosk helper functions
├── requirements.txt     # Python Dependencies
└── README.md            # Documentation

🚨 RAKHA X — Intelligent Safety & Support Platform

AI-powered street safety, real-time emergency detection, and mental-wellbeing support — built end-to-end using Flask, ML models, and production-ready APIs.

Rakha X is a full-stack, real-world safety system designed to help users stay protected in high-risk situations.
It combines audio threat detection, smart SOS alerts, an interactive safety simulator, and a mental-health AI assistant — all in one seamless web application.

⭐ Why This Project Matters

This isn’t a basic Flask CRUD app. It’s a multi-module safety platform solving real human problems:

Detects gunshots, screams, explosions using ML (YAMNet)

Analyses speech for panic keywords

Triggers automatic WhatsApp SOS alerts

Guides users with AI-powered emotional support

Educates citizens through a street safety simulation game

Built with production practices — modular architecture, real APIs, secure uploads, and model pipelines.

🎯 Key Features
🕹️ 1. Street Safety Simulator

A lightweight game that teaches users how to identify safe, caution, and danger zones.
Built with: HTML Canvas + JS + Flask backend

🎧 2. Real-Time Audio Threat Detection

YAMNet model via TensorFlow

Speech-to-text (Vosk)

Detects emergency audio events

Auto-triggers SOS if threat probability is high

🚨 3. Smart SOS System

WhatsApp alerts via Twilio

Sends location, alert message & audio evidence

One-click emergency button

🧠 4. AI Mental-Health Assistant

Gemini API integration

Crisis detection

Safety recommendations

Emotional first-aid

🏗️ Tech Stack

Backend: Flask (Modular Blueprints)
AI / ML: TensorFlow, TensorFlow Hub, YAMNet, Vosk STT
Frontend: HTML, CSS, JS (Game + UI)
APIs: Twilio WhatsApp, Google Gemini
Audio Processing: Librosa
Database: (Optional future module)

📂 Project Structure
project/
├── app.py
├── templates/
├── static/
├── models/
└── requirements.txt


Clear separation of concerns: UI, ML utilities, and backend routes.

⚙️ Setup
git clone <repo>
cd project
pip install -r requirements.txt
python app.py

Add API Keys

In app.py:

GEMINI_API_KEY = "your_key"
account_sid = "your_sid"
auth_token = "your_token"


Then launch the app at http://localhost:5000.

📌 Highlighted Endpoints
Route	Function
/	Home dashboard
/game	Street safety simulator
/detect	Audio threat detection
/sos	Emergency alert center
/chatbot	AI mental health support
/send_sos/<file>	WhatsApp SOS
🧪 What Makes This Project Recruiter-Ready

Fully original concept, not tutorial-level

Combines AI, real-time processing, web dev, and APIs

Directly solves public safety, a meaningful problem

Shows end-to-end engineering, not isolated skills

Demonstrates ability to integrate multiple technologies into a functional product

Any recruiter reading this sees a candidate who can ideate, design, engineer, integrate, and deploy.
Not just "follow tutorials."

📬 Contact & Support

Feel free to raise issues, suggestions, or collaboration ideas.
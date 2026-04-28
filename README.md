# Brain-Aware-AI-learning-system-

 Feauters offered by our solution 

🧠 Brain-Aware AI – Adapts learning based on mood, performance, and habits
💬 AI Chat Tutor 
📘 Smart Learning 
📝 Adaptive Quiz System 
📅 AI Study Planner 
📊 Progress Tracking 
🌐 Multilingual Support 
📶 Offline Mode 
🎧 Audio Learning Mode
📸 Real-time Doubt Scanner 
🎮 Gamification 
🧘 Mental Wellness Support


Additional Features

🎧 Audio/Podcast Learning Mode – Convert notes into voice-based lessons
📸 AI Doubt Scanner – Solve questions using camera instantly
🧠 Learning Style Detection – Adapts to visual, audio, or reading learners
🎮 Gamification System – XP, badges, leaderboards for motivation
🧩 Micro-learning Mode – Quick 1-minute concept cards
📊 Smart Analytics Dashboard – Shows best study time & weak areas

🧠 How It Works

The system starts by collecting user inputs such as learning goals, study time, and mood (Brain Mode). This data is processed by a Brain-Aware AI engine that adapts the learning experience in real time.
When a user interacts—asking questions, uploading notes, or taking quizzes—the request is sent to the backend, where the MNEE layer analyzes context and selects the appropriate AI model (OpenAI or Gemini). The response is then personalized based on the user’s mood, performance, and learning style.
The platform continuously tracks progress, identifies weak areas, and updates study plans and difficulty levels accordingly. It also supports offline access and multilingual learning for better accessibility.
👉 Overall, the system creates a continuous feedback loop that delivers a personalized, adaptive, and intelligent learning experience.

🔗 THIRD-PARTY APIs & SDKs

🧠 AI & NLP
OpenAI API
Google Gemini API
🎤 Voice Features
Google Speech-to-Text API → Voice input
Google Text-to-Speech API → Audio learning
📸 Camera & Image Processing
Camera API (Flutter) → Capture notes
ML Kit (Google) → Text recognition (OCR)
🔐 Authentication
Firebase Auth SDK
Google Sign-In SDK
📊 Analytics & Tracking
Firebase Analytics
Crashlytics (error tracking)
📶 Offline Support
Hive / SQLite
Cached API responses

🔧 TECH STACK ARCHITECTURE
🎨 Frontend (User Interface)
Flutter → Cross-platform mobile app (Android & iOS)
HTML, CSS, JavaScript → Web dashboard (optional)
UI Design: Material UI / Custom Design System

⚙️ Backend (Server & Logic)
Python (FastAPI / Flask) → API development
Handles:
User authentication
AI request routing
Study planner logic
Quiz engine

🧠 AI Layer (Core Intelligence)
OpenAI API → Explanation, tutoring, chat responses
Google Gemini API → Multimodal AI (text + image understanding)
AI Features:
Brain-mode adaptation
Step-by-step explanations
Multi-language support

🗄️ Database & Storage
Firebase Firestore → Real-time database
Firebase Authentication → Login (Email/Google/Phone)
Firebase Storage → Notes, images
Local Storage (SQLite / Hive) → Offline mode

🛠️ AI Development Tool
Antigravity → Prototype building & AI workflow integration

⚙️ INSTALLATION & SETUP

1️⃣ Frontend Setup (Flutter)
Bash
flutter create brain_ai_app
cd brain_ai_app
flutter pub get
flutter run

2️⃣ Backend Setup (Python)
Bash
pip install fastapi uvicorn openai google-generativeai firebase-admin
uvicorn main:app --reload

3️⃣ Firebase Setup
Go to Firebase Console
Create project
Enable:
Authentication
Firestore Database
Storage
Download google-services.json → Add to Flutter project
4️⃣ Environment Variables
Create .env file:

OPENAI_API_KEY=your_key
GEMINI_API_KEY=your_key
FIREBASE_CREDENTIALS=your_json_path

🔌 MNEE INTEGRATION
Connects mood + learning + AI response
Dynamically selects best AI model
🔹 Components:
Emotion Analyzer → Detects stress/focus
Learning Engine → Tracks performance
Response Adapter → Adjusts explanation style
🔹 Flow:
User Input → MNEE → AI Model Selection → Personalized Output

https://claude.ai/public/artifacts/9455cb1b-23ee-4bfa-8331-a665b735ba5d

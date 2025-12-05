🌾 AI-AgroBot – Intelligent Farming Assistant

A multilingual AI-powered agricultural support system that helps farmers with crop guidance, disease detection, fertilizer suggestions, and real-time farming recommendations.
Built using Flask, NLP, Gemini API, Image Analysis, and a Knowledge Base.

📌 Table of Contents

About the Project

Features

Tech Stack

System Architecture

How the AI Works

Installation

Project Structure

Future Enhancements

Contributors

License

📖 About the Project

AI-AgroBot is a smart agriculture assistant designed to help farmers get instant answers to crop-related issues.
Farmers can chat in their own language, upload crop images for disease detection, and receive region-based advice.
The system also includes an Admin Panel to manage the knowledge base and users.

✨ Features
✔️ Multilingual Chatbot

Supports English, Hindi, and Tamil using NLP + translation.

✔️ AI Image Analysis

Upload crop images → Gemini Vision API → disease detection + suggestions.

✔️ Knowledge Base (Offline Mode)

If stored answers exist → bot replies instantly without internet.

✔️ Gemini API Fallback

When KB has no answer → Gemini provides intelligent, accurate responses.

✔️ User Authentication

Register, login, manage profile, track chat history.

✔️ Admin Dashboard

Manage users, update Knowledge Base, upload CSV, monitor chat history.

✔️ Secure & Modern UI

Clean interface with JavaScript-based chat and alerts.

🧠 Tech Stack
Frontend

HTML5, CSS3, JavaScript

Responsive UI components

Dynamic chat animations

Backend

Python Flask

Flask-Login

Flask-SQLAlchemy

AI / ML / NLP

Gemini API (Text + Vision)

langdetect → language detection

googletrans/deep-translator → translation

Pillow (PIL) → image preprocessing

Keyword-based Knowledge Base (offline AI)

Database

SQLite

CSV-based Knowledge Base

🏗️ System Architecture
User Interface (HTML/CSS/JS)
        ↓
Flask Backend (API Endpoints)
        ↓
NLP Layer (Language Detect + Translation)
        ↓
Knowledge Base (Offline Answer)
        ↓      (If no answer)
Gemini API (Online AI Response)
        ↓
Database (Users, Chats, KB)


Image flow:

User uploads image → PIL preprocess → Gemini Vision → Disease detection → Response

🤖 How the AI Works

User asks a question

Detect language using langdetect

Translate to English using Google Translate

Search Knowledge Base (offline)

If not found → call Gemini AI

Translate answer back to user's language

Save chat to database and display result

Image analysis flow:

User uploads crop image

PIL resizes & processes image

Gemini Vision analyzes disease

Returns health status + suggestions

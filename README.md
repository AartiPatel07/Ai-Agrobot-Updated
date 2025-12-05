🌾 AI-AgroBot – Intelligent Farming Assistant

AI-AgroBot is a multilingual, AI-powered agriculture assistant that helps farmers with crop guidance, disease detection, fertilizer recommendations, and smart farming decisions.
It uses Flask, NLP, Knowledge Base Search, and Google Gemini (Text + Vision APIs) to deliver accurate and personalized support.

⭐ Features Overview

💬 Multilingual Chatbot (English, Hindi, Tamil)

📚 Offline Knowledge Base for instant responses

🤖 Gemini Text API fallback for advanced answers

🌱 Image-based Disease Detection (Gemini Vision API)

👤 User login, profile & chat history

🛠️ Admin Dashboard (KB edit, CSV upload, user management)

🔐 Role-based authentication

🚀 Clean UI with real-time chat



Farmers require quick answers for pest control, nutrient deficiency, irrigation planning, and crop selection.
AI-AgroBot solves this problem through:

Smart multilingual chat

Real-time plant disease detection

Personalized farming recommendations

Region- and crop-based suggestions

Admin tools for knowledge management

This system aims to make agricultural knowledge accessible, accurate, and available 24/7.

✨ Features
💬 1. Multilingual Chatbot

Detects language using NLP (langdetect)

Translates using googletrans/deep-translator

Replies in English, Hindi, or Tamil automatically

🌱 2. Image Analysis

Image preprocessing using Pillow (PIL)

Real disease/pest analysis using Gemini Vision API

Returns health status + treatment steps

📚 3. Offline Knowledge Base (KB)

Fast keyword-based matching

Does NOT require internet

Admin can update JSON/CSV

🤖 4. Gemini Text API Fallback

If offline KB has no answer →
Gemini Text API generates an intelligent, contextual, agriculture-specific answer.

👤 5. User System

Registration & login

Profile details (crop, region, language)

Chat history stored in DB

🛠️ 6. Admin Dashboard

View & delete users

Clear chat history

Edit Knowledge Base

Upload CSV data

🧠 Tech Stack
Frontend

HTML, CSS, JavaScript

Responsive chat layout

Backend

Python Flask

Flask-Login

Flask-SQLAlchemy

Werkzeug security

AI / NLP

Gemini Text API → Q&A

Gemini Vision API → Image diagnosis

langdetect → Language identification

deep-translator/googletrans → Translation

Pillow (PIL) → Image preprocessing

Custom keyword matching KB engine

Database

SQLite

JSON Knowledge Base

CSV import support

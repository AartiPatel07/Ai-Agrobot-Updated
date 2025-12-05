# AI-AgroBot – Intelligent Farming Assistant

AI-AgroBot is a multilingual, AI-powered agriculture assistant that helps farmers with crop guidance, disease detection, fertilizer recommendations, and smart farming decisions.
It uses Flask, NLP, Knowledge Base Search, and Google Gemini (Text + Vision APIs) to deliver accurate and personalized support.

# Features Overview

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

# Features
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

# Tech Stack
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
# Outputs 

<img width="1913" height="964" alt="Screenshot 2025-12-05 132436" src="https://github.com/user-attachments/assets/f83450e3-4183-4d4e-94ee-87b6d471bc68" />

----

<img width="1909" height="976" alt="Screenshot 2025-12-05 132453" src="https://github.com/user-attachments/assets/cba40ae5-0390-4fe3-a632-8d6e76e62be3" />

----

<img width="1902" height="978" alt="Screenshot 2025-12-05 132508" src="https://github.com/user-attachments/assets/79633850-016e-4a1d-89ab-9774004d3b18" />

----

<img width="1909" height="985" alt="Screenshot 2025-12-05 132622" src="https://github.com/user-attachments/assets/cbaacb63-85ed-4576-89d8-7929a86ad968" />

----
<img width="1900" height="1007" alt="Screenshot 2025-12-05 132640" src="https://github.com/user-attachments/assets/e0d2a769-32d5-463f-9ced-934daddfd0ae" />

----




<img width="1910" height="971" alt="Screenshot 2025-12-05 132655" src="https://github.com/user-attachments/assets/fb144999-abd8-4d64-a245-768045debea0" />

----

<img width="1919" height="990" alt="Screenshot 2025-12-05 132709" src="https://github.com/user-attachments/assets/690b4f7d-999d-48b0-909c-ad6de81a3477" />

----

<img width="1911" height="975" alt="Screenshot 2025-12-05 132720" src="https://github.com/user-attachments/assets/b6e08cd9-6840-4c4a-a4b4-59b0f07f06ea" />


----

<img width="1914" height="976" alt="Screenshot 2025-12-05 132732" src="https://github.com/user-attachments/assets/513111ac-9868-452c-89e3-57e4be25f62a" />


----


<img width="1916" height="961" alt="Screenshot 2025-12-05 132754" src="https://github.com/user-attachments/assets/2c3b5f2c-13db-4cb7-91ae-336fcd9e70a7" />


----
<img width="1893" height="964" alt="Screenshot 2025-12-05 132817" src="https://github.com/user-attachments/assets/ca3e7ed4-ca09-4905-8774-7824c0b4d064" />
----


<img width="1908" height="967" alt="Screenshot 2025-12-05 132833" src="https://github.com/user-attachments/assets/82f92348-217b-4d0d-a1fd-5f300e9fc3b4" />

----





<img width="1919" height="968" alt="Screenshot 2025-12-05 133055" src="https://github.com/user-attachments/assets/a653e9a0-72ed-4287-ad49-154622ae8c1b" />

----


<img width="1910" height="971" alt="Screenshot 2025-12-05 133220" src="https://github.com/user-attachments/assets/f4692093-c82d-485f-b92c-c9d93b852c70" />

----

<img width="1916" height="980" alt="Screenshot 2025-12-05 133247" src="https://github.com/user-attachments/assets/e0c83d31-1128-4a02-8de6-d38d1e3816d5" />

----




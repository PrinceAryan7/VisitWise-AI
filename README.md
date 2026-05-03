<<<<<<< HEAD
# VisitWise AI - Complete Setup Guide

## Project Structure
```
visitwise-ai/
├── backend/          → Node.js + Express API
├── frontend/         → React.js UI
├── prediction/       → Python FastAPI ML Service
└── README.md
```

## Prerequisites (Install karo pehle)
1. Node.js v18+ → https://nodejs.org
2. Python 3.10+ → https://python.org
3. PostgreSQL 15 → https://postgresql.org/download
4. Git → https://git-scm.com

## Quick Start (3 terminals mein)

### Terminal 1 - Backend
```bash
cd backend
npm install
npm run dev
```

### Terminal 2 - Prediction Service
```bash
cd prediction
pip install -r requirements.txt
uvicorn main:app --reload --port 8001
```

### Terminal 3 - Frontend
```bash
cd frontend
npm install
npm start
```

App opens at: http://localhost:3000
=======
🚀 VisitWise AI

Smart Crowd & Cost Prediction Platform

VisitWise AI helps people plan smarter visits to malls, cafes, gyms, parks, tourist spots, and more — by predicting crowd levels, wait times, best visiting hours, and estimated costs before you even leave home.


📌 Problem

People often face:

⏳ Wasted Time – Reaching crowded places with long queues

💸 Unexpected Costs – No idea about spending beforehand

😤 No Timing Insights – Uncertainty about peak/off-peak hours

📍 Lack of Data – No crowd info for local or tourist places


💡 Solution

VisitWise AI solves this using AI-powered predictions:

📍 Detects nearby places using GPS

🔍 Smart search for any location (powered by OpenStreetMap)


🤖 Predicts:

Crowd level

Wait time

Best time to visit

Estimated cost

📊 Provides analytics for smarter planning


⚙️ Key Features

📍 Location Detection – Auto-detect nearby places

🏙️ Manual Search – Search any city/place

🏛️ Tourist Support – Works for monuments, parks, zoos, etc.

🤖 AI Confidence Rating – Accuracy indicator

🟢 Open/Closed Status – Real-time availability

➕ Add Custom Places – User-generated locations

📊 Analytics Dashboard – Crowd insights & trends


🧠 How It Works

User searches or detects location

System identifies place category

Applies time-based crowd pattern

Adds modifiers (weekend, popularity, etc.)

Outputs predictions (crowd, wait time, cost)


🏗️ Architecture

3-Tier System:

Frontend: React.js (Dashboard, UI, GPS, Analytics)

Backend: Node.js + Express (API, Auth, Database)

AI Engine: Python FastAPI (Prediction logic)


🛠️ Tech Stack

Frontend

React.js

Axios, React Router

Backend

Node.js + Express

JWT Authentication

Database

PostgreSQL

AI Engine

Python + FastAPI

Maps & Search

OpenStreetMap + Nominatim (100% Free)


📊 Crowd Prediction Logic

Based on real-world time patterns (168 data points/category)

Categories include:

Mall (weekend peaks)

Cafe (morning/evening rush)

Gym (morning peaks)

Tourist places (weekend evenings)


🌟 Highlights

✅ 100% Free (No paid APIs)

⚡ Scalable with caching

📈 Accurate pattern-based predictions

🌍 Supports multiple place categories


🔮 Future Scope

Google Maps “Popular Times” integration

📱 Mobile App (React Native)

⭐ User reviews & ratings

🔔 Alerts for low crowd times


🙌 Conclusion

VisitWise AI makes travel and daily outings smarter by giving users data-driven insights — saving time, money, and effort.


📎 Built With

React.js • Node.js • Python FastAPI • PostgreSQL • OpenStreetMap
>>>>>>> ba33f8d52dcb6d0eaaf4a25db02b65ee4d71f307

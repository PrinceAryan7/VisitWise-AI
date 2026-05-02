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

# Test Project

This repository provides a minimal FastAPI backend and a React frontend.

## Prerequisites
- Python 3.8+
- Node.js 18+

## Backend Setup
```
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

The API exposes `GET /api/health` for a basic health check.

## Frontend Setup
```
cd frontend
npm install
npm run dev
```

The frontend will fetch from `/api/health` and display the status.

## Running Tests
```
cd backend
pytest
```

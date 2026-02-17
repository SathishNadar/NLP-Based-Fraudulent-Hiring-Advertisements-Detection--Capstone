# Fake Job Posting Detection - Case Study Project

## Prerequisites
- Python 3.8+
- Node.js & npm

## Quick Start (Mac/Linux)

We have included a script to start everything at once. Run:
```bash
./start.sh
```

---

## Manual Startup

### 1. Backend (Flask API)
Open a terminal and run:

```bash
cd FakeJobDetection
# Create Virtual Environment
python3 -m venv venv
source venv/bin/activate

# Install Dependencies
pip install -r backend/requirements.txt

# Train Model (First time only)
python3 backend/train_model.py

# Run Server
python3 backend/app.py
```
*Server will start at http://127.0.0.1:5000*

### 2. Frontend (React + Tailwind)
Open a **new** terminal tab and run:

```bash
cd FakeJobDetection/frontend
npm install
npm run dev
```
*App will open at http://localhost:5173*

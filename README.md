# NETRA-AI: National Enhanced Tracking and Real-time Analytics

NETRA-AI is a high-performance, AI-driven surveillance system designed for real-time suspect triangulation. This dashboard is tailored for the Delhi Police "Safe City" vision, providing a unified operational picture for tracking targets across city-wide camera grids.

## 🏛 Vision and Mission

- **Shanti (Peace):** Preventing crime through AI-enabled behavioral analysis.  
- **Seva (Service):** Rapid response through integrated PCR unit dispatch.  
- **Nyaya (Justice):** Maintaining tamper-proof audit logs for investigative integrity

## 🛠 Tech Stack

Frontend: React 18, TypeScript, Tailwind CSS.
Backend: FastAPI (Python), WebSockets for real-time data streaming
Logic: SVG-based trajectory mapping and AI confidence scoring

## 📂 Project Structure

```
NETRA-AI
├── backend
│   ├── app
│   │   ├── api (alerts.py, incidents.py)
│   │   ├── data (mock_alerts.json, mock_tracking.json)
│   │   ├── models (alert.py, tracking.py)
│   │   └── ws (live_tracking.py)
│   └── main.py
│
├── frontend
│   ├── src
│   │   ├── components (UI Blocks)
│   │   ├── hooks (WebSocket Logic)
│   │   ├── pages (App.tsx Dashboard)
│   │   └── styles (Tailwind CSS)
│   └── package.json
│
└── README.md
```
## 🚀 Installation Guide

## 1. Backend Setup (FastAPI)

Navigate to the backend folder:

```bash
cd backend
```
Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

- **Mac/Linux:** `source .venv/bin/activate`
- **Windows:** `.venv\Scripts\activate`

Install requirements:

```bash
pip install -r requirements.txt
```

Run the server:

```bash
python main.py
```


# -edgeiq-or-edgeiq-ml-sports-analytics-etc.-
Real-time sports analytics platform that tracks player performance, generates prop-style insights, and simulates parlay outcomes using live game data and basic statistical
# EdgeIQ

EdgeIQ is a sports analytics platform that pulls live game data, tracks player performance, and runs simple outcome simulations for player props and matchups.

It’s built as a way to explore sports data in a more structured, visual way instead of just box scores or highlights.

---

## What it does

- Pulls live or recent game data from sports APIs
- Displays player stats in a clean dashboard
- Runs basic simulations for player performance ranges
- Shows hit probability estimates for simple prop-style outcomes
- Lets you compare players side by side

---

## Why I built it

Most sports data is either:
- too scattered (box scores, articles, highlights)
- or too locked behind betting apps

I wanted a simple system where I could take raw stats and turn them into something visual and interactive.

---

## Tech Stack

- Python (data + backend logic)
- Flask (API layer)
- JavaScript / React (frontend)
- Recharts (visualization)
- REST APIs (sports data sources)

---

## Features (current state)

- Live player stats feed
- Basic projection/simulation model
- Player comparison view
- Simple dashboard UI

---

## How to run

### Backend
```bash
cd backend
pip install -r requirements.txt
python app.py

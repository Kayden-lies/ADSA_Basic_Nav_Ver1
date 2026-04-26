# Campus Navigation System

A graph-based navigation system designed to simulate real-world route planning within a campus environment.

## 🚀 Features

- Graph-based campus representation
- Weighted edges using real geographic distances
- Multiple route generation (k-shortest paths)
- Duplicate and loop filtering
- Interactive web-based visualization
- Route simulation with animation

---

## 🧠 Tech Stack

- Backend: FastAPI, NetworkX
- Frontend: Leaflet.js
- Distance Calculation: Geopy

---

## 📂 Project Structure

```
backend/
  main.py
  requirements.txt

frontend/
  index.html
```

---

## ▶️ Running Locally

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

API will be available at:
http://127.0.0.1:8000

---

### Frontend

```bash
cd frontend
python -m http.server 5500
```

Open:
http://localhost:5500

---

## 🌐 Deployment

- Backend: Render (Web Service)
- Frontend: Render (Static Site)

---

## 📌 Future Improvements

- Real-time user tracking
- Turn-by-turn navigation
- Mobile app (Expo / React Native)
- AR-based navigation

---

## 📖 Concept

The campus is modeled as a graph where:
- Nodes represent locations
- Edges represent walkable paths
- Edge weights represent real-world distances

Routing algorithms are used to generate optimal and alternative paths.

---

## 👨‍💻 Author

Developed as part of a campus navigation and simulation project.

# 🚀 FastAPI Learning Project

This repository contains my personal learning project using **FastAPI**, created to understand and practice building high-performance APIs in Python.  
It’s a sandbox for experimenting with routing, request/response handling, query parameters, path parameters, and integration with external libraries.

---

## 📦 Tech Stack
- **Python** 3.11+
- **FastAPI** — modern web framework for building APIs
- **Uvicorn** — ASGI server for running FastAPI
- **Pydantic** — data validation and serialization
- **Requests** — for making HTTP requests
- **Geopy** — for geolocation and distance calculations
- **Polyline** — for working with encoded route coordinates

---

## 📂 Project Structure
```
project/
│── app/
│   ├── main.py         # Entry point of the application
│   ├── routes/         # API route definitions
│   ├── models/         # Pydantic models for requests/responses
│   ├── services/       # Business logic
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```

---

## ▶️ Installation & Running
1. **Clone the repository**
   ```bash
   git clone https://github.com/username/fastapi-learning.git
   cd fastapi-learning
   ```
2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the server**
   ```bash
   uvicorn app.main:app --reload
   ```
5. **Open in browser**
   - Swagger UI: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
   - ReDoc: [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

---

## 📌 Example Endpoints
- `GET /ping` — Health check (`{"message": "pong"}`)
- `GET /items/{id}` — Get item by ID
- `GET /search?q=keyword` — Search items
- `POST /items` — Create a new item
- `PUT /items/{id}` — Update item
- `DELETE /items/{id}` — Delete item

---

## 🎯 Purpose
This project is **for learning purposes only**.  
It’s my personal playground to:
- Learn FastAPI fundamentals
- Experiment with routes & parameters
- Work with geolocation and external APIs
- Build small API prototypes quickly

---

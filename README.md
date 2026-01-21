# Career-Mitra Full Stack Assignment

## Overview
This is a simple full stack web application developed as part of the Career-Mitra assignment.
The goal of this project is to demonstrate backend API development, frontend integration,
and basic database handling.

The application allows users to add student assessment details and view them in a dashboard.

---

## Features
- Add student details (Name, Class, Interests, Aptitude Score)
- View student data in tabular format
- REST API using FastAPI
- React frontend with Axios integration
- SQLite database for persistence

---

## Tech Stack

### Frontend
- React.js
- Axios
- CSS

### Backend
- Python
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

---

## Setup Instructions

### Backend Setup
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload

### frontend setup
cd frontend
npm install
npm start

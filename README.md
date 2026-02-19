🎬 Django REST Backend API (IMDB Clone)

This repository contains a RESTful backend API built using Django REST Framework as part of my backend development learning project.

🧠 About

This project is a backend API that implements the core functionality of an IMDB-like application.
It includes user authentication, movie/watchlist management, pagination, filtering, and more.

🚀 Features

🔐 JWT Authentication (Access + Refresh tokens)

📋 CRUD APIs for watchlist and movie data

🔎 Filtering, Searching & Ordering

🧩 Pagination support

🛠 Tested API endpoints using Postman

📦 Requirements included in requirements.txt

📂 Tech Stack
Technology	Version
Python	3.11+
Django	3.x+
Django REST Framework	3.x+
Simple JWT	Latest
SQLite / PostgreSQL (Future upgrade)	—

🧩 Project Structure
backend-project/
├── manage.py
├── watchlist_app/
├── watchmate/
├── user_app/
├── requirements.txt
├── .gitignore
└── README.md

📌 API Endpoints (Examples)
POST /api/register/ — Register new user
POST /api/token/ — Get JWT access & refresh
GET /api/watchlist/ — List movies
POST /api/watchlist/ — Add new movie

🛠 Future Improvements

✔ Convert DB to PostgreSQL
✔ Add Docker support
✔ Add deployment (Railway/Render)
✔ Add automated testing (pytest)
✔ Add API documentation

Email: manishub75@gmail.com
GitHub: https://github.com/manishub45


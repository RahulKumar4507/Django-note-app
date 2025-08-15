# 📝 Django Notes App

A simple Django project to create and manage notes.  
This project is Docker-ready and easy to run without extra setup.

---

## 📦 Project Structure
```
├── api/                 # API related code
├── mynotes/             # Django app (main logic)
├── notesapp/            # Project settings and configs
├── nginx/               # Nginx config for deployment
├── requirements.txt     # Python dependencies
├── docker-compose.yml   # Run project using Docker
├── Dockerfile           # Docker image build
├── manage.py            # Django management commands
├── .env                 # Environment variables (already included)
├── Procfile             # For platforms like Heroku
└── README.md            # Project instructions
```

---

## 🚀 How to Run the Project

### Option 1: Run with Docker (Recommended ✅)
1. Clone this repository:
   ```bash
   git clone https://github.com/RahulKumar4507/Django-note-app.git
   cd django-notes-app
   ```

2. Build and start the containers:
   ```bash
   docker-compose up --build
   ```

3. Open your browser and visit:
   ```
   http://serverpublicIP:80/
   ```

---

## ⚙️ Environment Variables
The `.env` file is already included in the repo, so you don’t need to create it manually.  
It contains project settings (no secrets exposed).

---

## 🌟 Features
- Create, edit, and delete notes
- Beginner-friendly setup
- Docker & non-Docker support
- Ready for deployment with Nginx

---

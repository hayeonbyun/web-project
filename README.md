# web-project

# Django Portfolio Project

Live Demo 👉 [https://web-project-6ndx.onrender.com](https://web-project-6ndx.onrender.com)

---

## About The Project

This project is a public web application built with Django, demonstrating CRUD functionality and deployment workflow.  
It includes:

- 📝 **To-Do List** (Add / Update / Delete tasks)  
- 📰 **Blog** (Create / Read / Update / Delete posts)  
- 🌍 Fully deployed on **Render**  
- 🗄 SQLite database for lightweight storage  
- 🧩 Django Template system with reusable `base.html`  

Focus: Understanding Django project structure, routing, templates, models, and deployment.

---

## Tech Stack

- Python 3  
- Django 6  
- HTML / CSS / Bootstrap 5  
- SQLite  
- Gunicorn  
- Render (Deployment)

---

## Local Installation

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Open http://127.0.0.1:8000/ to view the project locally.

🔹 Replace YOUR_USERNAME / YOUR_REPO with your GitHub account and repository name.



🌍 Deployment

Deployed using Render.

Build Command (executed automatically on Render):

pip install -r requirements.txt
python manage.py migrate

Start Command:

gunicorn todo_project.wsgi

After deployment, the Render URL (Live Demo above) is publicly accessible.
Both To-Do and Blog features are fully functional.

📸 Screenshots
To-Do Page

Blog Page

(Make sure screenshots exist in screenshots/ folder with exact names above)

🎯 What I Learned

Django project structure & URL routing

Template inheritance (base.html)

CRUD operations with forms & models

Handling authentication & optional login

Deployment workflow using Render

Debugging ALLOWED_HOSTS, Gunicorn, and AppRegistry issues

💻 Demo Access

No login required for demo (public)

For admin panel: create superuser locally using python manage.py createsuperuser

Demo account can be used to test app if needed (optional)

📬 Contact

GitHub: https://github.com/hayeonbyun

Email: hbyunart@gmail.com
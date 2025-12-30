# Django Blog Website (Practice Project)

## 📌 Overview
This is a Django-based blog website built for **learning and practice purposes**.  
The project focuses on understanding how a real-world blogging system works using Django, including posts, categories, comments, authentication, and admin management.

The main goal of this project is to improve backend development skills and gain hands-on experience with Django features commonly used in production applications.

---

## 🎯 What I Learned
- Django project structure and app-based architecture  
- Models, relationships, and database migrations  
- Django templates and dynamic content rendering  
- Forms handling and user input  
- Authentication and authorization basics  
- Admin panel customization  
- Media file (image) upload and static files handling  
- URL routing and slug-based pages  
- Debugging and fixing common Django errors  

---

## ✨ Features
- Blog posts with categories  
- Featured and recent posts section  
- Comment system (authenticated users only)  
- Django admin panel for content management  
- Image upload support for blog posts  
- Category-wise blog listing  
- Responsive UI using Bootstrap  

---

## 🛠️ Technologies Used
- **Python 3**
- **Django**
- **HTML, CSS, Bootstrap**
- **SQLite** (development database)
- **Git & GitHub**

---

## 🎓 Project Purpose
This project is created **only for educational and practice purposes**.  
It is not intended for commercial use.  
The focus is on learning Django by building a functional blog application step by step.

---

## 🚀 How to Run the Project

```bash
# create virtual environment
python -m venv venv

# activate virtual environment
venv\Scripts\activate

# install dependencies
pip install -r requirements.txt

# apply migrations
python manage.py makemigrations
python manage.py migrate

# run server
python manage.py runserver

Open your browser and visit:
http://127.0.0.1:8000

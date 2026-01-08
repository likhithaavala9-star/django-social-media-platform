# Django Social Media Platform (Core Features)

A Django-based social media platform implementing core social networking features such as user authentication, posts, comments, and likes.

---

## Features

### 👤 User & Authentication
- User registration and login
- Logout functionality
- Django built-in authentication system
- Superuser / Admin panel support

### 📝 Posts
- Create posts
- View all posts on the home feed
- Display post author and content
- Posts ordered by latest first

### 💬 Comments
- Add comments to posts
- Display comments under each post
- Comments linked to users and posts

### ❤️ Likes
- Like and unlike posts
- Prevent duplicate likes
- Like count displayed for each post

---

## 📌 Project Scope

This project focuses on implementing core social media functionality using Django.  
It is intended for learning and demonstration purposes.

---

## ✅ Implemented Features
- User authentication
- Posts
- Comments
- Likes

---

## Future Enhancements (Not Implemented)
- User following / friend system
- Notifications
- Real-time features (WebSockets)
- REST API (Django REST Framework)
- Deployment

---

## 🛠️ Tech Stack
- **Backend:** Django
- **Authentication:** Django Auth
- **Database:** SQLite
- **Frontend:** HTML, CSS, Bootstrap
- **File Handling:** Django Media Framework

---

## 📂 Project Structure

django-social-media-platform/
│

├── accounts/ # User authentication & profiles

├── posts/ # Posts, comments, likes

├── templates/ # HTML templates

├── static/ # CSS and static files

├── media/ # Uploaded media files

├── social_media/ # Main Django project settings

│
├── db.sqlite3

├── manage.py

└── requirements.txt

yaml
Copy code

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/likhithaavala9-star/django-social-media-platform.git
cd django-social-media-platform

shell
Copy code

### 2️⃣ Create Virtual Environment
python -m venv venv


### 3️⃣ Activate Virtual Environment (Windows)
venv\Scripts\activate


### 4️⃣ Install Dependencies
pip install -r requirements.txt


### 5️⃣ Apply Migrations
python manage.py makemigrations

python manage.py migrate


### 6️⃣ Create Superuser (Optional)
python manage.py createsuperuser


### 7️⃣ Run the Server
python manage.py runserver


### 8️⃣ Open in Browser
http://127.0.0.1:8000/
http://127.0.0.1.8000/admin/

---

## 📜 License
This project is licensed under the MIT License.


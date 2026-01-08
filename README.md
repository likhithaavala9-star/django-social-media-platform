Django Social Media Platform (Core Features)

A Django-based social media platform implementing core social networking features such as user authentication, posts, comments, and likes.

Features
👤 User & Authentication

User registration and login

Logout functionality

Django built-in authentication system

Superuser / Admin panel support

📝 Posts

Create posts

View all posts on the home feed

Display post author and content

Posts ordered by latest first

💬 Comments

Add comments to posts

Display comments under each post

Comments linked to users and posts

❤️ Likes

Like and unlike posts

Prevent duplicate likes

Like count displayed for each post

📌 Project Scope

This project focuses on implementing core social media functionality using Django.
It is intended for learning and demonstration purposes.

✅ Implemented Features

User authentication

Posts

Comments

Likes

🔮 Future Enhancements (Not Implemented)

User following / friend system

Notifications

Real-time features (WebSockets)

REST API (Django REST Framework)

Deployment (AWS / Heroku / Render)

🛠️ Tech Stack

Backend: Django

Authentication: Django Auth

Database: SQLite

Frontend: HTML, CSS, Bootstrap

File Handling: Django Media Framework

📂 Project Structure
django-social-media-platform/
│
├── accounts/          # User authentication & profiles
├── posts/             # Posts, comments, likes
├── templates/         # HTML templates
├── static/            # CSS and static files
├── media/             # Uploaded media files
├── social_media/      # Main Django project settings
│
├── db.sqlite3
├── manage.py
└── requirements.txt

🔧 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/django-social-media-platform.git
cd django-social-media-platform

2️⃣ Create a Virtual Environment
python -m venv venv

3️⃣ Activate the Virtual Environment

Windows

venv\Scripts\activate

Install Dependencies
pip install -r requirements.txt

Apply Migrations
python manage.py makemigrations
python manage.py migrate

Create Superuser (Optional)
python manage.py createsuperuser

Run the Server
python manage.py runserver

Open in Browser
http://127.0.0.1:8000/

📸 Screenshots

Screenshots demonstrating posts, comments, and likes are included in the repository.

📜 License

This project is licensed under the MIT License.

# django-social-media-platform
A complete social media platform built with Django featuring user profiles, posts, comments, and likes. Includes authentication, media uploads, and a responsive UI.
## 🚀 Features

### 👤 User & Profile

-   User registration & login
-   Automatically created user profiles
-   Profile picture upload
-   Bio section

### 📝 Posts

-   Create, edit, and delete posts
-   Attach images to posts
-   View individual post pages
-   Post timestamps

### 💬 Comments

-   Add comments to posts
-   Display comments under posts
-   Comment count

### ❤️ Likes

-   Like/unlike system
-   Prevent duplicate likes
-   Like counter for each post

## 🛠️ Tech Stack

  Component     Technology
  ------------- -----------------------
  Backend       Django
  Auth          Django Auth System
  Database      SQLite (default)
  Frontend      HTML, CSS, Bootstrap
  File Upload   Django Media Handling

## 📂 Project Structure

    django-social-media-platform/
    │
    ├── accounts/          # Profile, Register, Login
    ├── posts/             # Posts, Comments, Likes
    ├── templates/         # HTML templates
    ├── media/             # Uploaded images
    ├── project/           # Main Django config
    │
    ├── manage.py
    └── requirements.txt

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/<your-username>/django-social-media-platform.git
cd django-social-media-platform
```

### 2️⃣ Create Virtual Environment

``` bash
python -m venv venv
```

### 3️⃣ Activate Virtual Environment

Windows:

``` bash
venv\Scripts\activate
```

### 4️⃣ Install Dependencies

``` bash
pip install -r requirements.txt
```

### 5️⃣ Apply Migrations

``` bash
python manage.py migrate
```

### 6️⃣ Run Server

``` bash
python manage.py runserver
```

### 7️⃣ Open in Browser

    http://127.0.0.1:8000/

## 📜 License

This project is licensed under the **MIT License**.

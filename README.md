
# 🧠 inevitablegs-django-learning

This is a simple Django project designed for learning purposes. It features user authentication (signup, login, logout), a profile management system, and basic template rendering using Django's templating system.

---

## 📁 Project Structure

```
inevitablegs-django-learning/
├── db.sqlite3
├── manage.py
├── accounts/
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   ├── apps.py
│   ├── tests.py
│   └── migrations/
├── Basics/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   ├── asgi.py
│   └── wsgi.py
└── templates/
    ├── home.html
    ├── login.html
    └── signup.html
```

---

## 🚀 Features

- User Signup & Login
- Logout functionality
- Profile with:
  - Bio
  - Location
  - Birth date
- Home page for authenticated users
- Message-based feedback for errors and updates

---

## 🛠️ How to Run

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/inevitablegs-django-learning.git
cd inevitablegs-django-learning
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Django

```bash
pip install django
```

### 4. Run Migrations

```bash
python manage.py migrate
```

### 5. Start the Development Server

```bash
python manage.py runserver
```

---

## 🌐 Routes

| URL Path     | View            | Description                  |
|--------------|------------------|------------------------------|
| `/`          | `home`          | Home page after login        |
| `/login/`    | `login_view`    | Login page                   |
| `/signup/`   | `signup_view`   | User registration            |
| `/logout/`   | `logout_view`   | Logout user                  |
| `/profile/`  | `profile_view`  | View and update user profile |

---

## ✍️ Author

- **GS (Ganesh Sonawane)** – Django Learner & Creator

---

## 📜 License

This project is for educational use. Feel free to use and modify.

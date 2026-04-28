# MyApp — Django Authentication Project

A beginner-friendly Django web app with Login, Register, Dashboard, and Logout.

## Setup & Run

```bash
# 1. Install Django
pip install -r requirements.txt

# 2. Apply database migrations
python manage.py migrate

# 3. (Optional) Create admin superuser
python manage.py createsuperuser

# 4. Start the server
python manage.py runserver
```

Then open: http://127.0.0.1:8000

## URL Routes

| URL           | Page       |
|---------------|------------|
| /             | Home (auto-redirect) |
| /login/       | Login Page |
| /register/    | Register Page |
| /dashboard/   | Dashboard (login required) |
| /logout/      | Logout |
| /admin/       | Django Admin |

## Project Structure

```
myproject/
├── manage.py
├── requirements.txt
├── README.md
├── myproject/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── myapp/
    ├── views.py
    ├── urls.py
    └── templates/
        ├── base.html
        ├── login.html
        ├── register.html
        └── dashboard.html
```

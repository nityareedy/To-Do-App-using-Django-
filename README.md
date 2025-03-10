# Django Todo App

A simple and elegant Todo application built with Django. This application allows users to create, read, update, and delete todo items.

## Features

- User Authentication (Register, Login, Logout)
- Create, Read, Update, and Delete Todos
- Mark Todos as Complete/Incomplete
- Clean and Responsive UI using Bootstrap

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/nityareedy/To-Do-App-using-Django-
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser (optional):
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ to see the application running.

## Technologies Used

- Django 5.0.2
- Bootstrap 4
- SQLite (Database)
- Crispy Forms 
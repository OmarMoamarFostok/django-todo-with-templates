# Task Management Django Project

A simple Django-based task management web app with user authentication and task CRUD operations.

---

## Features

- User registration and login
- Task list, add, update, delete tasks
- Simple HTML templates with CSS styling
- Authentication protected pages
- Pipenv for virtual environment and dependencies

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/OmarMoamarFostok/django-todo-with-templates.git
cd django-todo-with-templates
```

### 2. Install dependencies with Pipenv
```bash
pipenv install
pipenv shell
```

### 3. Apply migrations
```bash
python manage.py migrate
```

### 4. Create a superuser (optional)
```bash
python manage.py createsuperuser
```

### 5. Run the development server
```bash
python manage.py runserver
```

### 6. Access the app
Open your browser and go to:
http://127.0.0.1:8000/
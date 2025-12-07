# Sinastar System

A Django-based web application.

## Features

- User authentication
- Database models
- Admin interface
- Media file handling

## Setup

1. Clone the repository
2. Create a virtual environment:
   ```
   python -m venv venv
   ```
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Unix/MacOS: `source venv/bin/activate`
4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Run migrations:
   ```
   python manage.py migrate
   ```
6. Create a superuser (optional):
   ```
   python manage.py createsuperuser
   ```
7. Run the development server:
   ```
   python manage.py runserver
   ```

## Requirements

- Python 3.8+
- Django 5.2.5
- Other dependencies listed in requirements.txt

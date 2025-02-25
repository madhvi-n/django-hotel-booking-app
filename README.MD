# StayFinder

[![Django CI](https://github.com/madhvi-n/stay-finder/actions/workflows/django.yml/badge.svg)](https://github.com/madhvi-n/stay-finder/actions/workflows/django.yml)
[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-5.1-brightgreen?style=flat&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Django Rest Framework](https://img.shields.io/badge/Django_Rest_Framework-3.15-red)](https://www.django-rest-framework.org/)
[![Angular](https://img.shields.io/badge/Angular-19-blueviolet)](https://angular.io/)

A **comprehensive hotel booking application**, designed to provide users with a seamless experience in finding and booking accommodations. StayFinder allows users to search, compare, and book hotels with ease, offering real-time availability, user reviews, and secure payments.

## 🚀 Features

### **🔑 Authentication & User Management** (📝 To-Do)

- User registration & login
- Token-based authentication
- Role-based access control

### **📦 Core Functionality** (📝 To-Do)

- Search and book hotels
- Filter by price, location, amenities, and ratings
- Real-time room availability and pricing
- Secure payment gateway integration
- User reviews and ratings
- Wishlist and favorites feature
- Responsive & mobile-friendly UI

### **📊 Admin Dashboard** (📝 To-Do)

- Manage users, bookings, and settings
- View reports and analytics

## 🔮 Future Considerations (📝 To-Do)

- **💬 Customer Support Chat System** *(For queries and assistance)*
- **🔎 Advanced Search & Filters** *(Additional sorting options)*
- **🛠️ Integration with External APIs** *(Google Maps, Weather, etc.)*

## 🛠 Prerequisites

- Python 3.x
- Django 4.x or higher
- Database (PostgreSQL/MySQL/SQLite)
- Virtual environment (recommended)

## ⚡ Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/stayfinder.git
    cd stayfinder
    ```

2. **Set up a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # For macOS/Linux
    venv\Scripts\activate     # For Windows
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply database migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Create a superuser (if applicable):**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

    Access the application at: <http://127.0.0.1:8000>

## 📝 API Documentation

The API documentation is available via **Swagger**:

- **Swagger UI:** `http://127.0.0.1:8000/api/swagger/`
- **Redoc:** `http://127.0.0.1:8000/api/redoc/`

## ⚙️ Environment Variables *(Example .env file)*

```ini
SECRET_KEY=django-secret-key
DEBUG=True
DATABASE_NAME=db-name
DATABASE_USER=db-user
DATABASE_PASSWORD=db-password
DATABASE_HOST=db-host
DATABASE_PORT=5432
```

## 🎉 Happy Coding! 🚀

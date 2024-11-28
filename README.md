# Django Cars Management Project

This project was created using Django and Django Template Language. It is a car management project. The user can add new cars to the main list or edit/delete the current ones. All cars and their information will be displayed on the main page. 

## Table of Contents

- [Features](#features)
- [Installation and Setup](#installation-and-setup)
- [Screenshots](#screenshots)

---

## Features
- **Cars Management:** it is possible to add, edit or delete cars.
- **User Permissions:** only logged in users have permission to add, edit or delete cars.

## Installation and Setup
### Prerequisites
- Python 3.8+
- Git
- Virtualenv

### Steps
1. Clone this repository:
    ```bash
    git clone https://github.com/aguiarjv/django-cars-project
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Apply migrations:
    ```bash
    python manage.py migrate
    ```

6. Create a superuser for admin panel access:
    ```bash
    python manage.py createsuperuser
    ```

7. Run the server:
    ```bash
    python manage.py runserver
    ```

## Screenshots

### Main Page (pt-BR)
![Main Page](/screenshots/main-page.png?raw=true "Main Page")

### Car Detail (pt-BR)
![Car Detail](/screenshots/car-detail.png?raw=true "Car Detail")

### Car Edit (pt-BR)
![Car Edit](/screenshots/car-edit.png?raw=true "Car Edit")
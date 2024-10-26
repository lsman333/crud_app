# CRUD App with Django

A simple CRUD (Create, Read, Update, Delete) application built with Django for managing a to-do list. This project uses Django and additional libraries to provide a clean, styled UI with crispy forms.

## Features

- Add, view, update, and delete to-do items.
- Simple UI with Bootstrap styling for forms.
- Built with Django, `crispy-bootstrap5`, and `django-crispy-forms` for form management and styling.

## Requirements

- Python 3.11
- Django 5.1.2
- asgiref 3.8.1
- crispy-bootstrap5 2024.10
- django-crispy-forms 2.3
- sqlparse 0.5.1

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/lsman333/crud_app.git
   cd crud_app

2. **Create the virtual environment**
    python3 -m venv venv

3. **Activate the virtual environment**
    on MacOS and Linux:
    source venv/bin/activate

4. **On Windows**
    venv\Scripts\activate

4. **Install the dependencies**
    pip install -r requirements.txt

5. **Run the migrations**
    python manage.py migrate

6. **Start the development server**
    python manage.py runserver

7. **Access the app**
    Open your web browser and go to http://127.0.0.1:8000/


Usage
-----
To add a new to-do item, click on "Add" and fill out the form.
To update an item, click "Edit" next to it, make changes, and save.
To delete an item, click "Delete."

Dependencies
------------
The following packages are used in this project:

* Django: The web framework used to build the application.
* asgiref: ASGI reference library, a Django dependency.
* crispy-bootstrap5: Bootstrap 5 integration for django-crispy-forms.
* django-crispy-forms: Provides easy integration of Bootstrap with Django forms.
* sqlparse: SQL parser, a Django dependency.

License
-------
This project is open source and available under the MIT License.
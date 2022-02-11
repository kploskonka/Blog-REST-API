# Blog REST API

Blog API with user authorization and token authentication made using Django Rest Framework. 

## Installation

Use [pipenv](https://pypi.org/project/pipenv/) to create a virtual environment and install dependencies.

```bash
pipenv install
```

## Usage

```bash
# Activate the virtual environment
pipenv shell

# Set up the application
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
The application by default runs on [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Documentation
- Login: [http://127.0.0.1:8000/api/v1/rest-auth/login/](http://localhost:8000/api/v1/rest-auth/login/)
- REST API documentation available at: [http://127.0.0.1:8000/swagger-docs/](http://127.0.0.1:8000/swagger-docs/) - Available only to authenticated users.

---
Katarzyna Płoskonka &copy; 2022

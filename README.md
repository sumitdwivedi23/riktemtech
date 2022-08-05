# Django-Chat-App


## Prerequisites

- [Django](https://www.djangoproject.com/)
- [MySQL](https://www.mysql.com/)

## Installation
- Create a virtual environment
    ```bash
     virtualenv -p python3 venv
    ```
- Activate the virtual environment
    ```bash
    source venv/bin/activate
    ```
- Install all the dependencies from `requirements.txt`
    ```python
    pip3 install -r requirments.txt
    ```
- Run the server
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```
- Hit the url `http://localhost:8000/`

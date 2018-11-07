# django-oscar-boilerplate

## Requirements
This project has been built using Django 2.1

## Installation

Install the project dependancies
```bash
pip install requirements.txt
```

Install optional oscar template requirements
```bash
pip install django-compressor
pip install django-widget-tweaks
```

Create the database structure
```bash
python manage.py migrate
```

Create a user to login.
Note: The oscar login requires an email address
```bash
python manage.py createsuperuser
```

Run the project
```bash
python manage.py runserver
```

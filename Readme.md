# Store Front

## Installation and Running Project

### Install & Check Python
```bash
python3 --version
```
Clone the repository
```bash 
git clone ""
```

### Installing pipenv on entire machine
```bash
pip3 install pipenv
```
### Virtual Enviroments
Creating virtual enviroment for the specific project
```bash
pipenv install django
```
Activating
```bash
pipenv shell

```

### Starting a Django project
```bash
django-admin
# list all django commands available
django-admin startproject projectname .
# This will start a roject at the current directory without creating another directory where projectname is the name of the project you intent to make
```
### Running the server
```bash
python manage.py runserver
```
### Creatin an app in the project
```bash
python manage.py startapp new_app_name
```

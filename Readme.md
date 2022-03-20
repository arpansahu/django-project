
# Django Project

This project is implementation for the following topics related to technologies used with Django

-Implemented Complete Auth Using Django Default Auth Model.
    
1. Used built in Django Auth Model
2. Implemented custom error View for customizing Templates
3. Login. SingUp, Logout, Account Views Implemented
4. In built views of PasswordChangeDoneView, PasswordChangeView, PasswordResetCompleteView, PasswordResetConfirmView, PasswordResetView, PasswordResetCompleteView
5. Build Custom Templates for These Inbuilt Views

-Implemented Crud Operations with Django Forms

1. build crud operation create, update, delete, read function views
2. build templates for handling it
3. Created Django forms

-Implemented Crud Operations with Ajax 

1. build crud operations with generic View as base class 
2. used ListView as base class for View
3. Used Ajax for Dynamically interacting with these views without reloading the html page

-Implemented Crud Operations with GraphQl

1. used graphene python library, for performing curd operations 
2. build function based crud views
3. used ajax, django forms

-Build Rest API

1. Used Django Rest Framework, and build a lot of apis for handling different operations
2. Implemented all the views available in Django Rest Framework
3. Build Swagger around all the apis whose link is available at the homepage at live demo

-Build GraphQl API

1.Build API for crud using Graphene

## Tech Stack

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Jquery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)](https://jquery.com/)
[![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)](https://graphql.org/)
[![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)](https://www.django-rest-framework.org/)
[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

## Demo

Available at: https://django-project-api-crud-graphq.herokuapp.com/

admin login details:--
username: arpansahu
password: showmecode
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Installation

Installing Pre requisites

```bash
  pip install -r requirements.txt

```

Making Migrations and Migrating them.

```bash
  python manage.py makemigrations
  python manage.py migrate

```

Creating Super User

```bash
  python manage.py createsuperuser

```

Run Server
```bash
  python manage.py runserver

```

## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?


## Deployment on Heroku

Installing Heroku Cli from : https://devcenter.heroku.com/articles/heroku-cli
Create your account in Heroku.

Inside your project directory

Login Heroku CLI
```bash
  heroku login

```

Create Heroku App

```bash
  heroku create [app_name]

```

Push Heroku App
```
    git push heroku master
```

Configure Heroku App
```bash
  add all the env variables used from app setting page on heroku app dashboard.

```
Configuring Django App for Heroku
```
    install whitenoise : pip install whitenoise 
    include it in included_apps=[]
    add whitenoise middleware
    add: procfile
    add: release-task.sh for running mutilple commands in run: section of procfile
```
## Tech Stack

**Client:** HTML, Jinja, CSS, BootStrap, Jquery

**Server:** Django, Django Rest Framework, Gunicorn, GraphQL, Heroku


## Deployment on Heroku

Installing Heroku Cli from : https://devcenter.heroku.com/articles/heroku-cli
Create your account in Heroku.

Inside your project directory

Login Heroku CLI
```bash
  heroku login

```

Create Heroku App

```bash
  heroku create [app_name]

```

Push Heroku App
```
    git push heroku master
```

Configure Heroku App
```bash
  add all the env variables used from app setting page on heroku app dashboard.

```
Configuring Django App for Heroku
```
    install whitenoise : pip install whitenoise 
    include it in included_apps=[]
    add whitenoise middleware
    add: procfile
    add: release-task.sh for running mutilple commands in run: section of procfile
```
## Documentation

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Jquery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)](https://jquery.com/)
[![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)](https://graphql.org/)
[![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)](https://www.django-rest-framework.org/)
[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

SECRET_KEY=
DEBUG=

DB_HOST=
DB_NAME=
DB_USER=
DB_PASSWORD=
DB_PORT=

EMAIL_USER=
EMAIL_PASS=

ALLOWED_HOSTS=

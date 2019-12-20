# djangotutorial
 Various tutorials for Django

NB: 
* django-admin startproject mysite to create project.
* python manage.py runserver to turn site on
* python manage.py startapp polls to create polls app

Routine for DB updates:
* python manage.py migrate
* { Make changes }
* python manage.py makemigrations polls
* python manage.py sqlmigrate polls 0001
* python manage.py migrate

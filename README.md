# helloworld

a very simple first Django app where we:

* created a directory for our code
* used pipenv to create a new virtual environment and installed Django
  * pipenv install django
  * pipenv shell
* created a new Django project (don't forget the .)
  * django-admin startproject helloworld_project .
* created a new app:
  * python manage.py startapp pages
* updated pages/views.py
* created and updated pages/urls.py
* migrate built in apps (avoid all the output in the command line)
  * python manage.py migrate
* ran the server:
  * python manage.py runserver

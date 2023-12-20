open folder
pip install pipenv  //to create virtual environment
pipenv shell  //activate virtual env
pipenv --venv  //to check are we in virtual env or not?
pip install django
django-admin //to view all django commands
cls //to clear terminal
django-admin startproject projectname //to create django project

then move all files from projectname folder to root folder

view->command palette ->python:select interpreter ->select our vitual env with our path and folder name 

//check cmd line to run manage.py using cd cmd

python manage.py runserver //to run django server

python manage.py runserver 8001 //to run django at specific server

python manage.py startapp app_name //to create app

//after creating apps and views and models

//makemigrations
python -m pip install Pillow
pip install psycopg2 //for postgresql  client--pip

python manage.py makemigrations

//migrate

python manage.py migrate

//then go to pgadmin and to db and check tables and press view data by rightclick on some class table to view structure of it //for postresql

//then createsuperuser for admin purpose

python manage.py createsuperuser

//then run server
python manage.py runserver

//modify url with /admin to logon admin panel 

to obtain good admin panel
add 'jazzmin', to installed_apps in settings.py

pip install django-jazzmin

then add category and products to provide a good looking E-commerce website

@Sebe S 2023
gathered from tutorial video form tutor joes
website:
https://sebe2k04.github.io
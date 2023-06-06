# Django-LcoTubers
My first Django project that i learnt from Learn Code Online by Hitesh Chaudhary.

## Setup Virtual Environment
  If you want to run your application in virtual environment then install pipenv.
  
    $ pip3 install pipenv
    
  You have to create shell by running command:
  
    $ pipenv shell
    
  Now your virtual environment is created. From now onwards you can activate your shell with same command.
  
  
## Install Django
  You can install it by using command:
  
    $ pip3 install Django
    
  But you are in virtual environment i.e: pipenv so use command:
  
    $ pipenv install Django
    
    
    
## Creating Django Project
  When we install Django it gives us django-admin. You can create your project by command:
  
    $ django-admin startproject PROJECT_NAME
  
  
  
## Check Your Installation
  Navigate to folder where you can find manage.py and running/checking your application run command:
  
    $ python3 manage.py runserver
  

## Create an admin User
  Django comes up with a default admin panel you just have to create user for it and start using it.
  Creation of superuser:

    $ python3 manage.py createsuperuser

  Enter all the required fields and your superuser created.
  type 127.0.0.1:8000/admin/ for entering into admin panel.

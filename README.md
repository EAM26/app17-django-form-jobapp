- pip install django
- django-admin startproject mysite .
- python manage.py startapp job_application
- // The project is mysite wich can have multiple apps (now only 
  job_application)
- // Add jop_application to settings.py
- python manage.py runserver // To run the app
- // Create form model
-  python manage.py makemigrations  // creates py file for setup db
- python manage.py migrate // the actual migration 


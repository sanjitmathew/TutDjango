## TutDjango
### Virtual Environment
- create folder in cmd and type **virtualenv .** in cmd to create virtual environment
- to activate virtual environment run **Scripts/activate**
### Django Project
- to create a project use **django-admin startproject ProjectName .**
- first use **migrate** alone to build database
- to start an application use **python manage.py startapp AppName** and register it in settings.py
- after each change to models use **makemigrations** and **migrate**
- use **python manage.py shell** to access python shell to insert values into model table
- all changes to models can be found in migrations folder

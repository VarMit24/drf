1. Activate venv
    -> source venv/bin/activate
2. How to create an app
    -> cd backend
    -> python manage.py startapp <app_name>
3. How to m=run migrations
    -> cd backend
    -> python manage.py makemigrations
    -> python manage.py migrate #To apply migrations
4. How to open a shell
    -> cd backend
    -> python manage.py shell
    -> from <app_name>.models import <app_name>
    -> <app_name>.objects.create()

Run backend server
    1. cd backend
    2. python manage.py runserver 8000

Run Frontend
    1. cd py_client
    2. python basic.py
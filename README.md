YOUTUBE LINK
https://www.youtube.com/watch?v=tYKRAXIio28&t=1379s

Virtual Environment (setting up virtual environment)

> Desktop>myDjangoNotes>env\scripts\activate

Command

> python manage.py runserver

> python manage.py createmigrations
> python manage.py migrate

> python manage.py createsuperuser

Installing RESTFRAMEWORK

> pip install djangorestframework

add 'rest_framework' to your INSTALLED_APPS setting.
INSTALLED_APPS = [
...
'rest_framework',
]

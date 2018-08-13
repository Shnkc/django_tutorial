## CODE OF DJANGO TUTORIAL FROM OFFICIAL SITE
Django version: v1.10

Site link: https://docs.djangoproject.com/en/1.10/intro/

### BEFORE START:
1. There ust be a db. This project does not have any db file. Therefore, before running, you need to build up one 
and integrate it with this project. Sqlite3 is integrated by default. Migrate the project with following command to 
have a ready-to-go db with necessary tables:

    ``python manage.py migrate``

2. Inside file `djangotest/settings.py`, `SECRET_KEY` parameter is not set by default. When you generate a Django project,
this key will be there. I have moved this key into a file. For a testing purpose, just set this parameter 
with a non-empty string.

I think this items will be enough to run the project smoothly. If there is any blocker, please inform me. 
### RUN PROJECT
``python manage.py runserver``
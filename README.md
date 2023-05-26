# django_boilerplate
This is a plain django 4.1 boiler plate setup to use postgres.

To use:
 - create a new repo using this as the template.
 - run docker-compose build --force

To add an app:
 - run docker-compose run --rm app sh -c "python manage.py startapp \<appname>"
 - run sudo chown -R $user:$user in the project directory to fix permision issues

To run manage.py:
  - run ```docker-compose run --rm app sh -c "python manage.py \<command>```

To run the app:
  - run ```docker-compose -d up```

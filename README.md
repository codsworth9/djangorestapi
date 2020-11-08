# Django Rest Api with blog model and authentication

## Requirements

- Python 3
- [Pip](https://pip.pypa.io/en/stable/)
- Virtual enviroment for python, for example [Pipenv](https://github.com/pypa/pipenv)

## Features

- Sign In
- Sign Up
- Sign Out
- Post Create-Read-Update-Delete
- Token authentication

## Try it out (example with pipenv)

```bash
pipenv shell

pipenv install

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
```

- Go to http://127.0.0.1:8000/admin to login to the admin area.

- Go to http://127.0.0.1:8000/api/v1/ to perform POST action with your current user.

- Go to http://127.0.0.1:8000/api/v1/{POST_id} to perform PUT and DELETE action with your current user.

- Go to http://127.0.0.1:8000/api/v1/rest-auth/registration/ to create a new user.

- Go to http://127.0.0.1:8000/api/v1/rest-auth/login/ to login with an existing usner.

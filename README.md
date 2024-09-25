# creating and activating virtualenv
```sh
python -m venv venv
venv/scripts/activate
```

# installing packages and creating project
```sh
pip install django
django-admin startproject core .
python manage.py startapp users
```

# installing grpahql and jwt
```sh
https://docs.graphene-python.org/projects/django/en/latest/installation/#
https://django-graphql-jwt.domake.io/quickstart.html

pip install graphene-django
pip install django-graphql-jwt
pip freeze > requirements.txt
```
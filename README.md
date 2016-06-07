# django-rest-framework-quickstart

This is the DRF quickstart tutorial

```shell
pip install django djangorestframework httpie
python manage.py migrate
python manage.py createsuperuser
http -a username:password GET http://localhost:8004/users/
```
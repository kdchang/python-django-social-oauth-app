# Python Django Social Oauth App
A python django web app use allauth to support oauth login

## Usage
1. $ git clone https://github.com/kdchang/python-django-social-oauth-app.git && cd python-django-social-oauth-app
2. $ virtualenv venv
3. $ source venv/bin/activate
4. $ pip install -r requirements.txt
5. $ python manage.py migrate
6. $ python manage.py makemigrations
7. $ python manage.py runserver
8. go to http://127.0.0.1:8000/admin setup your sites in admin
9. add social app in admin

## Documents
1. [Welcome to django-allauth! Doc](https://django-allauth.readthedocs.io/en/latest/index.html)
2. [Django-allauth No Facebook app configured: please add a SocialApp using the Django admin](https://stackoverflow.com/questions/14019017/django-allauth-no-facebook-app-configured-please-add-a-socialapp-using-the-djan)
3. [Anymail: Django email backends for Mailgun, Mailjet, Postmark, SendGrid and more](http://anymail.readthedocs.io/en/stable/)
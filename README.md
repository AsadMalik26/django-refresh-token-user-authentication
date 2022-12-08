# Installation guide

#Setup Backend
1. cd refresh-token-interval/backend
2. pip install -r requirements.txt
3. python manage.py createsuperuser
4.  python manage.py runserver

#Setup Frontend

1. cd refresh-token-interval/frontend
2. npm install
3. npm start


# if there is only Pipfile & pip lock file is nor present or deleted
pip freeze > requirements.txt
### it will create requirements.txt file
## then
$ pipenv lock -r > requirements.txt
or
$ pipenv install --skip-lock
### it will install dependencies from Pipfile
## Done



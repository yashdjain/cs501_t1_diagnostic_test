web: gunicorn manage:app
heroku ps:scale web=1
init: python manage.py db init
migrate: python manage.py db upgrade


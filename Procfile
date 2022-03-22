release: python manage.py makemigrations
--no-input
release: python manage.py migrate ---no-input
web: python userauthentications/manage.py runserver 0.0.0.0:$PORT
web: gunicorn userauthentications.wsgi

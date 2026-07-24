# This helps in deployment of the project
release: python manage.py makemigrations
release: python manage.py migrate
web: gunicorn portfolio.wsgi --log-file -
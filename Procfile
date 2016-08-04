web: python ./manage.py makemigrations
web: python ./manage.py migrate
web: gunicorn bucketlist_application.wsgi --log-file -

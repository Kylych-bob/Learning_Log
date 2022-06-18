release: python3 manage.py migrate
web: python project-name/manage.py runserver 0.0.0.0:$PORT
web: gunicorn learning_log.wsgi --log-file=-
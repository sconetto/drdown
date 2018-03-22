web: gunicorn config.wsgi:application
worker: celery worker --app=drdown.taskapp --loglevel=info

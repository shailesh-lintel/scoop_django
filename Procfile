web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=scoop_django.taskapp --loglevel=info
web: newrelic-admin run-program gunicorn --pythonpath="$PWD/test-django-rest" wsgi:application
worker: python test-django-rest/manage.py rqworker default
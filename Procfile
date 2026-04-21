web: python manage.py collectstatic --noinput && python manage.py migrate --run-syncdb && gunicorn frontend_server.wsgi --bind 0.0.0.0:$PORT

web: bin/start-pgbouncer gunicorn config.wsgi:application --log-file - --log-file debug
python manage.py collectstatic --noinput
manage.py migrate

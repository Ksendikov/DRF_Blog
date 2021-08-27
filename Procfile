web: bin/start-pgbouncer-stunnel gunicorn config.wsgi:application --log-file - --log-file debug
python manage.py collectstatic --noinput
manage.py migrate

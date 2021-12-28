web: gunicorn app:app --log-file=-
web: gunicorn firstDjango.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate
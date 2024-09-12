web: gunicorn blogsite.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn blogsite.wsgi
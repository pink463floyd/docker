#launch container to run django-admin.py; create image if needed.
docker-compose --verbose run web django-admin.py startproject composeexample .

#start postgres and django containers
docker-compose up

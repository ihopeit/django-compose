# to start the app
docker-compose up

# to migrate database

docker-compose run web python manage.py migrate

# create super user
docker-compose run web python manage.py createsuperuser

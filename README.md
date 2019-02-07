# recipe-app-api
Recipe App API Source Code


# run tests
docker-compose run --rm app sh -c "python manage.py test && flake8"

# build
docker-compose build

# run app
docker-compose up

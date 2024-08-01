# django-recipe-app-api-udemy

# flake 8 use for linting the code
# flake 8 run by the docker using this command
docker-compose run -rm app sh -c "flake8"
and click enter

# after that, i need to create new django project
# install django project with the docker 
docker-compose run --rm app sh -c "django-admin startproject ."
and click enter

# run project with docker compose
docker-compose up
and click enter


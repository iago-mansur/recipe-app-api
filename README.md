# recipe-app-api
Recipe API project.

=========Desenvolvimento===========
Criar Token no Dockerhub

Criar repositório no github e configurar Token

git clone https://github.com/iago-mansur/recipe-app-api.git

cd recipe-app-api/

code .

criar requirements.txt, Dockerfile, docker-compose.yml, .dockignore, pasta app

sudo chmod 666 /var/run/docker.sock

docker build .

docker-compose build

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose up

http://127.0.0.1:8000/

docker-compose run --rm app sh -c "python manage.py test"

docker-compose up

docker-compose down

docker-compose build

docker-compose run --rm app sh -c "django-admin startapp core"

docker-compose run --rm app sh -c "python manage.py test"

docker-compose run --rm app sh -c "python manage.py wait_for_db"

docker-compose run --rm app sh -c "python manage.py wait_for_db && flake8"

docker-compose down

docker-compose up

docker-compose run --rm app sh -c "python manage.py test"

docker-compose run --rm app sh -c "python manage.py makemigrations"

docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"

docker volume ls

docker volume rm recipe-app-api_dev-db-data

docker-compose down

docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"

docker-compose run --rm app sh -c "python manage.py test"

docker-compose up

http://127.0.0.1:8000/

docker-compose run --rm app sh -c "python manage.py createsuperuser"

Email: admin@example.com                    
Password: 123456
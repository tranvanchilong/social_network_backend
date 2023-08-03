# chạy project 

docker-compose -f docker-compose-test.yml up

# host


python -m django startproject ecommerce
python .\manage.py startapp product

docker run --name docker_django_ecommerce_login -p 5004:8000 -it -v ${PWD}/app:/app:rw api_django /bin/bash

python manage.py runserver 0.0.0.0:8000

pip install django-cors-headers
pip install -U djoser
pip install Pillow
pip install stripe-django


python manage.py runserver
long123
tranvanchilong@gmail.com
a0977293389
python manage.py makemigrations
python manage.py migrate 
python manage.py createsuperuser


'corsheaders.middleware.CorsMiddleware',


docker login registry.gitlab.com
docker build -t registry.gitlab.com/tranvanchilong/async_web_gia:v0.2 .
docker run --name test -it -p 5002:8000 -v ${PWD}/app:/app:rw registry.gitlab.com/tranvanchilong/async_web_gia:v0.2 /bin/bash
registry.gitlab.com/tranvanchilong/async_web_gia:v0.2
docker push registry.gitlab.com/tranvanchilong/async_web_gia:v0.2


scp -r starlette_web_gia root@139.162.28.246:/home
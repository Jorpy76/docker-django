# docker-django

pipenv shell
pip install django

django-admin startproject config .

verificar proyecto django que corra ...
python manage.py runservice 

docker build -t jriosf/docker-django .
docker run -p 8000:8000 jriosf/docker-django




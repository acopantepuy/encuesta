# Encuesta
Encuesta Python

Este proyecto es parte del tutorial de la pagina oficial de Django para asimilar los conceptos de Django:

https://docs.djangoproject.com/es/6.0/

## Contenido:
- Tutorial01
- Tutorial02
- Tutorial03
- Tutorial04
- Tutorial05
- Tutorial06

## Instalación

1. git clone git@github.com:acopantepuy/encuesta.git
2. cd encuesta
3. python -m venv .env
4. source .env/bin/activate
5. pip install -r requirements.txt
6. python manage.py migrate
7. python manage.py createsuperuser
8. python manage.py runserver

Panel Administrativo:

http://127.0.0.1:8000/admin/

- Se deben agregar las preguntas con sus respuestas.

App:

http://127.0.0.1:8000/polls/
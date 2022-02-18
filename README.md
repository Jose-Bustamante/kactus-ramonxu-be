# kactus-ramonxu-be

## What is this..
Good question, I have no clue, is supposed to be a Python project using Django to expose some microservice such as `api/todos/` and `/api/todos/${id}`
  - `http://localhost:8000/api/`
  - `http://localhost:8000/api/todos`
  - `http://localhost:8000/api/todos/1`


It uses SQLite as default DB, you can access the admin panel in the route `/admin` I think. `http://localhost:8000/` or `http://localhost:8000/admin`

It uses `djangorestframework` and `django-cors-headers` for the serialization of the models into JSON, you can inspect them in the UI in the URLs I put before.

The APIs are supposed to be consumed by a detached FE layer, build what ever you like, I will give you a React example so you don't cry me a river. [here](https://github.com/Jose-Bustamante/kactus-ramonxu-fe) is it.

## How to Start (I have no idea of what I am doing)
- Have Python 3 installed obviously you noob.
- Install DJango [here how](https://docs.djangoproject.com/en/4.0/intro/install/)
- `pip` should come with the latest versions of Phyton (but what do I know, never done Phyton in my life) so check it you have it `pip3 --version` if you see errors and shit... well google how to install it.
- Do some `python manage.py migrate` inside the project folder for some extra magic to happen.
- create your own Admin user cus I'aint giving you shit data `python manage.py createsuperuser` please use as your user password a super secure password such as "1234" or "password" for extra security when creating your user.
- Run your server by using `python manage.py runserver`

## Trouble shooting:
- If at this point you haven't figured out that I have no idea about none of this languages of frameworks... well seek help.
- JK, [here](https://letmegooglethat.com/?q=Django+getting+started) you have all the answers you need.
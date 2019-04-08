# Snippet DRF API

### Installation & Setup

```sh
$ git clone https://github.com/jaselnik/Snippet-DRF-API.git
$ cd Snippet-DRF-API
```
```sh
$ virtualenv venv
$ source venv/bin/activate
$ export DJANGO_SETTINGS_MODULE=tutorial.settings.api_prod
```
```sh
(venv) $ python manage.py migrate
(venv) $ python manage.py runserver 0.0.0.0:8000
(venv) $ python manage.py runserver --settings=tutorial.settings.api_prod
(venv) $ celery -A oreado_backend worker -l info -B
```

### REST API!

- [Local highlights](http://127.0.0.1:8000/)

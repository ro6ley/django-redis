[![HitCount](http://hits.dwyl.io/ro6ley/django-redis.svg)](http://hits.dwyl.io/ro6ley/django-redis)

# Django_Redis

This repository contains the code for this [blogpost](https://stackabuse.com/working-with-redis-in-python-with-django/).

## Getting Started

### Prerequisites

Kindly ensure you have the following installed on your machine:

- [ ] [Python 3](https://realpython.com/installing-python/)
- [ ] [Pipenv](https://pipenv.readthedocs.io/en/latest/#install-pipenv-today)
- [ ] [Redis](https://redis.io/download)
- [ ] [Git]()
- [ ] An IDE or Editor of your choice

### Running the Application

1. Clone the repository
```
$ git clone https://github.com/ro6ley/django-redis.git
```

2. Check into the cloned repository
```
$ cd django-redis
```

3. If you are using Pipenv, setup the virtual environment and start it as follows:
```
$ pipenv install && pipenv shell
```

4. Install the requirements
```
$ pip install -r requirements.txt
```

4. Configure Redis configuration in `django_redis_demo/settings.py`

5. Start the Django API
```
$ python manage.py runserver
```

6. Send requests to `http://localhost:8000/api/items`

## Contribution

Please feel free to raise issues using this [template](./.github/ISSUE_TEMPLATE.md) and I'll get back to you.

You can also fork the repository, make changes and submit a Pull Request using this [template](./.github/PULL_REQUEST_TEMPLATE.md).

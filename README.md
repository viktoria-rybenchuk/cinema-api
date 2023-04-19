# Cinema API

API service for cinema management written on DRF

## Installing using GitHub:

```
git clone git@github.com:viktoria-rybenchuk/cinema-api.git
cd cinema
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
set POSTGRES_HOST=<you db hostaname>
set POSTGRES_DB=<your db name>
set POSTGRES_USER=<your db username
set POSTGRES_PASSWORD=<your db user password>
python manage.py migrate
python manage.py runserver
```

## Run with Docker
Docker should be installed

```
docker-compose build
docker-compose up
```


## Getting access
- create user via/api/user/register/
- get access token via/api/user/token/

## Features

- JWT authenticated
- Admin panel/admin
- Documentation is located at /api/doc/swagger/
- Managing movies with genres, actors
- Creating cinema halls 
- Adding movie sessions 
- Filtering movies and movie sessions
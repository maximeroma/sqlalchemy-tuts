# sqlalchemy tuts

## Requirements:

- have venv python 3.6
- activate venv : pipenv shell

- docker run --name sqlalchemy-orm-psql \
  -e POSTGRES_PASSWORD=pass \
  -e POSTGRES_USER=usr \
  -e POSTGRES_DB=sqlalchemy \
  -p 5435:5432 \
  -d postgres

## Play with inserts:

- python inserts.py

## Play with queries:

- python queries.py

## Clear workspace:

- docker stop sqlalchemy-orm-psql
- docker rm sqlalchemy-orm-psql

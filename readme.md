# Crudzin

Experiência com um crud usando flask e suas ferramentas.

https://www.youtube.com/watch?v=WzaKIRJBGXo


- flask
- flask_sqlalchemy
- flask_migrage
- flask_marshmallow
- marshmallow_sqlalchemy


## Como rodar esse projeto:

```sh
export FLASK_APP=app
export FLASK_ENV=Development
export FLASK_DEBUG=True

flask run
```

## Como fazer as migrações

```sh
flask db init
flask db migrate
flask db upgrade
```
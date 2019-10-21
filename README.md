# Drjact Boilerplate

This repository contains a boilerplate project setup for Django and React. The project contains backend user authentication with the Django Rest Framework and rest-auth. The frontend has react redux setup for user authentication by storing the token in localstorage. It ships standard with sqlite but you'll also probably want to switch it over to postges once deployed. (Perhaps a future release might just have a command/script to run instead?)

[You too can watch the tutorial it was taken from!](https://youtu.be/YKYVv0gm_0o)

As a point of security, navigate over to a site like https://djecrety.ir/ to quickly make a secret key to place in base.py before trying to run the site. 


## Backend dev workflow

```json
virtualenv djenv
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

## Frontend dev workflow

```json
npm i
npm start
```

## For deployment

```json
npm run build
```
# drjact-boilerplate

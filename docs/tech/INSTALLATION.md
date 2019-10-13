# Installation

## Required
- [Docker compose](https://docs.docker.com/compose/install/)

## Prod
Create the file `api/.env.local`:
```yml
SERVER_NAME='[client's name]'
```

Create the file `client/.env`:
```yml
CODE_ADMIN=1987
API_URL=http://[server's ip]:8000
```
Then run `make install` and have a :coffee:.

## Dev
Create the file `api/.env.local`:
```yml
SERVER_NAME='[your name]'
APP_ENV=dev
APP_DEBUG=1
```

Create the file `client/.env`:
```yml
CODE_ADMIN=1987
```
Then run `make install` and have a :coffee:.

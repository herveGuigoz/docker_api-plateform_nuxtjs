# API

Documentation spécifique à l'API.

## Useful commands
```bash
# Composer
docker-compose run php composer
```

## Known errors
```bash
# 502 Bad gateway => restart php-fpm 
docker-compose exec php php-fpm -D 
```
ApiPlatform [Issue#797](https://github.com/api-platform/api-platform/issues/797)

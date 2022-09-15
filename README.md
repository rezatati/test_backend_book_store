# store Backend

## Project setup
```
composer install
```
## DB setup
Update .env for DB access info then run 
```
 php bin/console doctrine:database:create
 php bin/console doctrine:migrations:migrate 
```

## Run local server
```
symfony serve
```

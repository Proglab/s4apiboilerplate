# Symfony 4 boilerplate API

Ceci est un début de projet pour Symfony 4 

## Lancement local

### installation des dépendances

```bash
cd src
composer install
```

### Configuration de la DB

modifier le fichier .env

### Création de la DB locale

```bash
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
php bin/console doctrine:fixtures:load
```

### Lancer le serveur local

```bash
php bin/console server:run --docroot=public
```

## Outils de développement/intégration/tests/...

### PHP-CS-Fixer

#### Installer

```bash
composer global require friendsofphp/php-cs-fixer
```

#### Executer

```bash
php-cs-fixer fix src
```


### PHP CodeSniffer

#### Installer

```bash
composer global require "squizlabs/php_codesniffer=*"
```

#### Executer

```bash
php-cs-fixer fix src
```


## Contribution
Des pull requests sont les bienvenus. Pour des modifications plus importantes, merci de faire une issue qu'on en discute avant.

N'oubliez pas les tests et les [emojis](https://gitmoji.carloscuesta.me/) sur les commits ! 

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Technologies utilisées

- [Symfony](https://symfony.com/)
- [Api Platform](https://api-platform.com/)
- [Swagger](https://swagger.io/)

## Liens disponibles :

- /api pour le lein vers swagger
- /admin/ pour le lien vers l'admin

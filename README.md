
# Project Garage V. Parrot

Site vitrine du garage, disposant de la présentation des services proposés, des véhicules disponible à la vente, des horaires d'ouvertures ainsi qu'un moyen de contact.


## Documentation

https://symfony.com/doc/current/index.html
https://dev.mysql.com/doc/


Admin Connexion

Mail: VincentParrot@gmail.com
MDP: 1234
(hashé dans la base de donnée)


## Features

- Light/dark mode
- Gestions Admin EasyAdmin
- Fullscreen mode
- Cross platform


## Run Locally

Clone the project

```bash
  git clone du Projet
```

Launch MySQL

Services de composants>MySQL80>Démarrer


Install dependencies

```bash
   conposer uptdate
   yarn install
```

Start the server

```bash
  symfony server:start -d
```


## Tech Stack

"require":

        "php": ">=8.1",
        "ext-ctype": "*",
        "ext-iconv": "*",
        "doctrine/doctrine-bundle": "^2.10",
        "doctrine/doctrine-migrations-bundle": "^3.2",
        "doctrine/orm": "^2.15",
        "easycorp/easyadmin-bundle": "^4.7",
        "phpdocumentor/reflection-docblock": "^5.3",
        "phpstan/phpdoc-parser": "^1.22",
        "symfony/asset": "6.3.*",
        "symfony/console": "6.3.*",
        "symfony/doctrine-messenger": "6.3.*",
        "symfony/dotenv": "6.3.*",
        "symfony/expression-language": "6.3.*",
        "symfony/flex": "^2",
        "symfony/form": "6.3.*",
        "symfony/framework-bundle": "6.3.*",
        "symfony/http-client": "6.3.*",
        "symfony/intl": "6.3.*",
        "symfony/mailer": "6.3.*",
        "symfony/mime": "6.3.*",
        "symfony/monolog-bundle": "^3.0",
        "symfony/notifier": "6.3.*",
        "symfony/process": "6.3.*",
        "symfony/property-access": "6.3.*",
        "symfony/property-info": "6.3.*",
        "symfony/runtime": "6.3.*",
        "symfony/security-bundle": "6.3.*",
        "symfony/serializer": "6.3.*",
        "symfony/string": "6.3.*",
        "symfony/translation": "6.3.*",
        "symfony/twig-bundle": "6.3.*",
        "symfony/validator": "6.3.*",
        "symfony/web-link": "6.3.*",
        "symfony/webpack-encore-bundle": "^2.0",
        "symfony/yaml": "6.3.*",
        "twig/extra-bundle": "^2.12|^3.0",
        "twig/twig": "^2.12|^3.0",
        "vich/uploader-bundle": "^2.1"

 "devDependencies": {
        "@babel/core": "^7.17.0",
        "@babel/preset-env": "^7.16.0",
        "@popperjs/core": "^2.11.8",
        "@symfony/webpack-encore": "^4.4.0",
        "autoprefixer": "^10.4.14",
        "bootstrap": "^5.3.0",
        "core-js": "^3.23.0",
        "jquery": "^3.7.0",
        "postcss-loader": "^7.3.3",
        "regenerator-runtime": "^0.13.9",
        "sass": "^1.63.6",
        "sass-loader": "^13.0.0",
        "webpack": "^5.74.0",
        "webpack-cli": "^4.10.0",
        "webpack-notifier": "^1.15.0"
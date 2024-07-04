# twig-2024-2
Utilisation de Twig - moteur de template

Il faut vérifier que PHP soit dans path

```bash
php -v
```

## Installation de composer

Puis il faut installer `composer` en suivant le lien suivant :

https://getcomposer.org/download/

## Installation de Twig

Documentation :
https://twig.symfony.com/doc/3.x/

```bash
composer require "twig/twig:^3.0"
```

Grâce à `composer.json`, on peut installer (ou mettre à jour) 
n'importe quelle bibliothèque :

```bash
composer install
# ou
composer update
```

Les fichiers vont dans le dossier `vendor/`, il est donc utile de le mettre
dans le `.gtiignore`

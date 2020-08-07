# Gestion de catalogue V0
# Application minimale à installer comme fil rouge de test 
# du cours API en Symfony
#
# Symfony 5.0.8, PHP 7.3.11, MySQL 8.0.18
#
# Pour l'installation, les commandes suivantes vous permettront :
# de rapatrier touts les dépendances (vendor)
# de créer la base de données
# d'y créer les tables SQL
# de créer un jeu de données dans la base de données (fixtures)

### Installation :

- `composer install`
- `php bin/console doctrine:database:create`
- `php bin/console d:m:m`
- `php bin/console d:f:l --no-interaction`

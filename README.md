# Application Gestion de Location de Voitures

## Objectif de l'application

Le but de ce projet est de développer une application de gestion de location de voitures à l'aide du langage PHP, du framework Laravel, et d'une base de données MySQL.

## Fonctionnalités

- Gestion des voitures du parc (création, modification, suppression, listing).
- Liste des individus ayant loué une voiture.
- Emprunt et retour de voitures par des individus.
- Connexion obligatoire pour louer un véhicule.
- Consultation de la liste des véhicules possible en mode non connecté.
- Ajout, modification, et suppression de véhicules réservé aux profils administrateurs.
  ##Lancer le projet
#composer update

#creer la base de donne et le lier au fichier .env
-npm install

-php rtisan key:generate

-php artisan storage:link

-php artisan migrate --seed

-npm run build 

-php artisan serve

si vous voulez executer le projet en mode dev utiliser npm run dev dans un autre terminale


# heroes_backend

Ce dossier est le backend du projet Heroes

C'est un projet d'affichage d'informations à partir d'une base de données.

Pour pouvoir utiliser ce projet il faut avoir télécharger préalablement NodeJS,Postman et MongoDB.

# Utilisation sans le frontend

Utiliser ce projet sans le frontend necéssite Postman afin de tester les différentes routes.

En haut du fichier ce trouve les données à insérer dans une collection que vous nommerez heroes en suivant le modèle dans le fichier models

# Routes

GET - Afficher la liste des héros "/heroes"

GET - Afficher un héros de la liste "/heroes/:name"

POST - Ajouter de nouveaux héros "/heroes"

PATCH - Ajouter de nouveaux pouvoirs aux héros "/heroes/:id" ( les id sont créer par la base de données à l'ajout d'un document )

DELETE - Snap un héros "/heroes/:id"

GET - Rechercher les pouvoirs d'un héros "/heroes/:name/powers"

Voici la liste des routes accéssibles à ce jour

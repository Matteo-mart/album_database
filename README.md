Ce projet est la suite logique ou le moteur de données de ton API HTTP. En BTS SIO, il est crucial de montrer que tu maîtrises la persistance des données et la communication avec un SGBD (Système de Gestion de Base de Données) via un langage de programmation.

Voici une proposition de README pour album_database :
🗄️ Projet : album_database (Data Management en Go)
## Présentation du projet

album_database est un module backend développé en Go spécialisé dans la gestion et la persistance des données au sein d'une base de données relationnelle.

Ce projet sert de fondation de données pour une application de gestion de catalogue musical. Il implémente la logique d'accès aux données (DAL) et assure l'intégrité des échanges entre le code applicatif et le serveur SQL.
## Fonctionnalités

    Connexion SGBD : Gestion des drivers de connexion à une base de données SQL.

    Requêtage CRUD : Implémentation des requêtes de sélection, d'insertion et de mise à jour.

    Gestion du typage : Utilisation de structures Go pour mapper les résultats des requêtes SQL vers des objets manipulables par l'application.

## Compétences SIO (SLAM) validées

    B1.1 - Gérer le patrimoine informatique : Organisation des scripts de données et des archives de sauvegarde (album.zip).

    Conception de base de données : Compréhension du schéma relationnel nécessaire au stockage des albums (titre, artiste, prix, etc.).

    Développement logiciel : Maîtrise de la bibliothèque standard database/sql de Go.

## Structure du dépôt
    Fichier / Dossier	Rôle
    /album	Contient les sources Go pour la gestion de la base de données.
    album.zip	Archive de sauvegarde contenant probablement les scripts SQL ou une version exportée de la base.
## Utilisation
### Pré-requis

    Une base de données SQL (MySQL ou MariaDB par exemple) installée et configurée.

    Go installé sur votre environnement de développement.

### Lancer le module

    Une fois vos variables d'environnement configurées (User, Password, Host), vous pouvez tester la connexion et les requêtes :
      Bash

      cd album
      go run .

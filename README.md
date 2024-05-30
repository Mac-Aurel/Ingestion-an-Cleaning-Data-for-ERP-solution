Ingestion et Nettoyage de Données pour Solution ERP
Description

Ce projet fournit une solution d'ingestion et de nettoyage de données pour une solution ERP, visant à garantir la qualité et la fiabilité des données utilisées dans le système. Il comprend les fonctionnalités suivantes :
Fonctionnalités

    Conversion des fichiers XML en type de données cElementTree.
    Identification automatique des attributs et des types de données des relations de base de données.
    Système de gestion des pannes pour éviter la perte de données (Rollback et Checkpoint).
    Nettoyage et ingestion des données analysées dans une base de données PostgreSQL.

Instructions d'exécution

    Préparation des données :
        Mettre à jour le fichier data.txt avec les informations nécessaires.
        Créer un dossier data (ou utiliser un autre nom) et placer les fichiers XML à ingérer dans ce dossier.

    Exécution du script :
        Exécuter le script main.py pour lancer le processus d'ingestion et de nettoyage des données.

    Création de nouvelles relations :
        Mettre à jour les noms des relations et les clés primaires dans le script selon les besoins.
        Les autres attributs et relations seront automatiquement créés en fonction des fichiers XML d'entrée.

Avertissement

Assurez-vous de suivre les instructions avec précaution pour éviter toute perte de données ou erreurs lors de l'exécution du script.

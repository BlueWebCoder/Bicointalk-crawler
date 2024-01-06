# README du Projet Bitcointalk Crawler

Ce projet est un web crawler en Python pour extraire des données du forum Bitcointalk. Il utilise plusieurs bibliothèques Python et crée des fichiers et des bases de données pour stocker les données collectées.

## Installation des Bibliothèques

Avant d'exécuter le script, assurez-vous d'installer les bibliothèques Python nécessaires en utilisant les commandes shell suivantes :

- `cfscrape` : Une bibliothèque pour contourner la protection anti-bot des sites web.
    ```
    pip install cfscrape
    ```

- `BeautifulSoup` : Une bibliothèque d'analyse HTML et XML.
    ```
    pip install beautifulsoup4
    ```

- `dataset` : Une bibliothèque pour interagir avec des bases de données SQL.
    ```
    pip install dataset
    ```

## Fichiers Créés

Le script crée plusieurs fichiers pour stocker les données extraites :

- `database.db` : Une base de données SQLite pour stocker les données des fils de discussion.
- `database_tokens.db` : Une base de données SQLite séparée pour stocker les données des fils de discussion liés aux tokens.
- Fichiers texte pour les mois en cours :
    - `january.txt` : Fichier texte pour stocker les données des fils de discussion du mois de janvier.
    - `january_tokens.txt` : Fichier texte pour stocker les données des fils de discussion liés aux tokens du mois de janvier.
    - Vous devrez créer manuellement ces fichiers pour le mois en cours, puis les exécuter.

## Exécution du Script

Pour exécuter le script, suivez ces étapes :

1. Assurez-vous d'avoir installé les bibliothèques requises comme indiqué ci-dessus.

2. Créez manuellement les fichiers texte pour le mois en cours comme mentionné ci-dessus.

3. Lancez le script Python principal en utilisant la commande shell suivante :
   
```sh
python bitcointalk_month_annoncement.py
```




Le script commencera à collecter des données à partir du forum Bitcointalk et les stockera dans les bases de données et les fichiers texte appropriés.

N'oubliez pas de personnaliser le script en fonction de vos besoins spécifiques et d'adapter les noms de fichiers et les bases de données si nécessaire.



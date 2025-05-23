# Web Scraping des Annonces Immobilières

Ce projet consiste à extraire des informations sur les annonces de location immobilières dans les villes de Rabat et Marrakech à partir de deux sites web : [RabatImmo.ma](https://rabatimmo.ma/) et [Sarouty.ma](https://www.sarouty.ma/). Le script utilise **Selenium** pour naviguer sur les pages et charger dynamiquement le contenu, ainsi que **BeautifulSoup** pour analyser le HTML et extraire les informations pertinentes.

## Fonctionnalités

- **Extraction des données** : Le script récupère les informations suivantes pour chaque annonce :
  - Titre de l'annonce
  - Prix
  - Adresse (si disponible)
  - Nombre de chambres
  - Nombre de salles de bains
  - Surface
  - Lien de l'annonce

- **Fusion des données** : Les données extraites des deux sites sont fusionnées et enregistrées dans un fichier JSON.

- **Visualisation des données** : Les données peuvent être visualisées sous forme de tableau en utilisant **Pandas** ou via une interface web en utilisant **Flask**.

## Prérequis

Avant de lancer le script, assurez-vous d'avoir installé les bibliothèques nécessaires :

```bash
pip install selenium beautifulsoup4 flask pandas
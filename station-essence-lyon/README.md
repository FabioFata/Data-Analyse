Station essence Lyon project
#  Analyse des prix des stations-essence à Lyon

Ce projet est une **étude de cas data** réalisée dans le cadre d’une formation en Data Analytics (Cartel de la Data).  
L’objectif était de répondre à la question suivante :

> **Quelle est la station-essence la moins chère autour de Lyon ?**

Ce cas m’a permis d’appliquer une méthodologie data complète : collecte, préparation, analyse, visualisation et interprétation des résultats.

---

##  Objectifs du projet

- Extraire et structurer les données des prix des carburants.
- Nettoyer et filtrer les données pour la zone lyonnaise.
- Construire des métriques pertinentes (prix moyens, écarts, distributions).
- Visualiser les résultats dans un tableau de bord interactif.
- Identifier les stations les plus économiques.

---

## Données

Les données proviennent d’un jeu de données public sur les prix des carburants en France (Open Data).  
Elles comprennent notamment :

- Identifiant de la station
- Coordonnées géographiques (latitude/longitude)
- Types de carburants
- Prix observés selon la date et l’heure

Un **échantillon des données nettoyées** est disponible dans le dossier `data/cleaned/`.

---

## Méthodologie

### 1. Collecte et nettoyage

- Import des données d’origine (CSV)  
- Filtrage des observations pour l’aire urbaine de Lyon  
- Traitement des valeurs manquantes  
- Formatage des champs date / prix

### 2. Analyse

- Calcul des prix moyens par station
- Classement des stations par carburant
- Détection des outliers et des variations temporelles

### 3. Visualisation

Le dashboard interactif a été construit avec **Looker Studio**.  
Il permet :
- de comparer les stations selon différents critères
- de visualiser les zones les moins chères

---

## Outils utilisés

- **BigQuery** (SQL) pour l’interrogation des données et les transformations.
- **Looker Studio** pour la visualisation interactive.
- Fichiers `.sql` versionnés pour garder l’historique des requêtes.

---


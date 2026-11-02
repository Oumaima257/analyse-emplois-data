# Analyse des salaires dans les métiers de la data

Projet d'analyse de données réalisé avec Python (pandas, Matplotlib, Seaborn) sur Google Colab.

## Objectif

Répondre à la question : **quels facteurs influencent le salaire dans les métiers de la data ?** (niveau d'expérience, métier, pays, télétravail)

## Données

- **Source :** dataset Kaggle « Data Science Job Salaries »
- **Taille :** 607 offres, 12 colonnes
- **Colonnes principales :** niveau d'expérience, type de contrat, intitulé du poste, salaire en USD, pays de l'entreprise, taux de télétravail, taille de l'entreprise
- **Qualité :** aucune valeur manquante, aucun doublon

## Méthode

1. **Chargement** des données avec pandas
2. **Nettoyage** : suppression de la colonne d'index inutile, remplacement des codes (EN, MI, SE, EX...) par des libellés lisibles
3. **Analyse** : moyennes de salaires par niveau d'expérience, métier et pays, répartition du télétravail
4. **Visualisation** : graphiques en barres avec Seaborn et Matplotlib

## Résultats clés

1. **L'expérience fait fortement augmenter le salaire** : environ 60 000 USD en moyenne pour les débutants contre environ 200 000 USD pour la direction. Le groupe « Direction » compte peu de profils (N = À REMPLIR), sa moyenne est donc moins fiable.
2. **Métiers les mieux payés** : À REMPLIR (métier 1), À REMPLIR (métier 2) et À REMPLIR (métier 3) arrivent en tête (métiers avec au moins 5 offres).
3. **Le télétravail domine** : 381 offres sur 607 (63 %) sont en full remote, 127 (21 %) sur site et 99 (16 %) en hybride.
4. **Écarts entre pays** : À REMPLIR (pays 1) affiche le salaire moyen le plus élevé (À REMPLIR USD), contre À REMPLIR USD pour À REMPLIR (pays 2) (pays avec au moins 10 offres).

## Graphiques

![Salaire moyen selon le niveau d'expérience](images/salaire_experience.png)

## Limites

- Le dataset est de taille modeste (607 offres) et couvre surtout 2020 à 2022, une période marquée par la pandémie : la part de télétravail n'est peut-être pas représentative d'aujourd'hui.
- Certains groupes (direction, certains pays) comptent peu d'observations, donc leurs moyennes sont peu fiables.
- Les salaires sont convertis en USD sans tenir compte du coût de la vie dans chaque pays.
- Une corrélation n'est pas une causalité : cette analyse décrit les données, elle n'explique pas les causes.

## Pistes d'amélioration

- Ajouter des requêtes SQL pour interroger les données
- Construire un petit dashboard interactif avec Streamlit
- Tester un modèle simple de prédiction de salaire

## Lancer le projet

1. Ouvrir `analyse.ipynb` dans Google Colab
2. Importer `data/ds_salaries.csv`
3. Exécuter les cellules dans l'ordre

## Auteure

Oumaima, [LinkedIn](https://www.linkedin.com/in/oumaima-abdellatif-265105387)

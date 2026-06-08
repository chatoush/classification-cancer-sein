# Classification du Cancer du Sein

Ce projet utilise des techniques de Machine Learning pour classifier des tumeurs du sein en deux catégories : bénignes ou malignes, à partir du dataset Breast Cancer fourni par Scikit-Learn.

## Fonctionnalités et objectifs

- Analyse exploratoire des données (EDA)
- Visualisation de la distribution des variables
- Étude des corrélations entre les caractéristiques
- Préparation des données
- Création d'un pipeline avec normalisation et régression logistique
- Validation croisée des performances
- Évaluation à l'aide de plusieurs métriques
- Comparaison entre la Régression Logistique et Random Forest

## Technologies utilisées

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Résultats

La régression logistique a obtenu une accuracy d'environ 98 % sur les données de test avec seulement deux erreurs de classification.

Une comparaison avec Random Forest a également été réalisée. Sur ce dataset, la régression logistique a obtenu de meilleures performances globales que Random Forest.

## Apprentissages

Ce projet m'a permis de mieux comprendre :

- l'analyse exploratoire des données (EDA)
- les pipelines Scikit-Learn
- la normalisation des données
- la validation croisée
- les métriques de classification (accuracy, precision, recall et F1-score)
- l'interprétation d'une matrice de confusion

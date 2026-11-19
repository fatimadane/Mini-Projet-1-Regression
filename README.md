# Mini-Projet-1-Regression
Prétraitement des données et prédiction de la résistance du béton avec Ridge et SVR.


## Présentation du projet

Ce mini-projet a pour objectif de prédire la résistance à la compression du béton (Concrete Compressive Strength) à partir de ses différentes caractéristiques.

## Dataset

Le dataset utilisé est **Concrete_Data.xls**.

Il contient :
- 1030 observations.
- 8 variables explicatives (Features).
- 1 variable cible (Target) : Concrete Compressive Strength (MPa).

## Prétraitement des données

Les étapes de prétraitement comprennent :
- Exploration du dataset.
- Vérification et suppression des doublons.
- Séparation des variables explicatives (X) et de la variable cible (y).
- Division des données en ensembles d'entraînement et de test.
- Standardisation des variables numériques.

## Modèles étudiés

- Ridge Regression
- Support Vector Regression (SVR) avec noyau linéaire.
- Support Vector Regression (SVR) avec noyau RBF.

## Outils utilisés

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Objectif final

Comparer les performances des modèles de régression et évaluer leur capacité à prédire la résistance à la compression du béton.

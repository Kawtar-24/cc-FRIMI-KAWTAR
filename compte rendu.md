# Rapport d'Analyse -- Credit Scoring

## 1. Introduction

Le credit scoring est une méthode statistique utilisée pour prédire la
probabilité qu'un client fasse défaut sur un crédit. Cette étude vise à
analyser un jeu de données de crédit, à construire des modèles
prédictifs et à identifier les variables influençant le risque de
défaut.

## 2. Description du Jeu de Données

Le jeu de données contient : - Des variables numériques et catégorielles
concernant les clients. - Une variable cible binaire : **1 = défaut**,
**0 = bon payeur**.

Les étapes suivantes ont été suivies : - Inspection des colonnes, -
Analyse des valeurs manquantes, - Détection du déséquilibre de classes.

## 3. Prétraitement des Données

Les actions réalisées sont : - Imputation des valeurs manquantes
(médians pour numériques, mode pour catégorielles), - Encodage des
variables catégorielles (One-Hot Encoding), - Normalisation des
variables numériques, - Gestion du déséquilibre via **SMOTE**.

## 4. Modélisation

Les modèles suivants ont été testés : - Régression Logistique, - Random
Forest, - XGBoost.

Chaque modèle a été évalué par : - AUC ROC, - AUC PR, - Matrice de
confusion, - Rapport de classification.

## 5. Résultats

Les performances montrent que les modèles d'ensemble (Random Forest /
XGBoost) offrent généralement une meilleure capacité prédictive.

Les éléments évalués : - Courbes ROC, - Courbes Precision-Recall, -
Importance des variables, - Calibration des probabilités.

## 6. Visualisations Générées

Les figures produites (dans le notebook Colab) incluent : - Distribution
de la variable cible, - ROC curves, - PR curves, - Feature importance, -
Calibration plot.

## 7. Conclusion

Le modèle obtenu peut être utilisé en production pour estimer la
probabilité de défaut des clients.\
Il est recommandé de : - Surveiller la dérive des données dans le
temps, - Optimiser les seuils de décision selon les coûts métiers, -
Documenter et versionner les modèles.

## 8. Annexes

Ce rapport a été généré automatiquement depuis le code exécuté dans
Google Colab.

# Rapport d'analyse --- Accidental deaths in USA (monthly)

## 1. Introduction

Ce rapport présente l'analyse de la série temporelle des décès
accidentels mensuels aux États-Unis entre 1973 et 1978.\
L'objectif est de comprendre la tendance, la saisonnalité et les
variations de cette série.

## 2. Structure du fichier

Le fichier contient : - Une colonne de dates mensuelles, - Une colonne
indiquant le nombre de décès accidentels chaque mois.

## 3. Méthodologie

Les étapes incluent : - Nettoyage et mise en forme de la série
temporelle, - Statistiques descriptives, - Visualisation de la série, -
Moyennes mobiles, - Décomposition de la série, - Analyse ACF/PACF, -
Heatmap année × mois.

## 4. Résultats principaux

Des graphiques ont été générés : - Série temporelle, - Moyennes
mobiles, - Décomposition additive et multiplicative, - ACF, - PACF, -
Heatmap année-mois.

## 5. Conclusion

La série montre une saisonnalité marquée et une dynamique régulière.\
Cette analyse peut servir de base à la modélisation (ARIMA, SARIMA).

## 6. Fichiers complémentaires

Dans l'analyse Google Colab, les fichiers suivants sont générés : -
`time_series.png` - `moving_averages.png` - `acf.png` - `pacf.png` -
`decompose_additive.png` (si possible) - `year_month_heatmap.png`

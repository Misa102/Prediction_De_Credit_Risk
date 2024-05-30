# Prédiction du Risque de Crédit

Ce projet vise à développer un modèle de prédiction du risque de crédit des clients qui demandent un prêt à une banque. Le modèle utilise des données démographiques et financières des clients pour prédire s'ils présenteront un risque de défaut de paiement sur leur prêt.

## 1. Introduction

L'objectif principal de ce projet est de créer un modèle de machine learning capable de classer le risque de crédit des demandeurs de prêt en fonction de diverses caractéristiques telles que l'âge, le revenu, le type de propriété, la durée de l'emploi, etc. Nous utilisons la régression logistique comme modèle de classification.

## 2. Exploratory Data Analysis (EDA)

Dans cette phase, nous explorons les données pour comprendre leur structure et leur distribution. Nous analysons les caractéristiques et effectuons des visualisations pour identifier les tendances et les relations entre les variables. Nous nettoyons également les données en supprimant les valeurs manquantes, les doublons et les valeurs aberrantes.

## 3. Preprocessing des Données

Nous prétraitons les données en mettant à l'échelle les caractéristiques numériques et en encodant les variables catégorielles. Nous utilisons également l'analyse en composantes principales (PCA) pour réduire la dimensionnalité des données et sélectionner les variables les plus informatives.

## 4. Entraînement du Modèle

Nous divisons les données en ensembles de formation et de test, puis équilibrons les données en utilisant des techniques de sur-échantillonnage (SMOTE) pour gérer le déséquilibre de classe. Ensuite, nous entraînons un modèle de régression logistique en utilisant TensorFlow/Keras.

## 5. Évaluation du Modèle

Nous évaluons la performance du modèle en calculant l'exactitude (accuracy), l'aire sous la courbe ROC (AUC), et le score F1. Nous utilisons également des métriques telles que la matrice de confusion pour évaluer la capacité du modèle à prédire correctement les classes positives et négatives.

## Résultats

Le modèle de régression logistique a obtenu une précision de 84% sur l'ensemble de test, avec une AUC de 0.84 et un score F1 de 0.586. Ces résultats indiquent une performance solide du modèle dans la prédiction du risque de crédit.

## Résumé

Ce projet démontre l'utilisation de techniques de machine learning pour prédire le risque de crédit des clients. Il met en évidence l'importance de l'analyse exploratoire des données, du prétraitement des données et de l'évaluation du modèle pour obtenir des résultats fiables et précis.

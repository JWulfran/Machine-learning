# 🎯 Segmentation et Clustering de Clients avec Python

## Ce projet propose une approche complète de la **segmentation de clientèle** à l’aide de techniques d’**apprentissage non supervisé**. L’objectif est d’identifier des groupes de clients distincts à partir de données comportementales et démographiques, afin d’optimiser les stratégies marketing.

## 📌 Objectifs

- Segmenter la base de clients pour des actions marketing ciblées.
- Appliquer des algorithmes de clustering comme **K-Means** et le **clustering hiérarchique**.
- Extraire des insights exploitables à partir des clusters identifiés.

---

## 🧰 Technologies utilisées

- **Python** (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- **Jupyter Notebook** pour l’analyse exploratoire et la modélisation
- **K-Means**, **clustering agglomératif**, **dendrogrammes**
- **PCA** (Analyse en Composantes Principales) pour la visualisation

---

## 📈 Étapes du projet

1. **Prétraitement des données**

   - Gestion des valeurs manquantes
   - Encodage des variables catégorielles
   - Normalisation des variables

2. **Analyse exploratoire (EDA)**

   - Statistiques descriptives
   - Visualisations univariées et bivariées

3. **Clustering**

   - Méthode du coude et score de silhouette pour le choix du k optimal
   - Application de K-Means et du clustering hiérarchique

4. **Recommandations métier**
   - Profilage des segments
   - Idées d’actions marketing personnalisées

---

## 📊 Résultats clés

- Identification de groupes de clients aux comportements distincts (ex : gros dépensiers, clients fidèles, sensibles aux promotions).
- Illustration de la valeur stratégique de la segmentation pour le ciblage commercial.

---

## 🧠 Ce que j’ai appris

- Implémenter des algorithmes de clustering dans un contexte réel.
- Préparer des données efficacement pour l’apprentissage non supervisé.
- Traduire des résultats techniques en recommandations business concrètes.

---

📂 _Ce projet fait partie de mon portfolio en science des données et apprentissage automatique. N'hésitez pas à le cloner, à l'explorer ou à proposer des améliorations !_

# 🏡 Prédiction de Prix Immobiliers avec Machine Learning (Python)

Ce projet vise à prédire les prix de logements à partir de caractéristiques structurées (surface, nombre de pièces, année de construction, etc.) en utilisant des algorithmes de **machine learning supervisé**.

🔗 **Notebook GitHub** : [Housing_price_prédiction.ipynb](https://github.com/JWulfran/Machine-learning/blob/ae4d989558ffc296eefa2335d8cb53f767d12653/Housing_price_pr%C3%A9diction.ipynb)

---

## 📌 Objectifs du projet

- Explorer un jeu de données sur l’immobilier
- Mettre en œuvre des modèles de régression pour estimer le prix des maisons
- Comparer les performances de différents algorithmes
- Améliorer les prédictions avec de l’optimisation de modèle et de la sélection de variables

---

[Housing Price Prédiction](Housing_price_prédiction_pic.png)

---

## 🧰 Technologies et outils utilisés

- **Python** (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- **Jupyter Notebook** pour l’analyse interactive
- Algorithmes :
  - Régression Linéaire
  - Régression Ridge/Lasso
  - Arbres de Décision et Random Forest
- Évaluation via **RMSE**, **MAE**, **R²**

---

## 🔍 Étapes du projet

1. **Chargement et préparation des données**

   - Nettoyage, gestion des valeurs manquantes
   - Encodage des variables catégorielles
   - Standardisation

2. **Analyse exploratoire**

   - Visualisations : corrélations, distributions, outliers
   - Sélection de variables pertinentes

3. **Modélisation**

   - Entraînement de plusieurs modèles
   - Évaluation des performances avec validation croisée

4. **Optimisation**

   - Réglage d’hyperparamètres (GridSearchCV)
   - Réduction du surapprentissage

5. **Résultats finaux**
   - Comparaison des modèles
   - Interprétation des prédictions

---

## 📊 Résultats

- Le modèle **Random Forest Regressor** a fourni les meilleures performances sur les données de test avec un bon équilibre biais/variance.
- Visualisation des écarts entre prédiction et valeur réelle pour mieux interpréter les erreurs.

---

## 🧠 Ce que j’ai appris

- Préparer un dataset réel pour des modèles de régression
- Comparer et évaluer plusieurs approches de modélisation
- Appliquer la validation croisée pour éviter le surapprentissage
- Valoriser un projet de data science orienté business (immobilier)

---

📂 _Ce projet fait partie de mon portfolio en science des données. Il illustre ma capacité à transformer des données en insights prédictifs avec une approche rigoureuse et reproductible._

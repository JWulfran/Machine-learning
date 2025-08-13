# 🌳 Classification avec Arbre de Décision - Python

Ce projet présente une application pratique des **arbres de décision** pour résoudre un problème de classification supervisée. Il permet de visualiser les décisions prises par l’algorithme à travers un graphe arborescent et d’analyser les performances du modèle.

🔗 **Notebook GitHub** : [Classification_tree.ipynb](https://github.com/JWulfran/Machine-learning/blob/115f7806111e91004a1b0b3f92fd9771cf98c8bc/Classification_tree.ipynb)

---

## 🎯 Objectifs

- Comprendre le fonctionnement des **arbres de décision**
- Implémenter un modèle de classification sur un jeu de données
- Visualiser la structure de l’arbre
- Évaluer les performances du modèle avec des métriques classiques

---

## 🧰 Technologies utilisées

- **Python**
  - `pandas`, `numpy` pour la manipulation des données
  - `scikit-learn` pour la modélisation (DecisionTreeClassifier)
  - `matplotlib`, `seaborn` pour la visualisation
  - `graphviz` ou `plot_tree` pour l’arbre

---

## 🧪 Étapes du projet

1. **Chargement et préparation des données**
   - Nettoyage, encodage des variables
2. **Construction du modèle**
   - Utilisation de `DecisionTreeClassifier` de scikit-learn
   - Séparation entraînement/test
3. **Visualisation**
   - Affichage graphique de l’arbre de décision
   - Analyse des nœuds et des critères de découpe
4. **Évaluation**
   - Accuracy, matrice de confusion, classification report

---

## 📊 Résultats

- Le modèle est **interprétable et visuel**, ce qui en fait un bon outil pour l’explication métier.
- Les performances varient selon les paramètres comme la profondeur maximale.
- Permet d’identifier rapidement les **variables les plus discriminantes**.

---

## 🧠 Ce que j’ai appris

- Utiliser les arbres de décision pour classer des données tabulaires
- Visualiser et interpréter les règles de classification
- Comparer les performances selon les réglages de l’arbre
- Valoriser la simplicité et l’interprétabilité des modèles ML

---

📂 _Ce projet s’inscrit dans ma démarche d’apprentissage du machine learning et de la visualisation explicative des modèles supervisés._

---

# 👟 Classification avec k-Nearest Neighbors (KNN) - Python

Ce projet met en œuvre l’algorithme **KNN (k plus proches voisins)** pour résoudre un problème de **classification supervisée**. Il explore l’effet du paramètre `k` sur les performances du modèle, ainsi que la visualisation des frontières de décision.

🔗 **Notebook GitHub** : [KNN.ipynb](https://github.com/JWulfran/Machine-learning/blob/115f7806111e91004a1b0b3f92fd9771cf98c8bc/KNN.ipynb)

---

## 🎯 Objectifs

- Implémenter et comprendre l’algorithme **KNN**
- Étudier l’impact du nombre de voisins (`k`) sur la performance
- Visualiser les **zones de classification**
- Comparer les résultats avec d’autres algorithmes

---

## 🧰 Technologies utilisées

- **Python**
  - `pandas`, `numpy` pour la manipulation des données
  - `scikit-learn` pour l’algorithme KNN et les métriques
  - `matplotlib`, `seaborn` pour les visualisations

---

## 🧪 Étapes du projet

1. **Chargement et préparation des données**

   - Normalisation ou standardisation (important pour KNN)
   - Séparation en jeu d’entraînement/test

2. **Entraînement du modèle**

   - Utilisation de `KNeighborsClassifier` (Scikit-learn)
   - Sélection du meilleur `k` via validation croisée ou test empirique

3. **Évaluation**
   - Matrice de confusion
   - Score d’exactitude (`accuracy`)
   - Visualisation des frontières de décision

---

## 📊 Résultats

- Les performances varient fortement en fonction de la **valeur de `k`**.
- Visualisations très intuitives pour **comprendre la structure des données**.
- Le KNN est **sensible aux dimensions**, ce qui le rend plus adapté aux petits jeux de données.

---

## 🧠 Ce que j’ai appris

- Appliquer et interpréter un modèle de classification KNN
- Importance de la mise à l’échelle des données pour les algorithmes basés sur la distance
- Utiliser les visualisations pour analyser les erreurs de classification
- Choisir des hyperparamètres via expérimentation

---

📂 _Ce projet fait partie de mon portfolio d’apprentissage machine. Il illustre l’utilisation de KNN pour des problèmes de classification simples avec une forte composante visuelle._

---

# 🧠 Réseaux de Neurones (NN, MLP, CNN, Transfer Learning) avec Python

Ce projet présente une exploration comparative de différents types de **réseaux de neurones profonds** appliqués à la classification d’images. L’étude couvre les **réseaux de neurones simples (NN)**, **les perceptrons multicouches (MLP)**, **les réseaux de neurones convolutifs (CNN)** ainsi que le **transfer learning** à l’aide de modèles pré-entraînés.

🔗 **Notebook GitHub** : [NN_MLP_CNN_Transfert_learning.ipynb](https://github.com/JWulfran/Machine-learning/blob/115f7806111e91004a1b0b3f92fd9771cf98c8bc/NN_MLP_CNN_Transfert_learning.ipynb)

---

## 🎯 Objectifs

- Comprendre le fonctionnement et les différences entre NN, MLP et CNN
- Implémenter un pipeline de classification d’images
- Utiliser des modèles pré-entraînés pour améliorer la précision (transfer learning)
- Comparer les performances de chaque modèle

---

## 🛠️ Technologies utilisées

- **Python** : NumPy, Pandas
- **TensorFlow / Keras** : pour la modélisation des réseaux de neurones
- **Matplotlib / Seaborn** : visualisation des courbes d’apprentissage
- **Scikit-learn** : métriques d’évaluation

---

## 🧪 Méthodologie

1. **Chargement et prétraitement des données**
   - Redimensionnement, normalisation, encodage
2. **Modélisation**
   - Construction de réseaux NN, MLP, CNN
   - Application de **transfer learning** avec un modèle tel que **VGG16** ou **MobileNet**
3. **Entraînement**
   - Suivi des performances sur données de validation
4. **Évaluation**
   - Matrice de confusion, courbe de perte, précision
5. **Comparaison des résultats**
   - Analyse des performances en fonction de la complexité des modèles

---

## 📊 Résultats

- Les **CNN** surpassent largement les NN et MLP sur les images grâce à l’extraction de caractéristiques spatiales.
- Le **transfer learning** permet une **amélioration significative de la précision**, même avec peu de données.
- Visualisation des performances via **accuracy**, **loss**, et **matrices de confusion**.

---

## 🧠 Ce que j’ai appris

- Conception et entraînement de modèles de deep learning
- Avantages du transfer learning dans les tâches de vision par ordinateur
- Importance du prétraitement pour de bonnes performances
- Analyse des résultats pour guider le choix des architectures

---

📂 _Ce projet fait partie de mon portfolio data science et deep learning. Il démontre ma capacité à mettre en œuvre des solutions d’IA pour la classification d’images avec rigueur et clarté._

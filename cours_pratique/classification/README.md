# Projet : Classification des Fleurs Iris avec Python

Ce projet explore la construction d'un **model de classification** pour prédire l'espèce des fleurs dans le dataset **Iris** en utilisant **supervised learning**.

---

## Objectifs

- 🧠 Comprendre les étapes clés d'un projet de **machine learning**.
- 🔍 Explorer et analyser un dataset.
- ⚙️ Construire et évaluer un modèle de classification simple.
- 📊 Visualiser les performances pour en tirer des conclusions.

---

## Contenu du projet

### 1. **Description des données**

Le dataset **Iris** contient trois classes de fleurs :

- 🌸 **Iris-setosa**
- 🌺 **Iris-versicolor**
- 🌼 **Iris-virginica**

Chaque fleur est caractérisée par :

- 📏 La **longueur** et la **largeur** des **petals**
- 📏 La **longueur** et la **largeur** des **sepals**

Exemple de données :

| Sepal Length | Sepal Width | Petal Length | Petal Width | Classe          |
| ------------ | ----------- | ------------ | ----------- | --------------- |
| 5.1          | 3.5         | 1.4          | 0.2         | Iris-setosa     |
| 7.0          | 3.2         | 4.7          | 1.4         | Iris-versicolor |
| 6.3          | 3.3         | 6.0          | 2.5         | Iris-virginica  |

---

### 2. **Étapes du projet**

1. **📃 Préparation de l'environnement :**

   - 📦 Importation des **libraries** nécessaires.

2. **🔍 Exploration des données :**

   - 🖥️ Chargement et aperçu des premières lignes.
   - 📊 Visualisation des relations entre les variables à l'aide de **graphs**.

3. **⚙️ Prétraitement des données :**

   - ✂️ Division en **training set** et **test set**.
   - ⚖️ Normalisation des caractéristiques.

4. **🤖 Entraînement du model :**

   - 🌲 Utilisation d'un **Random Forest classifier** pour construire un modèle performant.

5. **📊 Évaluation des performances :**

   - 📄 Génération d'un **classification report**.
   - 🎯 Visualisation d'une **confusion matrix**.

---

## Technologies utilisées

- 🐍 **Python 3.10+**
- **Bibliothèques principales :**
  - `numpy` : 📐 Calcul numérique.
  - `pandas` : 🗂️ Manipulation des données.
  - `matplotlib` & `seaborn` : 🎨 Visualisation des données et résultats.
  - `scikit-learn` : 🧠 Implémentation des algorithmes de machine learning.

---

## Instructions pour exécuter

1. 🖥️ Cloner le dépôt du projet :

   ```bash
   git clone <lien-du-repo>
   ```

2. ⚙️ Créez et activez un environnement virtuel Python :

   ```bash
   python -m venv env
   source env/bin/activate # Sous Linux/Mac
   env\Scripts\activate # Sous Windows
   ```

3. 📦 Installez les dépendances avec :

   ```bash
   pip install -r requirements.txt
   ```

4. ▶️ Lancez le notebook Jupyter ou le script Python :

   ```bash
   jupyter notebook iris_classification.ipynb
   ```

---

## Résultats obtenus

- 📊 **Classification report :**

  - Précision globale et par classe.

- 🎯 **Confusion matrix :**

  - Visualisation des erreurs de classification.

---

## Limites et pistes d'amélioration

- 🔍 **Exploration de modèles alternatifs :** Tester d'autres algorithmes comme SVM ou KNN.
- 📈 **Augmentation des données :** Ajouter des données pour améliorer les performances.
- 🌌 **Scalabilité :** Tester sur des datasets plus volumineux.

---

## Auteur

Thomas Bruand - [LinkedIn](https://www.linkedin.com/in/tbruand/)\
Développeur IA passionné(e) par l'apprentissage automatique et l'analyse des données.

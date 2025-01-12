# Projet : Supervised Learning - Régression Linéaire

Ce projet illustre l'utilisation de la **régression linéaire supervisée** pour prédire le prix d'une maison en fonction de certaines caractéristiques : surface, nombre de pièces et emplacement. 🌟🌍📈

## Objectifs

- Comprendre le concept de la régression supervisée. 🧠
- Entraîner un modèle pour mapper des caractéristiques à une cible connue. 🎯
- Évaluer les performances du modèle en utilisant des métriques standards. 📊
- Visualiser les résultats pour interpréter la qualité du modèle. 🔍

---

## Contenu du projet

### 1. **Création du dataset**

Le dataset contient les caractéristiques suivantes : 🏠📋

- **`Area (m^2)`** : Surface de la maison en m².
- **`Rooms`** : Nombre de pièces.
- **`Location`** : Emplacement codé en 0 (périphérie) et 1 (centre-ville).
- **`Price (€)`** : Prix de la maison en euros (cible à prédire).

Exemple de données :

| Area (m^2) | Rooms | Location | Price (€) |
| ---------- | ----- | -------- | --------- |
| 80         | 2     | 1        | 200,000   |
| 120        | 3     | 0        | 250,000   |
| 60         | 1     | 1        | 150,000   |
| 100        | 3     | 0        | 220,000   |

---

### 2. **Préparation des données**

- Séparation des caractéristiques (**features**) et de la cible (**target**). ✂️🗂️
- Division des données en ensembles d'entraînement et de test (67%-33%). 🧪

### 3. **Modèle**

- Modèle utilisé : **Régression linéaire** (de `scikit-learn`). ⚙️
- Entraînement sur l'ensemble d'entraînement. 🖥️

### 4. **Évaluation du modèle**

- Métriques d'évaluation : 🧮
  - **Erreur quadratique moyenne (MSE)** : Mesure l'erreur moyenne au carré entre les prédictions et les valeurs réelles.
  - **Coefficient de détermination (R²)** : Indique le pourcentage de variance expliqué par le modèle.

### 5. **Visualisation des résultats**

- Diagramme de dispersion des prédictions vs les valeurs réelles pour analyser la précision du modèle. 📊✨

### 6. **Prédiction d'exemple**

- Exemple : Prédire le prix d'une maison de 90 m², avec 2 pièces, située en centre-ville. 🏡📉

---

## Technologies utilisées

- **Python 3.10+** 🐍
- **Bibliothèques** : 📚
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`

---

## Exécution

1. Installez les dépendances avec `pip install -r requirements.txt` (si un fichier `requirements.txt` est créé). ⚙️📦
2. Exécutez le script Python dans un environnement compatible. ▶️💻

---

## Résultats obtenus

- **Coefficients du modèle** : Relation entre les caractéristiques et le prix. 📐
- **Visualisation** : Alignement entre les prédictions et les valeurs réelles. 🎨
- **Exemple de prédiction** : Prédiction du prix pour une maison hypothétique avec des caractéristiques données. 💡

---

## Limites et améliorations

- **Dataset** : Les données sont fictives et limitées en taille. Un dataset plus grand et réel améliorerait la qualité du modèle. 📊
- **Modèle** : Tester des modèles plus avancés (Random Forest, Gradient Boosting). 🚀
- **Caractéristiques** : Ajouter des variables comme l'âge de la maison, la proximité des commodités, etc. 🏗️

---

## Auteur

Thomas Bruand - [LinkedIn](https://www.linkedin.com/in/tbruand/) 💻📚🌟
Développeur IA en formation, passionné par l'apprentissage automatique et l'analyse de données. 💻📚🌟

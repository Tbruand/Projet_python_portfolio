# Projet : Supervised Learning - Classification

Ce projet illustre l'utilisation de la **classification supervisée** pour prédire si un e-mail est un spam ou non en fonction de certaines caractéristiques : présence de mots-clés et longueur du message. 📧🚀

## Objectifs

- Comprendre le concept de la classification supervisée. 🧠
- Entraîner un modèle pour mapper des caractéristiques à une cible connue. 🎯
- Évaluer les performances du modèle avec des métriques standards. 📊
- Visualiser les résultats pour interpréter les prédictions. 🔍

---

## Contenu du projet

### 1. **Création du dataset**

Le dataset contient les caractéristiques suivantes : 📨📋

- **`presence_money_words`** : Indique la présence (1) ou l'absence (0) de mots comme "argent" ou "offre".
- **`message_length`** : Longueur du message en caractères.
- **`is_spam`** : Indique si le message est un spam (1) ou non (0).

Exemple de données :

| presence_money_words | message_length | is_spam |
| -------------------- | -------------- | ------- |
| 1                    | 100            | 1       |
| 0                    | 50             | 0       |
| 1                    | 80             | 1       |
| 0                    | 60             | 0       |
| 1                    | 150            | 1       |

---

### 2. **Préparation des données**

- Séparation des caractéristiques (**features**) et de la cible (**target**). ✂️🗂️
- Division des données en ensembles d'entraînement et de test (75%-25%). 🧪

### 3. **Modèle**

- Modèle utilisé : **Logistic Regression** (de `scikit-learn`). ⚙️
- Entraînement sur l'ensemble d'entraînement. 🖥️

### 4. **Évaluation du modèle**

- Métriques d'évaluation : 🧮
  - **Précision globale (accuracy)** : Pourcentage de prédictions correctes.
  - **Rapport de classification** : Précision, rappel et score F1 pour chaque classe.

### 5. **Visualisation des résultats**

- **Diagramme de dispersion** : Comparaison entre les prédictions et les valeurs réelles pour analyser la qualité des prédictions. 📊✨

### 6. **Prédiction d'exemple**

- Exemple : Prédire si un message de 70 caractères sans mots-clés est un spam ou non. 📩📉

---

## Technologies utilisées

- **Python 3.10+** 🐍
- **Bibliothèques** : 📚
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## Exécution

1. Installez les dépendances avec `pip install -r requirements.txt` (si un fichier `requirements.txt` est créé). ⚙️📦
2. Exécutez le script Python dans un environnement compatible. ▶️💻

---

## Résultats obtenus

- **Précision globale** : Taux de prédictions correctes sur l'ensemble de test. 🎯
- **Visualisation** : Alignement entre les prédictions et les valeurs réelles. 🎨
- **Exemple de prédiction** : Analyse de nouveaux messages pour déterminer s'ils sont des spams. 💡

---

## Limites et améliorations

- **Dataset** : Les données sont fictives et limitées en taille. Un dataset plus grand et réel améliorerait la qualité du modèle. 📊
- **Modèle** : Tester des modèles plus avancés (SVM, Random Forest). 🚀
- **Caractéristiques** : Ajouter des variables comme la fréquence de certains mots ou les métadonnées des e-mails. 📬

---

## Auteur

Thomas Bruand - [LinkedIn](https://www.linkedin.com/in/tbruand/) 💻📚🌟
Développeur IA en formation, passionné par l'apprentissage automatique et l'analyse de données. 💻📚🌟

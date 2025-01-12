# Projet : Réduction de Dimensionnalité - Analyse en Composantes Principales (PCA)

Ce projet explore l'utilisation de techniques de **réduction de dimensionnalité** pour simplifier des ensembles de données tout en préservant leur information principale.

---

## Objectifs

- 🧠 Comprendre l'importance de la réduction de dimensionnalité.
- 🔬 Implémenter et analyser des techniques telles que PCA.
- 📊 Visualiser les résultats pour évaluer la qualité de la réduction.
- 🏭 Identifier les applications pratiques dans le domaine de l'IA et de l'analyse de données.

---

## Contenu du projet

### 1. **Description des données**

- 📃 Les données traitées sont constituées de plusieurs caractéristiques multivariées utilisées pour démontrer l'efficacité de la réduction de dimension.

Exemple de structure de données (simplifiée) :

| Variable 1 | Variable 2 | Variable 3 | ... |
| ---------- | ---------- | ---------- | --- |
| 1.5        | 2.3        | -1.2       | ... |
| 0.7        | 1.8        | -0.8       | ... |
| 1.0        | 2.0        | -0.5       | ... |

---

### 2. **Étapes du projet**

1. **📃 Préparation des données :**

   - ⚖️ Normalisation des caractéristiques pour assurer une pondération égale.
   - 🔍 Analyse descriptive pour identifier les corrélations entre les variables.

2. **🔬 Réduction de dimension :**

   - 🔢 Application de la PCA pour projeter les données dans un espace réduit.
   - 📚 Explication de la variance cumulée pour déterminer le nombre de dimensions à conserver.

3. **📊 Visualisation des résultats :**

   - 🔄 Représentation des données projetées sur les premières composantes principales.
   - 📊 Analyse des contributions des variables dans la nouvelle base.

4. **🚀 Exemples d'applications :**
   - 🌐 Utilisation des données réduites pour la classification ou la segmentation.

---

## Technologies utilisées

- 🐍 **Python 3.10+**
- 📚 **Bibliothèques principales :**
  - `numpy` : 📉 Calcul matriciel et gestion des données.
  - `pandas` : 📂 Manipulation des données.
  - `matplotlib` & `seaborn` : 🎨 Visualisation des résultats.
  - `scikit-learn` : 🌐 Implémentation de la PCA.

---

## Exécution

1. 🔧 Cloner le dépôt du projet : `git clone <lien-du-repo>`.
2. 🚪 Créez et activez un environnement virtuel Python :
   ```bash
   python -m venv env
   source env/bin/activate # Sous Linux/Mac
   env\Scripts\activate # Sous Windows
   ```
3. 📦 Installez les dépendances avec : `pip install -r requirements.txt`.
4. ▶️ Lancez le notebook Jupyter ou le script Python : `jupyter notebook dimensionality_reduction.ipynb`.

---

## Résultats obtenus

- 🔢 **Explication de la variance :** Visualisation de la part de variance capturée par chaque composante principale.
- 🔄 **Projection des données :** Réduction efficace tout en conservant la majorité de l'information.
- 💡 **Applications potentielles :** Amélioration des performances pour les algorithmes d'apprentissage.

---

## Limites et améliorations

- 🔍 **Limites des techniques linéaires :** Tester des approches non linéaires comme t-SNE ou UMAP.
- 📊 **Qualité des données :** Travailler avec des datasets réels pour évaluer la robustesse.
- 🌌 **Scalabilité :** Comparer les performances sur des datasets de très grande taille.

---

## Auteur

👩‍💻 Thomas Bruand - [LinkedIn](https://www.linkedin.com/in/tbruand/)  
Développeur IA en formation, passionné par l'analyse des données et leur visualisation dans le domaine médical et scientifique.

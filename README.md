# 🎗️ Prédiction du cancer du sein avec la Machine à Vecteurs de Support (SVM)

## 📌 Présentation du projet

Ce projet utilise l'algorithme de **Machine à Vecteurs de Support (Support Vector Machine - SVM)** afin de prédire si une tumeur du sein est **bénigne** ou **maligne**.

Le projet couvre toutes les étapes d'un workflow de Machine Learning, depuis le prétraitement des données et l'analyse exploratoire jusqu'à l'entraînement du modèle et l'évaluation de ses performances.

---

## 🎯 Objectifs

- Explorer le jeu de données.
- Nettoyer et prétraiter les données.
- Supprimer les variables inutiles.
- Analyser les corrélations entre les variables.
- Détecter les valeurs aberrantes.
- Normaliser les données avec **StandardScaler**.
- Entraîner un classificateur **SVM**.
- Évaluer les performances du modèle.

---

## 📊 Informations sur le jeu de données

**Nom :** Breast Cancer Wisconsin Dataset

- Nombre d'observations : **569**
- Nombre de variables : **30**

### Variable cible

- **0 :** Tumeur bénigne
- **1 :** Tumeur maligne

---

## 🛠️ Technologies et bibliothèques utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Processus de Machine Learning

1. Chargement du jeu de données
2. Analyse exploratoire des données (EDA)
3. Vérification des valeurs manquantes
4. Vérification des doublons
5. Suppression de la colonne **ID**
6. Encodage de la variable cible
7. Analyse des corrélations
8. Détection des valeurs aberrantes (Boxplot)
9. Division des données en ensembles d'entraînement et de test
10. Normalisation des variables avec **StandardScaler**
11. Entraînement du modèle **SVM**
12. Prédiction des résultats
13. Évaluation des performances du modèle

---

## 📈 Résultats

| Indicateur | Valeur |
|------------|--------:|
| Accuracy | **97 %** |

---
## 📉 Visualisations

### Matrice de corrélation
<img width="1072" height="998" alt="image" src="https://github.com/user-attachments/assets/41efebfb-0cc2-4b2c-9aa0-9391a03d7393" />
 
### Détection des valeurs aberrantes (Boxplot)
<img width="1790" height="790" alt="image" src="https://github.com/user-attachments/assets/72a795bc-86da-45cb-9a88-523c65d8ec57" />

### Matrice de confusion
<img width="572" height="483" alt="image" src="https://github.com/user-attachments/assets/e8136c45-96af-45a6-9e26-748941286ddc" />

---

## 📁 Structure du projet

```text
Breast-Cancer-Prediction-SVM/
│
├── breast_cancer_prediction.ipynb
├── data.csv
├── README.md
├── requirements.txt
└── images/
    ├── boxplot.png
    ├── correlation_matrix.png
    └── confusion_matrix.png
```

---

## 🚀 Améliorations futures

- Optimiser les hyperparamètres avec **GridSearchCV**.
- Comparer les performances du modèle SVM avec d'autres algorithmes de classification.
- Déployer le modèle sous forme d'application web avec **Streamlit**.
- Réaliser une sélection des variables (**Feature Selection**) afin d'améliorer les performances du modèle.

---

## 👩‍💻 Auteur

**Amal El Mouatamad**

Étudiante en Intelligence Artificielle | Data Analyst

ISTA NTIC Rabat

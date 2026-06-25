# 📊 Prédiction de la souscription à un dépôt bancaire par Data Mining

![Python](https://img.shields.io/badge/Python-Data%20Mining-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Statut](https://img.shields.io/badge/Projet-Terminé-success)

---

## 📌 Présentation

Ce projet académique présente une étude de Data Mining consacrée à la prédiction de la souscription d'un client à un dépôt à terme bancaire. À partir d'un jeu de données issu d'une campagne de marketing bancaire, plusieurs modèles de Machine Learning sont développés et comparés afin d'identifier les facteurs influençant la souscription et d'évaluer leurs performances prédictives.

L'objectif est de montrer comment les techniques de Data Mining peuvent améliorer le ciblage des campagnes marketing bancaires.

---

## 🎯 Objectifs

- Construire plusieurs modèles de classification.
- Identifier les facteurs influençant la souscription.
- Comparer les performances des modèles.
- Évaluer la capacité prédictive de chaque approche.

---

## 📂 Jeu de données

- **Source :** UCI Machine Learning Repository
- **Nombre d'observations :** 41 188
- **Nombre de variables :** 21

Le jeu de données décrit les caractéristiques des clients, les interactions commerciales et le contexte macroéconomique d'une campagne de marketing bancaire.

---

## 🛠 Technologies utilisées

- R
- Quarto (.qmd)
- Data Mining
- Régression Logistique
- Random Forest

---

## 🤖 Modèles étudiés

- Régression Logistique
- Random Forest

### Résultats

| Modèle | Accuracy | AUC |
|---------|----------|-----|
| Régression Logistique | 90,82 % | 0,926 |
| Random Forest | 91,14 % | 0,942 |

Le modèle **Random Forest** offre les meilleures performances prédictives grâce à sa capacité à capturer des relations non linéaires et des interactions complexes entre les variables.

---

## 📈 Principaux enseignements

- Le jeu de données présente un fort déséquilibre entre les classes.
- Les variables **duration** et **poutcome** sont parmi les plus influentes.
- La Régression Logistique reste très interprétable.
- Le Random Forest améliore les performances globales.

---

## 📂 Contenu du dépôt

- `projet.qmd` : code source Quarto
- `projet_definitif.pdf` : rapport complet
- `bank-additional-full.csv` : jeu de données (si présent)

---

## 📚 Source des données

UCI Machine Learning Repository

https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

---

## 👨‍💻 Auteur

**Mamadou Pathe DIALLO**

Master 2 Études Économiques et Statistiques

Data Analyst | Data Mining | Machine Learning

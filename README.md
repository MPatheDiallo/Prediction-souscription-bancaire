# 🗺️ Analyse spatiale de l'innovation régionale en Europe

![R](https://img.shields.io/badge/R-4.x-blue)
![Spatial Analysis](https://img.shields.io/badge/Spatial%20Analysis-GIS-success)
![Quarto](https://img.shields.io/badge/Quarto-Project-blueviolet)
![Eurostat](https://img.shields.io/badge/Data-Eurostat-orange)

---

# 📌 Présentation

Ce projet académique porte sur l'analyse spatiale des disparités régionales en matière d'innovation au sein de l'Europe à partir des données **NUTS (Nomenclature of Territorial Units for Statistics)**.

L'étude mobilise des données économiques, démographiques et technologiques afin d'explorer les relations entre les dépenses en Recherche & Développement (R&D), le nombre de brevets, le PIB régional, le PIB par habitant et le capital humain.

L'objectif est de mettre en évidence les facteurs associés aux performances régionales en matière d'innovation grâce à des analyses statistiques et cartographiques.

---

# 🎯 Objectifs

- Nettoyer et préparer les données régionales NUTS.
- Réaliser une analyse statistique descriptive.
- Étudier les distributions des principales variables économiques.
- Analyser l'évolution temporelle des brevets.
- Produire des cartes thématiques.
- Explorer les relations entre innovation, R&D et richesse régionale.

---

# 📂 Jeu de données

**Source : Eurostat**

- Régions européennes (NUTS)
- 3 924 observations
- Variables économiques, démographiques et d'innovation

---

# 🛠 Technologies utilisées

- R
- Quarto (.qmd)
- sf
- mapsf
- ggplot2
- dplyr
- tidyverse

---

# 📊 Analyse exploratoire

Les analyses mettent en évidence une forte hétérogénéité des territoires européens concernant les dépenses de R&D et la production de brevets.

## Distribution des dépenses de R&D

![Distribution RD](images/rd_distribution.png)

La distribution est fortement asymétrique, traduisant une concentration des investissements en R&D dans un nombre limité de régions européennes.

---

## Évolution du nombre de brevets (1995–2012)

![Evolution brevets](images/patents_evolution.png)

L'évolution temporelle montre une progression globale de l'activité d'innovation, malgré des disparités importantes entre les territoires.

---

# 🗺️ Analyse spatiale

## Nombre de brevets par région française

![Carte Brevets](images/patents_france.png)

Les régions les plus industrialisées concentrent une part importante des dépôts de brevets.

---

## Dépenses de Recherche & Développement

![Carte RD](images/rd_france.png)

Les investissements en R&D présentent une forte concentration géographique, notamment autour des principaux pôles économiques.

---

## PIB par habitant

![Carte PIB](images/gdp_france.png)

Le PIB par habitant révèle des écarts significatifs entre les régions françaises, mettant en évidence des niveaux de développement économique contrastés.

---

## Innovation et richesse régionale

![PIB et Brevets](images/gdp_patents.png)

Cette analyse met en évidence une relation positive entre le niveau de richesse des régions et leur capacité d'innovation, mesurée par le nombre de brevets.

---

# 📈 Principaux résultats

- Forte concentration spatiale des dépenses de R&D.
- Les régions les plus développées économiquement concentrent également le plus grand nombre de brevets.
- Des disparités territoriales importantes existent en matière d'innovation.
- Les analyses statistiques mettent en évidence des corrélations entre les variables économiques et technologiques.

---

# 📂 Contenu du dépôt

```text
regional-innovation-spatial-analysis
│
├── README.md
├── DIALLO_NUTS25_2.qmd
├── DIALLO_NUTS25_2.pdf
├── data/
│   └── attributs_nuts.csv
└── images/
    ├── rd_distribution.png
    ├── patents_evolution.png
    ├── patents_france.png
    ├── rd_france.png
    ├── gdp_france.png
    └── gdp_patents.png
```

---

# 📚 Source des données

- Eurostat
- NUTS – Nomenclature of Territorial Units for Statistics

---

# 👨‍💻 Auteur

**Mamadou Pathe DIALLO**

🎓 Master 2 Études Économiques et Statistiques

📊 Data Analysis | Spatial Data Analysis | GIS | R | Statistics

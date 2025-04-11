# Visualisations Interactives avec Plotly – Projet VDD

Ce projet regroupe des visualisations interactives issues de quatre notebooks inspirés de Kaggle et du cours VDD. Chaque notebook traite un thème différent avec des jeux de données variés. L’objectif est de maîtriser Plotly à travers la rétro-ingénierie de visualisations interactives, en s'inspirant d'exemples existants.

---

## 1. `one.ipynb` – 20 Best Interactive Graphs with Plotly

📚 **Source originale :** [Plotly 20 Best Interactive Graphs (Tutorial)](https://www.kaggle.com/code/servietsky/plotly-20best-interactive-graphs-tutorial)

🔢 **Cellules étudiées :** 4, 7, 22, 24-27

### Objectifs :
- Explorer différents types de graphiques interactifs fournis par Plotly
- Apprendre à créer des visualisations dynamiques : scatter, bar, line, pie, heatmap, 3D plots, bubble charts, etc.

### Données :
- Données simulées ou aléatoires (dans le notebook)
- Données COVID-19 utilisées uniquement pour certains exemples

### Visualisations réalisées :
- Scatter plot interactif
- Heatmap animée
- Bar chart dynamique avec sliders
- Visualisation 3D de clusters

---

## 2. `two.ipynb` – Santé Mentale et Données d’Enquête

📚 **Source originale :** [Mental Health : Plotly Interactive Viz](https://www.kaggle.com/code/toomuchsauce/mentalhealth-plotly-interactive-viz/notebook)

🔢 **Cellules étudiées :** 10, 14, 18, 21

### Objectifs :
- Explorer la santé mentale dans le milieu professionnel via une enquête
- Créer des visualisations impactantes sur les tendances de santé mentale selon l’âge, le sexe, le lieu, etc.

### Données :
- `survey.csv` : résultats d’une enquête sur la santé mentale en entreprise

### Visualisations réalisées :
- Treemap des lieux de travail favorables à la santé mentale
- Donut chart des réponses à la recherche d’un traitement
- Sunburst chart sur le genre et la consultation
- Graphiques dynamiques avec `px.sunburst`, `px.pie`, `px.treemap`

---

## 3. `three.ipynb` – Salaires dans le domaine de la Data Science

📚 **Source originale :** [Data Science Job Salaries – Plotly](https://www.kaggle.com/code/priyark/data-science-job-salaries-plotly-interactive-graph/notebook)

🔢 **Cellules étudiées :** 11, 15, 16

### Objectifs :
- Visualiser les salaires selon l’expérience, le pays, le type de contrat et la taille de l’entreprise
- Utiliser des graphiques interactifs pour explorer des tendances complexes

### Données :
- `ds_salaries.csv` : dataset sur les salaires dans les métiers de la data

### Visualisations réalisées :
- Boxplot interactif selon l’expérience
- Scatter plot dynamique par pays
- Bar chart des salaires moyens par rôle

---

## 4. `four.ipynb` – Bonus : Visualisations de l’Assignment 2

🔢 **Cellules étudiées :** 38-39, 56-57

### Objectifs :
- Approfondir les interactions et animations avec Plotly
- Reprendre des exemples techniques avancés (animations, sliders, filtres)

### Données :
- Variables synthétiques ou réutilisées d’autres notebooks
- Basé sur la logique de transition dynamique et de layout enrichi

### Visualisations réalisées :
- Graphiques avec animation de frames
- Slider temporel sur une ligne de tendance
- Synchronisation de plusieurs éléments visuels dans un même graphique

---

## Bibliothèques utilisées

- `plotly.express` : visualisations interactives simples
- `plotly.graph_objects` : visualisations avancées et customisées
- `pandas` : manipulation des jeux de données
- `numpy` : génération de données aléatoires
- `matplotlib` (mineur) : comparaison ponctuelle
- `seaborn` (rare) : exploration complémentaire

---

## Organisation du projet


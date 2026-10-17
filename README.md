# Prédiction des notes étudiantes — Régression linéaire avec R

![Langage](https://img.shields.io/badge/Langage-R-276DC3?logo=r&logoColor=white)
![Domaine](https://img.shields.io/badge/Domaine-Analyse%20de%20donn%C3%A9es-425466)

## Présentation

Ce projet de **modélisation statistique sous R** a pour objectif d'étudier les facteurs académiques associés aux notes des étudiants et de **prédire leurs résultats** à l'aide d'une régression linéaire multiple.

Le travail couvre les principales étapes d'une analyse : préparation des données, construction du modèle, sélection des variables, vérification des hypothèses et évaluation des performances.

## Objectifs

- Explorer les données et repérer les variables potentiellement explicatives.
- Construire un modèle de régression linéaire multiple.
- Comparer des choix de variables à l'aide des critères **AIC** et **BIC**.
- Examiner les résidus pour vérifier les hypothèses du modèle.
- Mesurer la qualité des prédictions avec le **R²** et la **MSE** (erreur quadratique moyenne).

## Démarche

| Étape | Description |
| --- | --- |
| 1. Préparation | Nettoyage et exploration des données |
| 2. Modélisation | Ajustement d'une régression linéaire multiple |
| 3. Sélection | Étude des variables avec les critères AIC et BIC |
| 4. Diagnostic | Analyse des résidus et validation des hypothèses |
| 5. Évaluation | Calcul et interprétation du R² et de la MSE |

## Fichiers du projet

L'archive contient le script `run_analysis.R`, le jeu de données `data/project.csv` et un rapport détaillé (`report.qmd` et `report.html`).

## Outils et notions mobilisés

- **R / RStudio** : analyse statistique et modélisation.
- **Packages présents dans le script** : `ggplot2`, `GGally`, `corrplot`, `patchwork` et `DescTools`.
- **Régression linéaire multiple** : étude de la relation entre une note et plusieurs variables explicatives.
- **AIC / BIC** : critères d'aide à la sélection de modèles.
- **Analyse des résidus** : diagnostic de l'ajustement.
- **R² ajusté, MSE et RMSE** : indicateurs de performance. Le script compare aussi plusieurs modèles et réalise des prédictions sur des données de test.

## Accéder au projet

Le projet est disponible ici :

📦 **[Télécharger l'archive du projet](Projet_mode%CC%80le_line%CC%81aire.zip)**

Pour consulter le travail :
1. Télécharger l'archive.
2. Extraire son contenu.
3. Ouvrir le dossier `Linear model project` dans RStudio.
4. Consulter le rapport `report.html` ou lancer `run_analysis.R` depuis le dossier du projet, avec les packages R nécessaires installés.

## Compétences illustrées

Analyse exploratoire · Modélisation statistique · Sélection de variables · Diagnostic de modèle · Évaluation prédictive

---

*Projet académique de modélisation linéaire sous R.*

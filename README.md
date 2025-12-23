# Projet Statistique HRPF

Analyse statistique des variables anthropométriques et de condition physique issues du texte scientifique HRPF coréen.

## 📝 Description

Ce projet a pour objectif d’étudier l’influence du sexe, de l’âge et d’autres facteurs sur différentes mesures physiques et physiologiques. Il inclut :

- Analyse descriptive des données
- Tests statistiques paramétriques 
- Modèles de régression linéaire avec méthode stepwise
- Gestion et nettoyage du dataset

Le travail a été réalisé en R et est documenté avec les codes, graphiques, résultats et interprétations.

### Fonctionnalités principales

- 📊 Analyses descriptives avec `tapply`
- 🔬 Comparaison de moyennes (`t-test`, `ANOVA`) et variances (`Fisher`, `Bartlett`)
- 📈 Tests d’indépendance et de corrélation (`Pearson`)
- 🧮 Modèle de régression linéaire avec élimination des résidus >2
- 📂 Gestion du dataset et visualisations graphiques

## ⚙️ Prérequis

- R 4.3+ ou version récente
- RStudio (optionnel mais recommandé)
- Packages R : `ggplot2`, `dplyr`, `readr`, `stats`, `openxlsx`, `readxl`, `psych`, `corrplot`, `MASS`, `naniar`, `tidyr`, `gridExtra`

## 🚀 Installation

1. Clonez le repository :
```bash
git clone https://github.com/InesBenDhifallah/HRPF_stat_project.git
cd HRPF_stat_project

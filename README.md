# 🌿 Analyse Multidimensionnelle et Temporelle des Données de Tourbières
*Multidimensional and Time Series Analysis of Peatland Data*

🌍 **[English version below](#english-version)**

---

## 🇫🇷 Version Française

### 📝 Description du projet
Ce projet a été réalisé dans le cadre du Master 1 en Mathématiques Appliquées et Statistique à l'Université d'Orléans (Programme de recherche Junon). 
L'objectif est d'analyser les données bio-météorologiques de la tourbière de La Guette (2017-2021) afin de mieux comprendre son écosystème, et en particulier la dynamique des flux de gaz à effet de serre (CO2 et CH4).

Le projet s'articule autour de trois grands axes :
1. **Nettoyage et Imputation des données :** Gestion des valeurs manquantes massives.
2. **Analyse en Composantes Principales (PCA/ACP) :** Étude des corrélations et oppositions entre les dynamiques thermiques, hydrologiques et atmosphériques.
3. **Séries Temporelles (Time Series) :** Décomposition, stationnarisation et modélisation prédictive des flux en utilisant les composantes de l'ACP comme régresseurs.

### 🛠️ Outils et Technologies
* **Langage & Environnement :** R, R Markdown
* **Méthodes statistiques :** PCA (Principal Component Analysis), Modélisation de Séries Temporelles (ARIMA)
* **Packages principaux :** `FactoMineR`, `ade4`, `factoextra`, `ggplot2`, `corrplot`, `dplyr`, `tidyr`, `missMDA`, `forecast`, `tseries`

### 📂 Structure du dépôt
* `projettourbière.pdf` : Le rapport final complet et détaillé du projet.
* `projettourbière.tex` : Le code source LaTeX du rapport final.
* `projetfinal.Rmd` / `projetfinal.html` : Notebook R contenant la première partie de l'analyse (exploration, nettoyage, et Analyse en Composantes Principales).
* `projet_tourbiere_modelisation.Rmd` / `projet_tourbiere_modelisation.html` : Notebook R contenant la seconde partie (séries temporelles et prévisions).

> ⚠️ **Note sur les données :** Le jeu de données original n'est pas inclus dans ce dépôt (données issues du programme de recherche Junon). Les scripts et notebooks sont partagés à des fins de démonstration technique et méthodologique. Vous pouvez consulter les fichiers `.html` pour visualiser le code exécuté et les résultats obtenus.

### 🚀 Prérequis
Si vous souhaitez tester ou adapter le code avec vos propres données, vous aurez besoin des bibliothèques suivantes :
```R
install.packages(c("FactoMineR", "ade4", "factoextra", "ggplot2", "corrplot", "dplyr", "tidyr", "missMDA", "forecast", "tseries", "dygraphs", "xts"))
```


## 🇬🇧 English Version

### 📝 Project Description
This project was carried out as part of the 1st year of the Master's degree in Applied Mathematics and Statistics at the University of Orléans (Junon research program).
The objective is to analyze bio-meteorological data from the La Guette peatland (2017-2021) to better understand its ecosystem, and in particular the dynamics of greenhouse gas fluxes (CO2 and CH4).

The project is structured around three main axes:
* **Data Cleaning and Imputation:** Handling of massive missing values.
* **Principal Component Analysis (PCA):** Study of the correlations and oppositions between thermal, hydrological, and atmospheric dynamics.
* **Time Series:** Decomposition, stationarization, and predictive modeling of fluxes using PCA components as regressors.

### 🛠️ Tools and Technologies
* **Language & Environment:** R, R Markdown
* **Statistical Methods:** PCA (Principal Component Analysis), Time Series Modeling (ARIMA)
* **Main Packages:** `FactoMineR`, `ade4`, `factoextra`, `ggplot2`, `corrplot`, `dplyr`, `tidyr`, `missMDA`, `forecast`, `tseries`

### 📂 Repository Structure
* `projettourbière.pdf`: The complete and detailed final report of the project.
* `projettourbière.tex`: The LaTeX source code of the final report.
* `projetfinal.Rmd` / `projetfinal.html`: R Notebook containing the first part of the analysis (exploration, cleaning, and Principal Component Analysis).
* `projet_tourbiere_modelisation.Rmd` / `projet_tourbiere_modelisation.html`: R Notebook containing the second part (time series and forecasting).

> ⚠️ **Note on Data:** The original dataset is not included in this repository (data from the Junon research program). The scripts and notebooks are shared for technical and methodological demonstration purposes. You can consult the `.html` files to view the executed code and the results obtained.

### 🚀 Prerequisites
If you want to test or adapt the code with your own data, you will need the following libraries:

```R
install.packages(c("FactoMineR", "ade4", "factoextra", "ggplot2", "corrplot", "dplyr", "tidyr", "missMDA", "forecast", "tseries"))
```

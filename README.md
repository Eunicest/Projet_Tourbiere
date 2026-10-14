# 🌿 Analyse Multidimensionnelle et Temporelle des Données de Tourbières (La Guette)

## 🎯 Résultats Clés
*(Pour le détail de l'analyse, consultez le rapport : `projettourbière.pdf`)*

* **Analyse en Composantes Principales (ACP) :** 
* **Séries Temporelles et Prévision :** Les flux de gaz (CO2/CH4) ont été modélisés à l'aide des composantes de l'ACP. Le meilleur ajustement a été obtenu avec un modèle ** **, permettant des prévisions fiables avec une erreur [RMSE / MAPE] de ****.

---

## 📝 Contexte du projet
Projet réalisé dans le cadre du Master 1 Mathématiques Appliquées et Statistique de l'Université d'Orléans (Programme de recherche Junon). 
L'objectif est d'analyser les données bio-météorologiques de la tourbière de La Guette (2017-2021) afin de comprendre la dynamique de cet écosystème face aux flux de gaz à effet de serre (CO2 et CH4).

Le projet s'articule autour de :
1. **L'Imputation des données :** Gestion des valeurs manquantes massives (`missMDA`).
2. **L'ACP :** Étude des dynamiques thermiques, hydrologiques et atmosphériques.
3. **Séries Temporelles :** Décomposition, stationnarisation et modélisation (ARIMA).

### 🛠️ Outils et Technologies
* **Environnement :** R, R Markdown
* **Méthodes :** ACP, Modélisation ARIMA
* **Packages clés :** `FactoMineR`, `ade4`, `factoextra`, `ggplot2`, `corrplot`, `dplyr`, `tidyr`, `missMDA`, `forecast`, `tseries`

### 📂 Structure du dépôt
Pour une lecture fluide, les rendus finaux sont à la racine, et les codes sources sont regroupés :
* 📄 `projettourbière.pdf` : Le rapport final complet.
* 📊 `projetfinal.html` : Notebook interactif (exploration, nettoyage, ACP).
* 📈 `projet_tourbiere_modelisation.html` : Notebook interactif (séries temporelles).
* 📁 `src/` : Dossier contenant les codes sources (`.Rmd`, `.tex`, `figure-latex/`).

> ⚠️ **Note sur les données :** Les données originales (programme Junon) ne sont pas incluses. Les fichiers `.html` permettent de visualiser le code exécuté et les résultats.

---
<br>

<details>
<summary>🇬🇧 <b>English version (Click to expand)</b></summary>

## 🎯 Key Results
*(For the full analysis, read the report: `projettourbière.pdf`)*

* **Principal Component Analysis (PCA):** 
* **Time Series & Forecasting:** Gas fluxes (CO2/CH4) were modeled using PCA components as regressors. The best fit was achieved with an ** ** model, yielding forecasts with an [RMSE / MAPE] error of ** **.

---

## 📝 Project Context
Project carried out as part of the 1st year of the Master's in Applied Mathematics and Statistics at the University of Orléans (Junon research program). 
The objective is to analyze bio-meteorological data from the La Guette peatland (2017-2021) to understand the dynamics of greenhouse gas fluxes (CO2 and CH4).

### 🛠️ Tools and Technologies
* **Environment:** R, R Markdown
* **Methods:** PCA, Time Series Modeling (ARIMA)
* **Core Packages:** `FactoMineR`, `ade4`, `factoextra`, `ggplot2`, `corrplot`, `dplyr`, `tidyr`, `missMDA`, `forecast`, `tseries`

### 📂 Repository Structure
For a smooth reading experience, final outputs are at the root, and source codes are grouped:
* 📄 `projettourbière.pdf`: The complete final report.
* 📊 `projetfinal.html`: Interactive notebook (exploration, cleaning, PCA).
* 📈 `projet_tourbiere_modelisation.html`: Interactive notebook (time series).
* 📁 `src/`: Folder containing all source codes (`.Rmd`, `.tex`, `figure-latex/`).
</details>
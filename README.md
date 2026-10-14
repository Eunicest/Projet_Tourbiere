# 🌿 Analyse Multidimensionnelle et Temporelle des Données de Tourbières (La Guette)

## 🎯 Résultats Clés
*(Pour le détail de l'analyse, consultez le rapport : `projettourbière.pdf`)*

- **Analyse en Composantes Principales (ACP) :** Mise en évidence de 3 grands facteurs régissant la tourbière : les dynamiques thermiques (Axe 1), hydrologiques (Axe 2, qui isole notamment la sécheresse de 2019) et atmosphériques (Axe 3). Le CO2 se révèle très corrélé aux variations thermiques, tandis que le CH4 est particulièrement sensible aux conditions atmosphériques.
- **Séries Temporelles et Prévision :** Les flux de gaz (CO2/CH4) ont été modélisés à l'aide des composantes de l'ACP. Le meilleur ajustement a été obtenu avec un modèle **ARIMAX (utilisant les 4 premiers axes de l'ACP comme régresseurs)**, permettant des prévisions fiables avec une erreur **RMSE de 1.58** pour le CO2 (modèle 2017-2020) et un **MAPE de 68.8%** pour le CH4 (modèle 2017-2018). L'étude souligne également l'impact majeur des événements extrêmes (sécheresse de 2019, confinements de 2020) sur ces flux.

---

## 📝 Contexte du projet
Projet réalisé dans le cadre du Master 1 Mathématiques Appliquées et Statistique de l'Université d'Orléans (Programme de recherche Junon). 
L'objectif est d'analyser les données bio-météorologiques de la tourbière de La Guette (2017-2021) afin de comprendre la dynamique de cet écosystème face aux flux de gaz à effet de serre (CO2 et CH4).

Le projet s'articule autour de :
1. **L'Imputation des données :** Gestion des valeurs manquantes massives (`missMDA`).
2. **L'ACP :** Étude des dynamiques thermiques, hydrologiques et atmosphériques.
3. **Séries Temporelles :** Décomposition, stationnarisation et modélisation (ARIMA/ARIMAX).

### 🛠️ Outils et Technologies
- **Environnement :** R, R Markdown
- **Méthodes :** ACP, Modélisation ARIMA / ARIMAX
- **Packages clés :** `FactoMineR`, `ade4`, `factoextra`, `ggplot2`, `corrplot`, `dplyr`, `tidyr`, `missMDA`, `forecast`, `tseries`

### 📂 Structure du dépôt
Pour une lecture fluide, les rendus finaux sont à la racine, et les codes sources sont regroupés :
- 📄 `projettourbière.pdf` : Le rapport final complet.
- 📊 `projetfinal.html` : Notebook interactif (exploration, nettoyage, ACP).
- 📈 `projet_tourbiere_modelisation.html` : Notebook interactif (séries temporelles).
- 📁 `src/` : Dossier contenant les codes sources (`.Rmd`, `.tex`, `figure-latex/`).

> ⚠️ **Note sur les données :** Les données originales (programme Junon) ne sont pas incluses. Les fichiers `.html` permettent de visualiser le code exécuté et les résultats.

---
<br>

<details>
<summary>🇬🇧 <b>English version (Click to expand)</b></summary>

## 🎯 Key Results
*(For the full analysis, read the report: `projettourbière.pdf`)*

- **Principal Component Analysis (PCA):** Identification of 3 main drivers for the peatland: thermal dynamics (Axis 1), hydrology (Axis 2, which captures the severe 2019 drought), and atmospheric conditions (Axis 3). CO2 is highly correlated with thermal variations, while CH4 is mostly driven by atmospheric conditions.
- **Time Series & Forecasting:** Gas fluxes (CO2/CH4) were modeled using PCA components as regressors. The best fit was achieved with an **ARIMAX** model (incorporating the first 4 PCA axes), yielding forecasts with an **RMSE of 1.58** for CO2 and a **MAPE of 68.8%** for CH4. Extreme events (2019 drought, 2020 lockdowns) were shown to significantly disrupt these natural fluxes.

---

## 📝 Project Context
Project carried out as part of the 1st year of the Master's in Applied Mathematics and Statistics at the University of Orléans (Junon research program). 
The objective is to analyze bio-meteorological data from the La Guette peatland (2017-2021) to understand the dynamics of greenhouse gas fluxes (CO2 and CH4).

### 🛠️ Tools and Technologies
- **Environment:** R, R Markdown
- **Methods:** PCA, Time Series Modeling (ARIMA / ARIMAX)
- **Core Packages:** `FactoMineR`, `ade4`, `factoextra`, `ggplot2`, `corrplot`, `dplyr`, `tidyr`, `missMDA`, `forecast`, `tseries`

### 📂 Repository Structure
For a smooth reading experience, final outputs are at the root, and source codes are grouped:
- 📄 `projettourbière.pdf`: The complete final report.
- 📊 `projetfinal.html`: Interactive notebook (exploration, cleaning, PCA).
- 📈 `projet_tourbiere_modelisation.html`: Interactive notebook (time series).
- 📁 `src/`: Folder containing all source codes (`.Rmd`, `.tex`, `figure-latex/`).
</details>

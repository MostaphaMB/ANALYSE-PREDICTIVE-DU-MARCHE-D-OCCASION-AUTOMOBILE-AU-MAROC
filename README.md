# 🚗 Analyse Prédictive du Marché d'Occasion Automobile au Maroc
<img width="1194" height="669" alt="01" src="https://github.com/user-attachments/assets/2928c647-aba1-4ab5-af1e-7689d85b25ac" />

<img width="1192" height="665" alt="02" src="https://github.com/user-attachments/assets/4e6594fb-62f1-4455-9e69-7a4389ba7504" />

<img width="1188" height="667" alt="03" src="https://github.com/user-attachments/assets/5b91bf5d-9eca-40d6-b67a-10615bb7becb" />

<img width="1189" height="671" alt="04" src="https://github.com/user-attachments/assets/571ca75d-c754-40bb-9438-e05918d3937b" />

## 📝 Présentation du Projet
Ce projet "Fil Rouge" consiste à concevoir et déployer une solution complète de Data Science, allant de la collecte de données brutes sur le web (**Web Scraping**) jusqu'à l'estimation des prix des véhicules d'occasion au Maroc par **Machine Learning**. En s'appuyant sur les annonces de la plateforme leader *Moteur.ma*, l'objectif est d'apporter de la transparence à un marché traditionnellement opaque en fournissant un outil prédictif fiable, interprétable et adapté aux réalités économiques marocaines.

## 🎯 Objectifs du Projet
* **Collecte de Données (Scraping)** : Développer un script automatisé pour extraire les annonces (HTML brute) de manière éthique et robuste.
* **Analyse Exploratoire (EDA)** : Identifier les facteurs clés influençant la valeur des véhicules (marque, modèle, âge, kilométrage, carburant, puissance fiscale, ville).
* **Pipeline de Preprocessing** : Traiter les données manquantes, éliminer les anomalies de prix et standardiser les variables catégorielles.
* **Modélisation Prédictive** : Entraîner et comparer plusieurs algorithmes de régression pour optimiser la précision de l'estimation (Score $R^2$ et métriques d'erreur).
* **Restitution Decisionnelle & Interactive** : Concevoir un dashboard analytique et une interface utilisateur permettant de simuler le prix d'un véhicule en temps réel.

## 🛠️ Stack Technique
* **Collecte de Données** : Python (BeautifulSoup / Scrapy / Requests).
* **Analyse & Preprocessing** : Pandas, NumPy, Scikit-learn.
* **Visualisation & Business Intelligence** : Matplotlib, Seaborn, Power BI.
* **Modélisation ML** : Scikit-learn (Algorithmes de régression), Joblib.
* **Déploiement / Interface** : Streamlit (Application de simulation interactive).
* **Gestion de Projet** : Cadre méthodologique agile avec Jira & GitHub.

---

## 🏗️ Architecture des Données & Pipeline

Le cycle de vie du projet s'articule autour de 4 phases majeures :
1. **Extraction (Web Scraping)** : Collecte des caractéristiques techniques et des prix affichés sur *Moteur.ma*.
2. **Nettoyage & Préparation** : Gestion des inconsistances textuelles, conversion des types, traitement des valeurs nulles et standardisation.
3. **Modélisation (Machine Learning)** : Entraînement de modèles de régression et analyse des caractéristiques clés (*Feature Importance*).
4. **Restitution & Industrialisation** : Intégration du modèle final dans un outil interactif d'aide à la décision.

---

## 🚀 Échéancier et Étapes de Réalisation

### Semaine 1 : Collecte & Ingestion des Données 🌐
* Conception et validation du script de web scraping sur la plateforme cible.
* Extraction des variables essentielles (Modèle, Année, Kilométrage, Prix, etc.) et stockage brut au format CSV.

### Semaine 2 : Analyse Exploratoire (EDA) & Data Cleaning 🧹
* Traitement des prix manquants et suppression des valeurs aberrantes (ex: véhicules premium sous-évalués ou citadines surévaluées).
* Analyse statistique des corrélations (impact de la puissance fiscale et du type de carburant sur le prix au Maroc).
* Encodage des données textuelles et normalisation des caractéristiques numériques.

### Semaine 3 : Modélisation Prédictive & Évaluation 🧪
* Séparation stricte des données (Train/Test) et mise en place des pipelines de preprocessing.
* Entraînement et comparaison de plusieurs estimateurs (Régression Linéaire, Random Forest, Gradient Boosting).
* Évaluation fine des performances et sélection du meilleur modèle basé sur la généralisation des prédictions.

### Semaine 4 : Industrialisation, Dashboarding & Restitution 🏆
* Sérialisation du modèle retenu au format `.joblib`.
* Développement d'un dashboard de suivi du marché et d'une interface utilisateur web interactive avec **Streamlit**.
* Finalisation de la documentation technique et préparation de la soutenance.

---

## 📦 Contenu des Livrables
* **Code Source** : Repository GitHub modulaire contenant le scraper, les pipelines de préparation et l'application.
* **Dataset Final** : Fichier CSV nettoyé, enrichi et prêt pour l'analyse.
* **Notebook EDA** : Analyse exploratoire détaillée et commentée.
* **Modèle Sérialisé** : Fichier `.joblib` du modèle prédictif optimal.
* **Interface Interactive** : Code de l'application de simulation Streamlit.
* **Dashboard / Rapport** : Support de présentation final de la démarche et des insights du marché automobile marocain.

---
*Projet Fil Rouge réalisé individuellement dans le cadre de la formation DATA Analyst (Simplon x JobInTech).*

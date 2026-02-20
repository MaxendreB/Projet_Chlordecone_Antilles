# 🌴 Analyse de la contamination à la Chlordécone aux Antilles

**Projet de Data Science (Python)**

*Auteur : Maxendre Bauthamy*

## 📋 Contexte
La chlordécone est un pesticide organochloré utilisé aux Antilles françaises jusqu’au début des années 1990. Sa persistance dans les sols, les eaux et les chaînes alimentaires en fait aujourd’hui un enjeu sanitaire, environnemental et socio-économique majeur.

Ce projet vise à exploiter des jeux de données réels ou réalistes (environnement, santé, agriculture, enquêtes, données spatiales et temporelles) afin de :
- structurer, nettoyer et transformer les données,
- mener des analyses statistiques et exploratoires avancées,
- produire des insights utiles à la prise de décision publique.

## 🛠️ Méthodologie
1. **Ingénierie des Données :**
   - Nettoyage et conversion des types (gestion des virgules, caractères parasites, formatage des dates).
   - Traitement des valeurs manquantes (imputation par la médiane pour les variables numériques).
2. **Analyse Exploratoire :**
   - Étude agronomique et climatique (impact du type de sol, du relief et de la pluviométrie sur la rétention de la molécule).
   - Analyse temporelle et détection de biais d'échantillonnage (évolution des campagnes de prélèvements au fil des années).
   - Géomatique et cartographie.

## 📂 Structure du dépôt
- `data/` :
  - `data/raw/` : Contient le jeu de données brut (BaseCLD2026.csv).
  - `data/processed/` : Contient la base de données nettoyée après l'étape d'Ingénierie des données (BaseCLD_clean.csv).
- `notebooks/` : Contient les notebooks Python détaillant les parties Ingénierie des données (01_Ingenierie_Donnees.ipynb) et Analyse exploratoire des données (02_Analyse_Exploratoire.ipynb).

## 🎯 Livrables
- `Dépôt Kaggle` : Lien Kaggle : https://www.kaggle.com/code/maxendrebauthamy/projet-chlordecone-antilles
- `Un document Notebook pour l'étape ingénierie des données` : Le fichier nommé "01_Ingenierie_Donnees.ipynb". 
- `Rapport final synthétique orienté aide à la décision` : Le fichier nommé "02_Analyse_Exploratoire.ipynb".

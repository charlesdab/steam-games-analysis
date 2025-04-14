# 🎮 Steam Games Analysis

Ce projet a pour objectif de réaliser une **analyse exploratoire des jeux vidéo disponibles sur la plateforme Steam**, afin d’identifier les grandes tendances du marché, comprendre les préférences des joueurs, et fournir des **recommandations stratégiques à un éditeur de jeux**.

---

## 🚀 Objectif du projet

Vous travaillez chez **Ubisoft**, un éditeur de jeux vidéo. Dans le cadre de la préparation d’un **nouveau jeu révolutionnaire**, vous avez été chargé de :

- Explorer les données de Steam
- Identifier les tendances clés du marché
- Comprendre les facteurs de succès (genre, plateforme, prix, langue, etc.)
- Analyser la distribution des jeux, leurs notes, les éditeurs, etc.

---

## 🧠 Analyses réalisées

L’analyse est structurée en trois axes :

### 🔹 Analyse Macro

- Top éditeurs (nombre de jeux publiés)
- Jeux les mieux notés (ratio positif / total)
- Nombre de jeux sortis par année (effet du Covid observé)
- Distribution des prix et des réductions
- Langues les plus représentées
- Jeux interdits aux mineurs

### 🔹 Analyse des Genres

- Genres les plus populaires
- Genres avec les meilleurs retours utilisateurs
- Genres favoris selon les éditeurs
- Genres les plus lucratifs (prix moyen)

### 🔹 Analyse par Plateforme

- Répartition Windows / Mac / Linux
- Genres par plateformes dominantes

---

## 📊 Données utilisées

- **Source** : Steam game dataset (semi-structuré JSON)
- **Chemin S3** : `s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json`
- **Format** : JSON imbriqué avec structures `tags`, `categories`, `platforms`, etc.

---

## 🛠️ Technologies

- **Databricks** (notebook cloud)
- **PySpark** (traitement des données)
- **SQL + visualisations intégrées**
- **Matplotlib / Pandas** pour certaines représentations

---

## 📍 Lien vers le notebook publié

🔗 [Voir l’analyse complète sur Databricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/970896639981716/1056884091747424/2809145407473828/latest.html)

---

## 🎓 Contexte pédagogique

Projet réalisé dans le cadre du **bootcamp Data Science - Jedha**, module Analyse Exploratoire des Données (EDA), évaluation CDSD.

---

## ✍️ Auteur

**Charles D.**

📁 Dépôt GitHub : [steam-games-analysis](https://github.com/charlesdab/steam-games-analysis)

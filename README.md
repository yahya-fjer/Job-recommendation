# Job Recommendation System

Ce projet vise à développer un système de recommandation d'emplois basé sur le traitement du langage naturel (NLP) et des techniques de similarité sémantique.

## 📌 Objectif

Proposer des recommandations de postes similaires à une offre d'emploi ou à un titre saisi par l'utilisateur, en se basant sur les descriptions disponibles dans une base de données.

## 📁 Structure du projet

- `job Recommendation.ipynb` : Notebook principal contenant le code de prétraitement, vectorisation des textes (TF-IDF), et la logique de recommandation.
- `MySQL` : Utilisation d'une base de données pour stocker les offres d'emploi.
- `NLTK`, `sklearn`, `pandas`, `re` : Outils utilisés pour le nettoyage et la vectorisation du texte.

## ⚙️ Fonctionnalités

- Nettoyage des titres de postes (suppression des villes, stopwords, etc.)
- Extraction des titres depuis une base de données MySQL.
- Calcul de similarité cosinus entre titres de postes.
- Recommandation de postes similaires à partir d’un titre saisi.

## 🚀 Comment exécuter le projet



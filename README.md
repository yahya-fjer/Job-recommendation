# 🔍 Job Recommendation System using PySpark

Ce projet propose un système de recommandation d’emploi basé sur les compétences extraites des descriptions d'offres et des profils candidats, en utilisant PySpark pour le traitement de données à grande échelle.

## 📁 Fichiers attendus

- `linkedin_job_postings.csv` : Fichier contenant les offres d’emploi avec leurs titres, descriptions, etc.
- `stopwords.txt` : Liste des mots à ignorer lors du traitement des textes.
- `test_cases.csv` : Fichier de profils de chercheurs d'emploi avec leurs compétences ou descriptions.
- `output_job_skills_match.csv` : Fichier de sortie généré avec les correspondances entre profils et emplois.

## ⚙️ Technologies utilisées

- Python
- PySpark
- NLTK (Natural Language Toolkit)
- TF-IDF (extraction des mots-clés)
- Spark MLlib (vectorisation et similarité)

## 🚀 Exécution du projet

1. **Installer les dépendances** :
   ```bash
   pip install pyspark nltk

# Analyse de sentiments des avis clients sur des livres 📚

## Description
Ce projet analyse des avis clients réels sur des livres afin de prédire le **sentiment** des commentaires (positif ou négatif).  
Il présente un pipeline complet de **NLP classique** et de **Machine Learning**, de l’exploration des données jusqu’à l’évaluation des modèles.

---

## Datasets
- **Books.csv** : informations sur les livres (titre, auteur, catégories, etc.)  
- **Ratings.csv** : avis clients (score, texte, résumé, date, etc.)  

Les deux fichiers sont joints pour relier les avis aux livres.

---

## Pipeline du projet
1. **Exploration des données (EDA)** : distribution des sentiments, longueur des avis, statistiques sur les livres.  
2. **Nettoyage du texte** : mise en minuscule, suppression de ponctuation, chiffres et stopwords.  
3. **Vectorisation TF-IDF** : transformation des textes en vecteurs numériques.  
4. **Entraînement des modèles ML** :  
   - Logistic Regression  
   - Naive Bayes  
   - SVM (LinearSVC)  
5. **Évaluation et comparaison** : Accuracy, F1-score, classification report et matrice de confusion.  
6. **Conclusion et interprétation** : identification du meilleur modèle et recommandations d’amélioration.

---

## Résultats
- Le **SVM** obtient généralement les meilleurs résultats.  
- Les modèles permettent de détecter efficacement les avis positifs et négatifs.  
- Le pipeline est reproductible et peut être amélioré avec des modèles avancés comme **BERT**.

---

## Technologies et bibliothèques utilisées
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- nltk  
- scikit-learn (Logistic Regression, Naive Bayes, SVM, TF-IDF, train_test_split, métriques)

---

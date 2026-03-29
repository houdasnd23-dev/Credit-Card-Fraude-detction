# 💳 Détection de Fraude Bancaire — Projet Personnel

Ce projet est un projet personnel que j'ai réalisé après avoir suivi un module d'introduction à l'IA.  
J'ai voulu mettre en pratique ce que j'ai appris en travaillant sur un vrai dataset.

---

##  C'est quoi ce projet ?

J'ai essayé de construire un programme capable de détecter automatiquement les fraudes bancaires.  
Le dataset contient **284 807 transactions réelles** — dont seulement 492 fraudes (0.17%).

Le défi principal : comment détecter quelque chose d'aussi rare ?

---

## 📊 Dataset utilisé

- Source : Kaggle – Credit Card Fraud Detection (dataset public)
- 284 807 transactions bancaires réelles
- 492 fraudes seulement (0.17% du total)

---

##  Ce que j'ai fait

1. **Analyser les données** — comprendre la distribution, les montants, le temps
2. **Préparer les données** — normalisation, gestion des valeurs manquantes
3. **Gérer le déséquilibre** — avec une technique appelée SMOTE
4. **Tester 3 modèles ML** et comparer leurs performances

---

##  Résultats obtenus

| Modèle | F1-Score | AUC-ROC |
|---|---|---|
| Logistic Regression | 0.109 | 0.969 |
| **Random Forest**  | **0.841** | **0.973** |
| XGBoost | 0.802 | 0.979 |

Le **Random Forest** a donné les meilleurs résultats.

---

##  Ce que j'ai appris

- Pourquoi l'accuracy seule ne suffit pas sur des données déséquilibrées
- L'importance du Recall quand les erreurs sont coûteuses
- Comment le SMOTE aide le modèle à mieux apprendre
- Comparer plusieurs modèles avant de choisir

---

##  Outils utilisés

- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn, XGBoost
- Google Colab

---

## 👤 Auteur

**SANDOUBI HOUDA**  
Étudiant en Cybersecurity & Digital Trust Engineering   
[LinkedIn](www.linkedin.com/in/houda-s-9284aa315)

# Machine-Learning : Prédiction de la réadmission à l’hôpital (<30 jours)

Objectif:
La réadmission hospitalière est un enjeu majeur pour la qualité des soins et la gestion des ressources. L’objectif est de prédire si un patient diabétique sera réadmis dans les 30 jours suivant sa sortie.

 Objectif secondaire : 
 impact clinique, optimisation des soins, prévention.

 Dataset : 
 Source : Kaggle / UCI — patients diabétiques hospitalisés
 Taille : ~100k patients
 Variables clés : âge, sexe, antécédents, nombre d’admissions précédentes, durée d’hospitalisation, etc.

Méthodes:
- Préparation des données : Nettoyage, gestion des valeurs manquantes, Transformation de la variable cible (readmitted yes/no)
- Feature engineering : Variables pertinentes créées ou transformées
- Modélisation : Logistic Regression, Random Forest, XGBoost
- Évaluation : ROC AUC, Recall, Confusion Matrix
- Interprétation : Importance des variables avec SHAP (ex. facteurs qui augmentent le risque de réadmission)

Compétences utilisées : 
Python : pandas, numpy, matplotlib/seaborn
ML : scikit-learn, XGBoost
Interprétation : SHAP
Statistiques et raisonnement clinique

Résumé : 
Le modèle XGBoost a obtenu un ROC AUC de 0.85 et un recall de 0.72. Les variables les plus influentes sont le nombre d’admissions antérieures, la durée du séjour et certaines comorbidités.

=> Ajouter un graphique clé (feature importance ou ROC curve).

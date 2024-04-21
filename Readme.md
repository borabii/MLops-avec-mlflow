# Titre du Projet : Prédiction de la Propension à Souscrire à un Produit Financier et déploiement du modèle avec mlflow

## Description Technique

Ce projet implique la création d'un modèle de machine learning destiné à prédire la probabilité qu'un client souscrive à un produit financier, en utilisant des données client historiques. Les principales étapes du processus comprennent :

1. **Importation des données depuis un fichier CSV**:

2. **Analyse univariée et multivariée**: Des analyses sont effectuées pour comprendre la distribution des données et les relations entre les variables, en incluant la génération d'histogrammes, de boîtes à moustaches, et l'examen des corrélations.

3. **Évaluation de la variable cible 'y'**: Le nombre de classes dans la variable cible (par exemple, souscription ou non à un produit financier) est déterminé, et l'équilibre des classes est évalué.

4. **Nettoyage des données**: Les valeurs manquantes et les valeurs aberrantes sont traitées, si nécessaire, pour garantir la qualité des données.

5. **Encodage des variables catégorielles**: Les variables catégorielles sont encodées pour être utilisées dans les modèles de machine learning.

6. **Séparation des caractéristiques (features) et de la variable cible**: Les données sont divisées en ensembles de caractéristiques (X) et de la variable cible (Y).

7. **Division des données en ensembles d'entraînement et de test**: Les données sont divisées en ensembles d'entraînement et de test pour évaluer les performances du modèle.

8. **Gestion du problème de données déséquilibrées**:

9. **Création d'une expérience avec mlflow**:

10. **Recherche du meilleur modèle**:Trois modèles sont évalués sans réglages, et le modèle optimal est identifié en termes de performances enregistrées dans mlflow.

11. **Optimisation des hyperparamètres**: Les hyperparamètres sont optimisés pour améliorer les performances des modèles, et le nouveau modèle amélioré avec les paramètres optimaux est enregistré dans mlflow.

12. **Déploiement du modèle avec mlflow**:

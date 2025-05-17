# Notebook d'un projet de Machine Learning pour estimer le juste prix d'une voiture d'occasion via une application

## Introduction
Je m'appelle **Charles-Henri SAINT-MARS** et je m'intéresse à l'**IA**, à la **Data Science** et au **Machine Learning**. Les notebooks de ce dépôt sont mes notes de travaux pratiques sur la création d'un modèle de Machine Learning pour estimer le juste prix d'une voiture d'occasion en fonction de son poids à vide. J'ai utilisé une approche avec la bibliothèque **Sklearn** et une autre approche avec une bibliothèque de classes et de méthodes personnalisées en Python exploitant **la méthode des moindres carrés**. Par la suite, les modèles de chaque approche sont implémentés dans une application Python comme pour répondre à un besoin métier.

## Projet de Machine Learning pour estimer le juste prix d'une voiture d'occasion via une application
### Travaux pratiques réalisés à partir du cours de Machine Learning de José AFOUDA
Remarque : La méthode des moindres carrés, via des classes et méthodes personnalisées, pour créer le modèle de régression linéaire est une approche personnelle.

## Scénario du projet :
Vous avez <u>une entreprise de développement d'applications mobiles</u>  et votre nouveau projet concerne la création d'une application qui met en relation des vendeurs de voitures d'occasion et des potentiels clients. Vous aimeriez ajouter une nouvelle fonctionnalité à cette application: celle de donner la possibilité aux utilisateurs de l'application de connaître le prix correct auquel ils peuvent acheter ou vendre une voiture d'occasion d'après les caractéristiques qu'ils souhaitent afin de ne pas se faire arnaquer par des vendeurs.

Ensuite l'application devra avertir un potentiel acheteur si la voiture qui l'intéresse est au prix "juste" et aussi avertir un vendeur si le prix auquel il veut vendre sa voiture est approprié.

Après avoir collecté des données de caractéristiques de plusieurs centaines de voitures d'occasion ainsi que leur prix de vente sur des plate-formes dédiées, vous décidez donc de construire un modèle de Machine Learning capable de prédire le prix d'une voiture en fonction de ses caractéristiques.

Remarque : dans ce projet, on s'intéresse uniquement à la caractéristique (ou variable) "poids à vide" de la voiture pour estimer son prix. En effet, il existe d'autres caractéristiques qui influencent le prix d'une voiture d'occasion, mais pour ce projet, on se concentre sur une seule caractéristique pour simplifier le modèle.

Lien du cours : [https://www.youtube.com/watch?v=7-WsA_arUpg](https://www.youtube.com/watch?v=7-WsA_arUpg)

## Les notebooks du projet
- [Notebook 1 : Modèle de régression linéaire crée avec SkLearn](https://github.com/charlenry/machine_learning_estimer_prix_voiture/blob/main/Estimer_prix_voiture_avec_sklearn.ipynb)
- [Notebook 2 : Modèle de régression linéaire crée avec une bibliothèque de classes et de méthodes personnalisées](https://github.com/charlenry/machine_learning_estimer_prix_voiture/blob/main/Estimer_prix_voiture_avec_moindres_carres.ipynb)

## Conclusion
Ce projet m'a permis de découvrir concrètement le Machine Learning dans un cas simple et de comprendre comment on peut l'implémenter dans une application Python dans un cas concret. Au cours de ce projet, j'ai appris à : 
- utiliser les librairies Pandas, Numpy, Plotly Express, Matplotlib, SkLearn, et Joblib
- manipuler des données
- nettoyer les données
- visualiser les données
- créer et entraîner un modèle de régression linéaire avec une variable en entrée et une en sortie
- évaluer la performance du modèle à l'aide du coefficient de détermination R² et du coefficient de corrélation
- utiliser le modèle pour faire des estimations
- sauvegarder le modèle dans un fichier PKL pour pouvoir l'utiliser ultérieurement
- implémenter le modèle dans une application Python pour répondre au besoin métier (voir scénario du projet ci-dessus)

## Contact
[LinkedIn de Charles-Henri SAINT-MARS](https://www.linkedin.com/in/charles-henri-saint-mars)

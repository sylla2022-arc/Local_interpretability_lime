# Description
Dans le contexte actuel où les décisions cruciales reposent en partie sur des modèles d'apprentissage automatique, comme la prédiction du risque de récidive du cancer ou de faillite en cas de prêt bancaire, l'interprétabilité des modèles devient essentielle pour garantir la transparence et la confiance dans les résultats.

LIME, une méthode implémentée dans le langage de programmation Python et initiée par Marco Tulio Ribeiro, joue un rôle crucial dans ce processus. Son objectif principal est d'évaluer la confiance dans les prédictions de tout modèle de classification en répondant à la question : "Pourquoi devrais-je vous faire confiance ?"

Dans ce contexte, il est particulièrement pertinent d'utiliser LIME pour :

* Interpréter localement un modèle de Machine Learning, tel qu'un classificateur Random Forest. 

* Créer des perturbations autour d'un point de données spécifique et calculer la prédiction correspondante, ce qui permet de comprendre comment les caractéristiques individuelles influent sur les prédictions du modèle.
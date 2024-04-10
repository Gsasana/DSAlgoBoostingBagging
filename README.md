# DSAlgoBoostingBagging
Les méthodes de bagging et de boosting sont des "méta-algorithmes" dont l'approche est de combiner plusieurs algorithmes d'apprentissage automatique en un modèle prédictif, afin de réduire leur variance ou leur biais, et d'améliorer la performance finale.


Les deux méthodes fonctionnent de manière similaire, et consistent en 2 étapes principales :
1) Construire différents modèles de Machine Learning simples sur des sous-ensembles des données d'origine.
2) Produire un nouveau modèle à partir de l'assemblage des précédents.

On utilisera le jeux de données 'letter-recognitive.csv' qui contient certaines caractèristiques propres à des images représentant l'une des 26 lettres capitales de l'alphabet latin, et une colonne letter avec la lettre correspondante. 
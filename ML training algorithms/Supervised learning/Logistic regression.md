La "Logistic regression" est aussi un algorithme de ML. Contrairement a la "[[Linear regression]]" , cet algorithme est utilisé pour `classer` la sortie, au lieu de donner une valeur numérique.

Cet algorithle utilise la fonction sigmoïde pour fonctionner, puisqu'elle va de 0 à 1.

Cependant, pour la classification avec plusieurs labels, on peut utiliser des "lignes de décision"(`decision boundary` ) pour mieux visualiser le modèle: Il s'agit de lignes placées par interfalle, afin de permettre au modèle de classer les prédictions.

Il est également possible d'utiliser la `sigmo¨ïde`, avec plusieurs valeurs disponibles: Pour cela, on utilise l'approche `One-vs-Rest`(OvR). Des modèles sont entrainés en parallèle, et celui avec la plus grande probabilité est choisi.

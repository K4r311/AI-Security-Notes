La "Logistic regression" est aussi un algorithme de ML. Contrairement a la "[[Linear regression]]" , cet algorithme est utilisé pour `classer` la sortie, au lieu de donner une valeur numérique.

Cet algorithle utilise la fonction sigmoïde pour fonctionner, puisqu'elle va de 0 à 1.
![func](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRp3_aAS7EXrliOEAjxH9vOdfT-L-UOC-fjFI4hlPHEfmUdvcQ7Nf2O0qDF&s=10)


Cependant, pour la classification avec plusieurs labels, on peut utiliser des "lignes de décision"(`decision boundary` ) pour mieux visualiser le modèle: Il s'agit de lignes placées par interfalle, afin de permettre au modèle de classer les prédictions.
![attachment](https://wirelesspi.com/wp-content/uploads/2022/08/figure-logistic-regression-decision-boundary-2.png)


Il est également possible d'utiliser la `sigmo¨ïde`, avec plusieurs valeurs disponibles: Pour cela, on utilise l'approche `One-vs-Rest`(OvR). Des modèles sont entrainés en parallèle, et celui avec la plus grande probabilité est choisi.

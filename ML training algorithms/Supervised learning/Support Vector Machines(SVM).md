Les SVM sont un algorithme d'entraînement des modèles de classification en ML

Ils utilisent également des  `decision boundaries` (appelées Hyperlanes en SVM), comme en [[Logistic regression]], mais ces limites de décision ne sont pas toujours linéaires.

De plus, les limites de décision au niveau des SVM ont des `marges` , plus ou moins éloignées de la limite de décision elle-même, ce qui permet une meilleure classification.

Ces marges sont définies par les points les plus proches des `hyperlanes`

![test ](https://towardsdatascience.com/wp-content/uploads/2023/10/1bXlp7LVAPhIay-Pk0MxdlA.png) 

Pour les SVM non linéaires, il existe une technique appelée le **kernel trick**. Elle permet de transformer implicitement les données dans un espace de dimension supérieure, où il peut devenir plus facile de les séparer à l'aide d'un hyperplan. 

Cette technique utilise des **kernel functions** pour calculer la similarité entre les données dans cet espace sans avoir à effectuer explicitement la transformation.

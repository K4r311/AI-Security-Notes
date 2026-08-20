Les arbres de décision sont un algorithme de ML, aussi utilisés dans la classification.

Au niveau des arbres de décision, la machine prend la `feature` avec le plus grand poids, et l'utilise comme `root node` ,

Ensuite, d'autres  `child nodes` sont crées a partir des valeurs de la feature choisie par le root node, et ces nodes enfants créent d'avantage de nodes a partir de la donnée du dataset.

Les nodes deviennent des `leave nodes` lorsqu'ils sont "pures", ou lorsqu'ils atteignent la limite (`max depth`), c'est-a-dire que la division qui va suivre ne sera pas favorable a l'apprentissage du modèle,plutôt à l'`overfitting`

Le "Naive Bayes" est un algorithme de classification en Machine Learning.


-----
***Théorème de Bayes***
Il  sert a calculer la probabilité qu'un évènement A ait lieu après un évènement B:
$$
P(A|B) = \frac{P(B|A) \times P(A)}{P(B)}
$$
- **P(A|B)** : Probabilité que A arrive dans les cas où B arrive (on prend B comme base)
- **P(A)** : Probabilité que A arrive en général (on prend le total comme base)
- **P(B|A)** : Probabilité que B arrive dans les cas où A arrive(on prend A comme base)
- **P(B)** : Probabilité que B arrive en général (on prend le total comme base)

----
***Naive Bayes***
L'algorithme bayésien naïf fonctionne en utilisant le théorème de Bayes. Il fonctionne en considérant que les "features" sont indépendantes les unes des autres, et enchaîne les multiplications en suivant la structure du `théorème de Bayes` 

Ensuite, celui-ci utilise le résultat de ces multiplications pour effectuer la `classification`
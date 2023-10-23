1) Mise en place de l’environnement de code
d) Manipuler les bibliothèques utiles
Numpy
ii)
La moyenne de la liste est : 1.49
L'écart type de la liste est : 0.87
La médiane de la liste est : 1.44

v)
Les deux liste sont généré de la même façon mais avec des valeurs différentes (à moins d'utiliser une graine(exemple : np.random.seed(0)) pour avoir les même valeurs) donc les moyennes, écarts type et médianes sont différents

xi)
Le noise fait penser à une parabole inversée


2) Données
b) Informations générales sur les données
i)
Il y a 469 motos et 447 voitures
ii)
Le format des images est : jpg
La taille des images est : 1080x1139

f) Séparation des sets d’entraînement et de test
iii)
Le random_state sert de "graine" afin d'avoir les mêmes données


3) Modèles de classification
a) Premier modèle de classification avec sklearn : arbre de décision
iv)
Pour prédire la première image du set de test il faut utiliser la méthode "predict" avec comme paramètre le premier élément de la liste que l'on veut prédire (exemple : clf.predict([X_test[0]]))

c) Evaluation
ii)
Pour le modèle 1, le nombre de motos classifiées comme une voiture est : 5
Le nombre de voitures classifiées comme une moto est : 8
Pour le modèle 2, le nombre de motos classifiées comme une voiture est : 5
Le nombre de voitures classifiées comme une moto est : 6


4) Comparaison de pipeline et fine tuning
a) Fine tuning du modèle 1
i)
La profondeur de l'arbre est de 7 couches
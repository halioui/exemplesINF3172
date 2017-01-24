makefiles
=========

Lors des travaux, il sera nécessaire de faire un makefile pour construire vos
logiciels. Cette matière ne sera pas couverte en classe, le moniteur va donc
vous expliquer les concepts relatifs à la création de makefiles :
* le programme make;
* les cibles;
* les dépendances (envers les autres cibles ou envers les fichiers);
* les options de compilation de gcc pour compiler en 2 étapes.

Objectifs
---------

* Utiliser le programme `make`.
* Développer des makefiles.

Exercices
---------

1. Créer un makefile pour compiler un programme avec un seul fichier source.
   (utiliser le programme hilo du premier atelier : https://github.com/jacquesberger/exemplesINF3172/blob/master/ateliers/environnement/enonce.md)

2. Créer un makefile pour compiler un programme avec plusieurs fichiers sources
   et en changeant le nom de l'exécutable.
   (diviser le programme hilo en deux functions readIntegerIn100.c (pour lire un entier entre 1 et 100) et isCorrectValue.c (pour vérifier si l'entier lu est égal au nombre aléatoire ) et une librairie hilo.h définissant ces deux fonctions)

3. Créer un makefile pour compiler un programme avec plusieurs fichiers sources
   en effectuant la compilation en deux étapes :
   * la compilation (génération des .o);
   * l'édition des liens (production de l'exécutable).

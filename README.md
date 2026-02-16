# Bienvenue

Programme C++ qui affiche "Bienvenue le monde !" en utilisant la fonction `afficherBienvenue()`.

## Fonctionnalités

- La fonction `afficherBienvenue()` peut recevoir :
  - un **message** à afficher (par défaut "Bienvenue le monde !")  
  - un **nombre de fois** que le message doit s’afficher (par défaut 1)

- Le programme principal `bienvenue.cpp` peut recevoir ces paramètres depuis la **ligne de commande**.

## Compilation

Pour compiler le programme :

```sh
$ make rebuild
Fabrication du programme : bienvenue
rm -f *.o
g++ -c -Wall -std=c++11 bienvenue.cpp
g++ -c -Wall -std=c++11 fonction-bienvenue.cpp
g++ -o bienvenue bienvenue.o fonction-bienvenue.o

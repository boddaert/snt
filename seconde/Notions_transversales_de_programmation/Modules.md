# Modules

## I. Définitions

Un *module* (ou *bibliothèque*) est un fichier Python contenant du code que nous pouvons utiliser en l'important dans notre propre fichier.

Le module `math` par exemple met à disposition toutes les fonctions mathématiques.

## II. Importation de module

Importer un module se fait avec l'instruction suivante :

```python
from math import *
```

Et ainsi, nous pouvons utiliser les fonctions mises à disposition dans ce module :

```python
from math import *
sqrt(5)
```

## III. Modules standards

### a) Module mathématique

Le module `math` possède toutes les fonctions mathématiques.

| Nom  du module : | `math` |
|---|---|
| Racine carrée | `sqrt` |
| Trigonométrie | `sin()`, `cos()` |
| Pi | `pi` |

Voir plus : [https://docs.python.org/fr/3.5/library/math.html](https://docs.python.org/fr/3.5/library/math.html)

### b) Module d'aléatoire

Le module `random` met à disposition plusieurs fonctions permettant d'obtenir de l'aléatoire.

| Nom du module : | `random` |
|---|---|
| Entier aléatoire | `randint` |


Voir plus : [https://docs.python.org/fr/3/library/random.html](https://docs.python.org/fr/3/library/random.html)

________

[Projet n°2 : Ecrire son prénom](./Projet_prénom.md)

________

[Sommaire](./../../seconde/)
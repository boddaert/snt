# Projet : Juste Prix

## I. Description

Le principe du jeu du Juste Prix est de deviner le prix de la vitrine en ayant à chaque essai une indication  si le nombre proposé est supérieur ou inférieur au prix de la vitrine.

## II. Cahier des charges

Vous devez écrire une fonction `jeu_Juste_Prix()` permettant de jouer au jeu du Juste Prix avec l'ordinateur.

Ce dernier choisira un entier aléatoire compris entre $0$ et $100$ et le joueur devra trouver le nombre caché.

>>> Vous pouvez obtenir un nombre aléatoire compris entre $0$ et $100$ en important le module `random` et en utilisant l'instruction `randint(0,100)`.

Voici un exemple d'affichage possible dans la console :

```python
>>> jeu_Juste_Prix()
Choisissez un nombre : 50
Le prix de la vitrine est supérieur.
Choisissez un nombre : 75
Le prix de la vitrine est inférieur.
Choisissez un nombre : 70
Le prix de la vitrine est supérieur.
Choisissez un nombre : 71
Bien joué !
```
________________

[Sommaire](./../README.md)
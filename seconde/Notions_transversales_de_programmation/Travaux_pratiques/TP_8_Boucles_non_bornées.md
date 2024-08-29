# Boucles non bornées

> [!WARNING]
> Répondre aux questions dans votre fichier `réponses_nom_prenom.txt`.

Une *boucle* permet de répéter des instructions.

Les *boucles non bornées* se répètent tant qu'une condition est vraie.

## I. Écrire une boucle non bornée

En Python, la boucle non bornée s'écrit pas le mot-clé `while` (*Tant que* en Français).

```python
a = 0
while a < 5 :
    a = a + 1
```

Nous pouvons traduire en Français le programme ci-dessus par : `Tant que a est inférieur à cinq, j'ajoute 1 à a`.

#### <ins>Exercice 1</ins>

Donner, pour chaque programme suivant, sa traduction en Français :

a) Programme 1 :

```python
a = 1
while a < 5 :
    a = a * 2
```

b) Programme 2 :

```python
a = 10
while a != 0 :
    a = a - 1
```

#### <ins>Exercice 2</ins>

Écrire une fonction `multiplie_par_cinq(a : int)->int` qui prend en paramètre un entier et renvoie le résultat de $a \times 5$. Cette fonction ne doit pas utiliser l'opérateur `*` : la stratégie est d'utiliser une boucle.

#### <ins>Exercice 3</ins>

Écrire une fonction `produit(a : int, b : int)->int` qui prend en paramètre deux entiers et renvoie le résultat de $a \times b$. Cette fonction ne doit pas utiliser l'opérateur `*` : la stratégie est d'utiliser une boucle.

______________

[Sommaire](./../../README.md)
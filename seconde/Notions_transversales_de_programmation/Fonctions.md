# Fonctions

## I. Définition

Une *fonction* est une séquence d'instruction réutilisable. Elle associe une séquence d'instruction à un nom.

Nous la distinguons des variables parce que le nom est suivi de parenthèses.

Elle réalise une tâche précise et peut dépendre de paramètres.

Par exemple, la fonction `type()` que nous avons vu au chapitre sur les types permet d'obtenir le type de la valeur passée en paramètre.

```python
>>> type(5)
<class 'int'>
```

### a) Signature

Soit `somme()` la fonction permettant de faire la somme de deux entiers.

Pour être un peu plus précis sur la définition d'une fonction, nous écrivons sa signature.

Ainsi, la signature de la fonction `somme()` s'écrirait : `somme(a : int, b : int) -> int`.

- Le nom est : `somme()`.

- Les paramètres sont $`a`$ et $`b`$ et sont tous les deux de type `int`.

- La valeur renvoyée par cette fonction est de type `int`.

La fonction `somme()` permet de faire la somme des entiers $a$ et $b$ passés en paramètres.

##### Exercice 1

Ecrire la signature de la fonction ``maximum()``qui prend en paramètres deux entiers $a$ et $b$ et renvoie comme résultat un entier.

### b) Paramètres

Une fonction peut avoir zéro ou plusieurs paramètres.

Un *paramètre* est le nom d'une variable utilisée à l'intérieur de la fonction.

## II. Ecriture de fonction

Une fonction en Python est composé de sa définition, d'un corps et d'un résultat.

### a) Définition d'une fonction en Python

Nous écrivons les fonctions en Python en utilisant le mot-cle : `def` suivi de la signature de la fonction suivi d'un `:`.

```python
def somme(a : int, b : int) -> int :
```

### b) Corps d'une fonction

Le *corps* d'une fonction est la séquence d'instruction située à l'intérieur.

Le corps d'une fonction est *indenté*, c'est-à-dire qu'il est légèrement décalé vers la droite.

```python
def somme(a : int, b : int) -> int :
    resultat = a + b
```

### c) Résultat d'une fonction

Le mot-clé `return` permet de renvoyer un résultat.

Cette instruction est toujours la dernière.

```python
def somme(a : int, b : int) -> int :
    resultat = a + b
    return resultat
```

##### Exercice 2

Ecrire, en Python, la fonction ``produit(a : int, b : int) -> int`` qui prend en paramètres deux entiers $a$ et $b$ et renvoie comme résultat $`a * b`$.

##### Exercice 3

Ecrire, en Python, la fonction `carre(n : int) -> int` qui prend en paramètres un entier $n$ et renvoie comme résultat $`n²`$.

## III. Appels de fonction

Lorsque nous utilisons une fonction pour obtenir un résultat, nous réalisons un *appel* à cette fonction.

Pour appeler une fonction, il suffit d'écrire le nom de la fonction avec, entre parenthèses, des arguments.

### a) Arguments

Paramètres et arguments ne définissent pas la même chose.

Un *argument* est la valeur que prend un paramètre lors d'un appel de fonction.

Ci-dessous, un exemple d'appel à la fonction `somme()` définie plus haut :

```python
>>> somme(5,2)
7
```

Les arguments sont $`5`$ et $`2`$.

Autrement dit, le paramètre $`a`$ a comme valeur $`5`$ et le paramètre $`b`$ a comme valeur $`2`$.

Il est important que le type de l'argument doit être le même que celui du paramètre.

##### Exercice 4

Vérifier la bonne réponse à l'exercice 2 en appelant la fonction dans la console Python plusieurs fois avec des arguments différents.

##### Exercice 5

Vérifier la bonne réponse à l'exercice 3 en appelant la fonction dans la console Python plusieurs fois avec des arguments différents.

##### Exercice 6

Donner le résultat des instructions suivantes :

a) Instruction 1

```python
>>> type(produit(3,4))
```

b) Instruction 2

```python
>>> a = somme(5,2)
>>> b = produit(3,4)
>>> c = a + b
>>> c
```

c) Instruction 3

```python
>>> somme(5, somme(3,2))
```
___________

[Sommaire](./../../seconde/)

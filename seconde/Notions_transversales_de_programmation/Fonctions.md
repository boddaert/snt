# Fonctions

Une *fonction* est une séquence d'instruction réutilisable. Elle associe une séquence d'instruction à un nom.

Nous la distinguons des variables parce que le nom est suivi de parenthèses.

Par exemple, la fonction `type()` permet d'obtenir le type de la valeur passée en paramètre :

```python
>>> type(5)
<class 'int'>
```

## I. Écrire une fonction dans un programme

Nous écrivons les fonctions en Python en utilisant le mot-cle : `def` suivi du nom de la fonction puis de paramètres entre parenthèses :

```python
def somme(a : int, b : int) -> int :
    ...
```

La fonction ci-dessus a comme :

- Nom : `somme`

- Paramètres : `a` et `b` tous deux de type entier naturel.

Un *paramètre* est le nom d'une variable utilisée à l'intérieur de la fonction.

Pour l'instant, le code à l'intérieur de la fonction est vide. Remplaçons les `...` par du code Python permettant de faire l'addition des paramètres et de renvoyer le résultat :

```python
def somme(a : int, b : int)->int :
    resultat = a + b
    return resultat
```

#### Exercice 1

Écrire, en Python, la fonction ``produit(a : int, b : int) -> int`` qui prend en paramètres deux entiers $a$ et $b$ et renvoie comme résultat $a \times b$.

#### Exercice 2

Écrire, en Python, la fonction `carre(n : int) -> int` qui prend en paramètre un entier $n$ et renvoie comme résultat $n^2$.

## II. Utiliser une fonction

Pour utiliser une fonction, il suffit d'écrire le nom de la fonction avec les valeurs que nous voulons utiliser à la place des paramètres.

Ci-dessous, un exemple d'utilisation dans la console de la fonction `somme()` définie plus haut :

```python
>>> somme(5,2)
7
```

Autrement dit, le paramètre `a` prend la valeur $5$ et le paramètre `b` prend la valeur $2$.

Il est important que le type de l'argument doit être le même que celui du paramètre.

#### Exercice 3

Utiliser dans la console la fonction `produit()` avec comme paramètres `6` et `3`.

#### Exercice 4

Utiliser dans la console la fontion `carre()` avec comme paramètre `5`.

#### Exercice 5

Sans utiliser la console, donner le résultat des instructions suivantes :

a) Instruction 1 :

```python
>>> type(produit(3,4))
...
```

b) Instruction 2 :

```python
>>> a = somme(5,2)
>>> b = produit(3,4)
>>> c = a + b
>>> c
...
```

c) Instruction 3 :

```python
>>> somme(5, somme(3,2))
...
```
___________

[Sommaire](./../../seconde/)

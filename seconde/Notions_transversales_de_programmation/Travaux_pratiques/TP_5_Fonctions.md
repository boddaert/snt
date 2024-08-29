# Fonctions

> [!WARNING]
> Répondre aux questions dans votre fichier `réponses_nom_prenom.txt`.

Une *fonction* est une séquence d'instruction réutilisable. Elle associe une séquence d'instruction à un nom.

## I. Écrire une fonction dans un programme

Nous écrivons les fonctions en Python en utilisant le mot-cle : `def` suivi du nom de la fonction puis de paramètres entre parenthèses :

```python
def somme(a : int, b : int)->int :
    resultat = a + b
    return resultat
```

La fonction ci-dessus a comme :

- Nom : `somme`

- Paramètres : `a` et `b` tous deux de type entier naturel.

Un *paramètre* est le nom d'une variable utilisée à l'intérieur de la fonction.

Son code permet d'additionner `a` et `b`, de placer le résultat dans une variable `resultat` et de la renvoyer.

#### <ins>Exercice 1</ins>

Écrire, en Python, la fonction ``produit(a : int, b : int) -> int`` qui prend en paramètres deux entiers $a$ et $b$ et renvoie comme résultat $a \times b$.

#### <ins>Exercice 2</ins>

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

#### <ins>Exercice 3</ins>

Utiliser dans la console la fonction `produit()` avec comme paramètres `6` et `3`.

#### <ins>Exercice 4</ins>

Utiliser dans la console la fontion `carre()` avec comme paramètre `5`.

#### <ins>Exercice 5</ins>

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

[Sommaire](./../../README.md)

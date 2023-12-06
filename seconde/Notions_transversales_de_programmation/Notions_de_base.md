# Notions de base

___________________

# Types

## I. Définitions

En Python, les valeurs ont des types. 

Nous appellons *valeur* toute donnée manipulable. Par exemple, $`42`$ et $`ù`$ sont des valeurs que l'on peut manipuler dans nos programmes.

Chaque valeur a un *type* qui la **caractérise**.

## II. Récapitulatif des types

| En Français | En Python | Exemples de valeurs |
| :---: | :---: | :---: |
| Entier naturel | `int` | $2$, $7$, $1000$ |
| Flottant | `float` | $3.14$, $8.0$, $78.78$ |
| Chaîne de caractères | `str` | `"bonjour a tous"`, `""`, `"coucou"` |
| Booléen | `bool` | $True$, $False$ |
| NoneType | `None` | `None` |

##### Exercice 1

a) Ouvrir Thonny.

b) Ecrire dans la console l'instruction `type(2)`.

c) Expliquer ce que fait la fonction `type()`.

d) En utilisant la fonction `type()`, vérifier le type des valeurs du tableau.

_______________________

# Opérateurs

## I. Définition

Un *opérateur* est un symbole permettant de réaliser une opération.

Comme sur la calculatrice classique, nous disposons les opérateurs entre des opérandes pour réaliser l'opération.

Les *opérandes* sont des valeurs ou des variables.

Par exemple dans l'exemple suivant, l'opérateur est `+` et les opérandes sont $`3`$ et $`6`$ :

```python
>>> 3 + 6
9
```

## II. Les différents opérateurs

### a) Opérateurs mathématiques

|   En Français    |   En Python   |
| --- | --- |
|   Addition    |`+`|
|   Soustraction | `-`|
|   Multiplication | `*` |
|   Division euclidienne | `/` |
|   Division entière    | `//` |
|   Puissance   |   `**` |
|   Modulo (reste de la division entière) |   `%` |

##### Exercice 2

Nous considèrons les expressions suivantes :

- `11 + 7`

- `11 * 7`

- `11 / 7`

- `11 // 7`

- `11 ** 7`

- `11 % 7`

a) Sur chacune des opérations ci-dessus et à l'aide de la console Python, donner leur résultat.

### b) Opérateurs de comparaison

|   En Français    |   En Python   |
| --- | --- |
|   Supérieur à |   `>` |
|   Inférieur à |   `<` |
|   Supérieur ou égal à |   `>=` |
|   Inférieur ou égal à |   `<=` |
|   Egal à |   `==` |
|   Différent de    |   `!=` |

##### Exercice 3

Nous considèrons les expressions suivantes :

- `11 > 7`

- `11 < 7`

- `11 >= 7`

- `11 <= 7`

- `11 == 7`

- `11 != 7`

a) Sur chacune des opérations ci-dessus et à l'aide de la console Python, donner leur résultat.

________________________

# Variables

## I. Définitions

Une *variable* est un nom qui possède une valeur.

On dit qu'une valeur est affectée à une variable.

## II. Affectations de variable

### a) Affectation simple

Nous pouvons affecter n'importe quelle valeur à une variable en Python avec l'opérateur d'affectation ``=`` :

```python
>>> ma_variable = 42
```

Pour connaître la valeur contenue dans une variable, il suffit de l'appeler :

```python
>>> ma_variable
42
```

### b) Ré-affectation

Pour modifier la valeur contenue dans une variable, j'affecte une nouvelle valeur à ma variable :

```python
>>> ma_variable = 42
>>> ma_variable
42
>>> ma_variable = 67
>>> ma_variable
67
```

L'ancienne valeur est alors écrasée par la nouvelle valeur.

##### Exercice 4

Dans la console python et en utilisant l'affectation, affecter :

- la variable `ma_variable_a` avec la valeur $`1`$
- la variable `ma_variable_b` avec la valeur $`9.99`$
- la variable `ma_variable_c` avec la valeur $`"hello world"`$
- la variable `ma_variable_d` avec la valeur $`True`$

Puis, vérifier en appelant chacune des variables les valeurs associées.

## III. Type d'une variable

Le type d'une variable est le type de la valeur qu'elle contient.

Nous pouvons, comme pour les valeurs, connaître le type des variables en utilisant la fonction ``type()`` :

```python
>>> type(ma_variable)
<class 'int'>
```

##### Exercice 5

Pour chacune des variables créées à l'application 1, vérifier leur type dans la console python en utilisant la fonction `type()`.

______________________

# Séquences d'instructions

Jusqu'à maintenant, nous avons essentiellement travaillé avec la console Python sur le mode interactif de Thonny.

Ce mode est très utile pour tester nos instructions mais celui-ci n'est pas destiné à écrire des programmes.

## I. Définitions

Un *programme informatique* est un texte composé d'intructions et d'opérations.

Une *instruction* désigne une étape dans un programme. Elle correspond à une action que l'ordinateur réalise lorsqu'il l'exécute.

Les programmes sont très souvent constitués de plusieurs instructions, cela constitue une *séquence d'instruction*.

On associe généralement une ligne de code à une instruction du programme.

## II. Ordre d'exécution

Lors de l'exécution d'une séquence d'instruction, l'ordinateur effectue les actions les unes après les autres dans l'ordre de lecture du programme. 

C'est à dire que l'instruction situé à la ligne $1$ sera exécutée en premier, puis celle située à la ligne $2$ en deuxième, et ainsi de suite ...

Nous pouvons le vérifier très facilement en écrivant un programme comportant une séquence d'instruction dans l'éditeur de texte de Thonny :

```python
a = 10
a = a + 1
```

Puis, après exécution, en vérifiant la valeur affectée à la variable `a` dans la console Python :

```python
>>> a
11
```

##### Exercice 6

Recopier le programme de l'exemple précédent et vérifier à votre tour la valeur affectée à la variable `a` dans la console Python.

_______

[Leçon n°4 : Fonctions](./Fonctions.md)

_______

[Sommaire](./../../seconde/)

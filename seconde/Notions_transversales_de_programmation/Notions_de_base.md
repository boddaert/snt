# Notions de base

___________________

## I. Types

En Python, les valeurs ont des types. 

Nous appellons *valeur* toute donnée manipulable. Par exemple, $`42`$ et $`ù`$ sont des valeurs que l'on peut manipuler dans nos programmes.

Chaque valeur a un *type* qui la **caractérise**.

Voici ci-dessous un tableau récapitulant les types présents en Python :

| En Français | En Python | Exemples de valeurs |
| :---: | :---: | :---: |
| Entier naturel | `int` | $2$, $7$, $1000$ |
| Flottant | `float` | $3.14$, $8.0$, $78.78$ |
| Chaîne de caractères | `str` | `"bonjour a tous"`, `""`, `"coucou"` |
| Booléen | `bool` | $True$, $False$ |

#### Exercice 1

a) Ouvrir Thonny.

b) Ecrire dans la console les instructions `type(2)` et `type("bonjour")`

c) En déduire sur ce que fait la fonction `type()`.

d) Tester la fonction `type()` avec quelques valeurs du tableau.

_______________________

## II. Opérateurs

### a) Opérateurs mathématiques

|   En Français    |   En Python   |
| --- | --- |
|   Addition    |`+`|
|   Soustraction | `-`|
|   Multiplication | `*` |
|   Division euclidienne | `/` |
|   Division entière    | `//` |
|   Puissance   |   `**` |

#### Exercice 2

Nous considèrons les expressions suivantes :

- `11 + 7`

- `11 / 7`

- `11 // 7`

- `11 ** 7`

Sur chacune des opérations ci-dessus et à l'aide de la console Python, donner leur résultat.

### b) Opérateurs de comparaison

|   En Français    |   En Python   |
| --- | --- |
|   Supérieur à |   `>` |
|   Inférieur à |   `<` |
|   Supérieur ou égal à |   `>=` |
|   Inférieur ou égal à |   `<=` |
|   Egal à |   `==` |
|   Différent de    |   `!=` |

#### Exercice 3

Nous considèrons les expressions suivantes :

- `11 > 7`

- `11 < 7`

- `11 == 7`

- `11 != 7`

Sur chacune des opérations ci-dessus et à l'aide de la console Python, donner leur résultat.

________________________

## III. Variables

Une *variable* est un nom qui possède une valeur. Une variable peut être assimilée à une boîte dans laquelle nous y mettons une valeur.

Nous pouvons donner une valeur à une variable en Python avec un ``=`` :

```python
>>> ma_variable = 42
```

Pour connaître la valeur contenue dans une variable, il faut l'appeler :

```python
>>> ma_variable
42
```

#### Exercice 4

a) Dans la console python, affecter la variable `ma_variable` avec la valeur `9.99`.

b) Vérifier le contenu de `ma_variable` en l'appelant dans la console.

c) Affecter la valeur `"hello world"` à la variable `ma_variable`, puis re-vérifier son contenu. Qu'en est-il de l'ancienne valeur ?

______________________

## IV. Écrire un programme

Jusqu'à maintenant, nous avons essentiellement travaillé avec la console Python sur le mode interactif de Thonny.

Ce mode est très utile pour tester nos instructions mais celui-ci n'est pas destiné à écrire des programmes.

#### Exercice 6

```python
a = 10
a = a + 1
```

a) Recopier le programme précédent dans le mode d'édition de Thonny.

b) Exécuter le programme en cliquant sur le bouton d'exécution.

c) Dans la console, vérifier le contenu de la variable `a`.

_______

[Sommaire](./../../seconde/)

# Instructions conditionnelles

Une *instruction conditionnelle* est une instruction permettant d'exécuter certaines instructions uniquement si la condition est remplie.

Si la condition n'est pas remplie, la suite du programme est exécutée normalement.


## I. Écrire une instruction conditionnelle

En Python, l'instruction conditionnelle s'écrit par le mot-clé ``if`` (*Si* en Français):

```python
if 3 > 6 :
    a = 5
```

Nous pouvons traduire en Français le programme ci-dessus par : `Si trois est supérieur à six alors je met la valeur cinq dans la variable a`.

#### Exercice 1

Donner, pour chaque programme suivant, sa traduction en Français :

a) Programme 1 :

```python
if a < b :
    a = a + b
```

b) Programme 2 :

```python
if a != b :
    a = b
a = a * 2
```

#### Exercice 2

Écrire une fonction `quotient(a : int, b : int)->float` qui prend en paramètre deux entiers et renvoie le résultat de $a/b$. Attention, la division par $0$ n'est pas possible.

## II. Alternative

L'instruction conditionnelle peut introduire une alternative, à n'exécuter que lorsque la condition est fausse.

En Python, l'instruction d'alternative s'écrit avec le mot-clé ``else`` (*Sinon* en Français) :

```python
if 3 > 6 :
    a = 5
else :
    a = 3
```

Nous pouvons traduire en Français le programme ci-dessus par : `Si trois est supérieur à six alors je met la valeur cinq dans la variable a, sinon, je met la valeur trois dans la variable a`.

#### Exercice 3

Donner, pour chaque programme suivant, sa traduction en Français :

a) Programme 1 :

```python
if a == b :
    a = a // 2
else :
    b = b // 2
```

b) Programme 2 :

```python
if a < b :
    b = b - 1
else :
    a = a - 1
```

#### Exercice 4

Donner, pour la phrase suivante, le programme Python correspondant : `Si a est supérieur à b alors je met la valeur dix dans la variable a, sinon, je met la valeur cinq dans la variable a`.

_________________________

[Sommaire](./../../seconde/)

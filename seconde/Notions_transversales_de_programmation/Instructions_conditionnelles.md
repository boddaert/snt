# Instructions conditionnelles

## I. Définitions

Une *instruction conditionnelle* est une instruction permettant d'exécuter certaines instructions uniquement si la condition est remplie.

Une *condition* est un booléen, elle peut être le résultat d'une comparaison.

Une condition vaut donc soit $True$, soit $False$.

Une condition est remplie si elle vaut $True$.

Si la condition n'est pas remplie, la suite du programme est exécutée normalement.


### a) Syntaxe en Python

En Python, l'instruction conditionnelle s'écrit par le mot-clé ``if`` (*Si* en Français):

```python
if a == 0 :
    a = a + 1
b = a
```

Nous constatons que la séquence d'instruction, exécutée si la condition est vraie, est indentée.

En Français, cela se traduirait :

- *Si* `a` est égal à $0$, alors nous ajoutons $1$ à `a`.

- Nous affectons à la variable `b` la valeur de `a`.

##### Exercice 1

Donner, pour chaque programme suivant, sa traduction en Français :

a) Programme 1

```python
if a != b :
    a = b
a = a * 2
```

b) Programme 2

```python
if a or b :
    a = True
    b = True
```

## II. Alternative

L'instruction conditionnelle peut introduire une séquence d'instruction alternative, à n'exécuter que lorsque la condition est fausse.


### a) Syntaxe en Python

En Python, l'instruction d'alternative s'écrit avec le mot-clé ``else`` (*Sinon* en Français) :

```python
if a == 0 :
    a = a + 1
else :
    a = a + 3
b = a
```

En Français, cela se traduirait :

- *Si* `a` est égal à 0, alors nous ajoutons $1$ à `a`.

- *Sinon*, nous ajoutons $3$ à `a`.

- Nous affectons à la variable `b` la valeur de `a`.

##### Exercice 2

Donner, pour chaque programme suivant, sa traduction en Français :

a) Programme 1

```python
if a == b :
    a = a // 2
else :
    b = b // 2
```

b) Programme 2

```python
if a < b :
    b = b - 1
else :
    a = a - 1
a = a * 2
b = b * 2
```

_________________________

[Projet n°3 : Chi Fu Mi](./Projet_chi_fu_mi.md)

_________________________

[Sommaire](./../../seconde/)

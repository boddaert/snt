# Introduction

## I. L'informatique

En Sciences Numériques et Technologiques, nous allons être amenés à écrire des programmes informatiques.

Un *programme informatique* est un texte composé d'instructions et d'opérations écrit dans un certain langage de programmation et destiné à être exécuté par un ordinateur.

L'*informatique* est la science des **données**, les programmes informatiques que nous écrivons nous permettent de manipuler ces données et d'effectuer des calculs sur celles-ci.

Pour nous aider à écrire des programmes informatiques, les informaticiens utilisent des algorithmes. Un algorithme est une suite d'instructions écrit en Français. Il sert à **résoudre un problème**.

L'objectif de construire un algorithme est qu'il soit compris par tous et qu'on puisse le traduire dans n'importe quel langage de programmation.

Un algorithme est comparable à une recette de cuisine.

Par exemple :

```
Recette Mayonnaise
- Mettre un jaune d'oeuf dans un bol
- Y ajouter une cuillière de moutarde
- Tant que la préparation est liquide :
    - Ajouter une cuillière à soupe d'huile.
    - Fouetter la préparation.
```
## II. Langage de programmation

Un *langage de programmation* est un langage dans lequel nous allons écrire notre programme.

Comme nos langues naturelles, un langage de programmation est composé d'un alphabet et de règles.

On distingue une multitude de langages comme le Java, le C++, le HTML, le CSS, le SQL, etc ...

![](./img/langages.png)

## III. Le Python

En SNT, nous travaillerons avec le langage Python principalement. Il a été inventé en 1989 par le néerlandais Guido Van Rossum et est aujourd'hui l'un des lagages les plus utilisés au monde.

![](./img/python_logo.png)

## IV. L'explorateur de fichiers

### a) Arborescence

Dans la mémoire d'un ordinateur, les données sont organisées sous la forme d'une arborescence représentant une hierarchie de répertoires et de fichiers :

- :file_folder: `C:`
    - :file_folder: `perso`
        - :page_rancing_up: `cv.odt`
        - :file_folder: `photos`
            - :page_rancing_up: `moi.png`
    - :file_folder: `lycee`
        - :file_folder: `cours`
            - :file_folder: `snt`
                - :page_rancing_up: `lecon1.odt`

Un *dossier* ou *répertoire* peut contenir des fichiers ou d'autres répertoires.

Un *fichier* est un contenant d'informations et possède en plus du répertoire une extension.

L'extension indique de quel type de fichier il s'agit (par exemple : `.png` pour les images).

Une arborescence est toujours constituée d'un dossier racine, sur le système Windows il s'agit de `C:`.

### b) Chemins

Pour représenter un fichier, nous indiquons généralement le chemin vers ce fichier.

Il existe deux types de chemins :

- Celui depuis la racine, appelé *chemin absolu*.
- Celui depuis l'endroit où nous sommes, appelé *chemin relatif*.

Le chemin se construit en donnant tous les répertoires à traverser pour arriver jusqu'à destination.

Les noms de répertoires sont séparés par des `/`.

`..` représente le répertoire parent.

Par exemple :

- Chemin absolu du fichier `moi.png` : `C:/perso/photos/moi.png`.
- Chemin relatif du fichier `moi.png` depuis le répertoire `cours` : `../perso/photos/moi.png`

##### Application 1

Donner le chemin absolu du fichier :

- `cv.odt`.
- `lecon1.odt`.

Donner le chemin relatif depuis le répertoire `photos` du fichier :

- `cv.odt`.
- `lecon1.odt`.

________

[Sommaire](./../../seconde/)
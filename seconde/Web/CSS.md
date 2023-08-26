# Langage CSS

## I. Définition

Le langage CSS (*Cascading Style Sheets*) que nous pouvons traduire en Français par "feuille de style en cascade" est le langage utilisé pour mettre en forme du contenu HTML.

Il permet d'appliquer des styles sur différents éléments sélectionnés dans un document HTML.

## II. Syntaxe d'un règle CSS

Une règle CSS est une règle de style appliqué à un sélecteur encadré par des accolades.

Le *sélecteur* correspond à un élément HTML présent dans le document.

Par exemple, voici ci-dessous une règle CSS appliquant la couleur rouge à tous les éléments paragraphe dans le document :

```css
p {
    color : red;
}
```

`p` est alors le sélecteur et `color : red;` est la règle.

## III. Intégration d'une feuille CSS à un document HTML

Pour faire le lien entre le document HTML et la feuille de style CSS qui sont deux fichiers différents, il faut ajouter dans la balise `head` du document HTML le lien vers le fichier CSS.

Par exemple, si ma feuille de style se nomme `style.css` :

```html
<link href="style.css" rel="stylesheet" type="text/css" />
```

## IV. Sélecteurs de classes et d'ID

Il est possible d'appliquer un style uniquement à certains éléments HTML en particulier en utilisant les sélecteurs spéciaux.

|| Sélecteur de classe | Sélecteur d'ID |
| --- | --- | --- |
| Description | Style appliqué à tous les éléments d'une page appartenant à la même classe. | Style appliqué à l'unique élément d'une page appartenant à l'identificateur. |
| Syntaxe dans le document HTML |  `<p class="menu">...</p>` | `<p id="2">...</p>` |
| Syntaxe dans la feuille de style CSS | `.menu { ... }` | `#2 { ... }` | 

## V. Activité 1

a) Dans le logiciel `notepad++`, créer un nouveau fichier situé dans le même répertoire que votre document HTML et que vous nommerez `votre-nom_presentation` suivi de l'extension `.css`.

b) Ajouter dans la balise `head` de votre document HTML le lien vers votre fichier CSS.

b) Ajouter la règle de CSS vue dans le `b)` de cette leçon dans votre fichier CSS et vérifier si les paragraphes apparaissent bien en rouge.

d) A l'aide de la documentation officielle du langage CSS (trouvable sur [https://www.w3schools.com/css/default.asp](https://www.w3schools.com/css/default.asp)), ajouter de la mise en forme sur votre document de présentation pour qu'il contienne au moins :

- Des textes de couleur différente.
- Des arrières-plan de texte de couleur différente.
- Des textes alignés à gauche.
- Des textes alignés à droite.
- Des textes centrés.
- Des textes de police différente.
- Des textes de taille de police différente.
- Une taille et une couleur des bordures d'un tableau différente.
- Une taille et une couleur des bordures d'une `div`.

_____________

[Sommaire](./../../seconde/)
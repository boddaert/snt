# Langage HTML

## I. Définition

Le langage HTML (*HyperText Markup Language*) que nous pouvons traduire en Français par "langage de balisage hypertexte" est le langage utilisé pour structurer une page web et son contenu.

Nous pouvons par exemple organiser le contenu en un ensemble de paragraphes, une liste d'éléments, utiliser des images ou des tableaux.

## II. Syntaxe de balise

Les contenus sont encadrés de *balises* indiquant de quel type de contenu il s'agit et cela constitue un *élément HTML*.

Par exemple, l'élément suivant représente un paragraphe :

```html
<p>Ceci est un paragraphe</p>
```

Nous distingons les balises ouvrantes et fermantes.

## III. Imbrication de balise

Nous pouvons imbriquer les balises pour ajouter un type à un contenu.

Par exemple, l'élément suivant présente du contenu de type paragraphe et gras :

```html
<p>Ceci est un <b>paragraphe gras</b></p>
```

Il faut cependant faire attention à imbriquer correctement les balises.

## IV. Squelette d'un document HTML

Un document HTML est organisé d'une façon précise. 

Tous les éléments du document sont contenus dans une balise `html`.

Le document est divisé en deux parties :

- Il y a la tête, contenue dans une balise `head` comprenant les *métadonnées*, c'est-à-dire les données qui ne sont pas affichées à l'écran. Il y a par exemple, l'encodage des caractères utilisé et le titre de la page.

- Et le corps, contenu dans une balise `body` comprenant les éléments qui sont affichés sur la page web.

Voici ci-dessous, un exemple de squelette d'un document HTML :

```html
<!doctype html>
<html lang="fr">
  <head>
    <meta charset="utf-8" />
    <title>Ma page de test</title>
  </head>
  <body>
    <p>test</p>
  </body>
</html>
```

## V. Mémo des balises HTML

| Nom de la balise | Syntaxe HTML | Aperçu |
| --- | --- | --- |
| Titre de taille cinq | `<h5>Titre</h5>` | <h5>Titre</h5> |
| Titre de taille quatre | `<h4>Titre</h4>` | <h4>Titre</h4> |
| Titre de taille trois| `<h3>Titre</h3>` | <h3>Titre</h3> |
| Titre de taille deux | `<h2>Titre</h2>` | <h2>Titre</h2> |
| Titre de taille un | `<h1>Titre</h1>` | <h1>Titre</h1> |
| Paragraphe | `<p>paragraphe</p>` | <p>paragraphe</p> |
| Lien hypertexte | `<a href="https://github.com/boddaert/snt">lien</a>` | <a href="https://github.com/boddaert/snt">lien</a> |
| Image | `<img src="https://urlr.me/3jLD4">` | <img src="https://urlr.me/3jLD4"> |
| Texte gras | `<b>Texte gras</b>` | <b>Texte gras</b> |
| Texte italique | `<i>Texte italique</i>` | <i>Texte italique</i> |
| Liste à puces numérotée | `<ol> <li>Premier</li> <li>Deuxième</li> </ol>` | <ol> <li>Premier</li> <li>Deuxième</li> </ol> |
| Liste à puces non numérotée | `<ul> <li>Premier</li> <li>Deuxième</li> </ul>` | <ul> <li>Premier</li> <li>Deuxième</li> </ul> |
| Tableau | `<table><tr><th>Première colonne</th><th>Deuxième colonne</th></tr><tr><td>Première ligne</td><td>Première ligne</td></tr><tr><td>Deuxième ligne</td><td>Deuxième ligne</td></tr></table>` | <table><tr><th>Première colonne</th><th>Deuxième colonne</th></tr><tr><td>Première ligne</td><td>Première ligne</td></tr><tr><td>Deuxième ligne</td><td>Deuxième ligne</td></tr></table> |

________________

[Sommaire](./../../README.md)
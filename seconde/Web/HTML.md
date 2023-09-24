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

## IV. Structure d'un document HTML

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
    ...
  </body>
</html>
```

## V. Mémo des balises

| Nom des balises | Syntaxe HTML | Aperçu |
| --- | --- |
| Titre de taille cinq | `<h5>Titre</h5>` | <h5>Titre</h5>

Consigne : Construire une page web vous présentant (: nom, âge, loisirs, desserts préférés,  artistes préférés, etc...) en utilisant le langage HTML.

a) Ouvrir le logiciel `notepad++` et copier sur l'éditeur de texte le squelette du document HTML.

b) Enregistrer sous le fichier dans votre espace de travail sous la forme `votre-nom_presentation` suivi de l'extension `.html`.

c) Vérifier votre code dans le navigateur en cliquant sur l'onglet `Affichage` puis de `Afficher le fichier dans` et choisir `Firefox`.

d) A l'aide de la documentation officielle du langage HTML (trouvable sur [https://www.w3schools.com/tags/default.asp](https://www.w3schools.com/tags/default.asp)), compléter votre présentation pour qu'il contienne au moins :

- Un titre de taille $1$, puis $2$, puis $3$.
- Un paragraphe.
- Un mot souligné.
- Un mot en gras.
- Un mot en italique.
- Un lien hypertexte.
- Une image.
- Une liste à puces numérotée.
- Une liste à puces non numérotée.
- Un texte mise dans un bloc `div`.
- Un tableau à plusieurs colones et plusieurs lignes.

________________

[Sommaire](./../README.md)
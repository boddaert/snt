# Page Rank

## I. Résultats d'une recherche

Vous disposez de six textes.

L’objectif est de comprendre comment un moteur de recherche classerait ces textes en fonction des mots-clés utilisés pour la recherche.

Texte n°1 :
```
Les premiers ordinateurs ont été conçus dans les années 1940 pendant la seconde guerre mondiale. Ils permettaient principalement de faire de grosses multiplications.

Deux technologies ont émergé simultanément, l’une utilisait des relais électromécaniques, l’autre des tubes à vides qui les rendaient entièrement électroniques.

• 1941 : le Z3 (Allemagne), binaire, électromécanique, programmable à l’aide de rubans perforés.

• 1944 : le Colossus Mark 1 (Royaume-Uni), binaire, électronique, programmable à l’aide de câbles et commutateurs.

• 1944 : le Mark I d’IBM (Etats-Unis), décimal, électromécanique, programmable à l’aide de rubans perforés.

• 1945 : l’ENIAC (Etats-unis), décimal, électronique, programmable à l’aide de câbles et commutateurs.

Petit à petit, les relais électromécaniques ont été abandonnés au profit des machines entièrement électroniques, plus rapides et plus fiables.
```

Texte n°2 :
```
ARPANET ou Arpanet (acronyme anglais de « Advanced Research Projects Agency Network », souvent typographié « ARPAnet ») est le premier réseau à transfert de paquets développé aux États-Unis par la DARPA. Le projet fut lancé en 1966, mais ARPANET ne vit le jour qu'en 1969. Sa première démonstration officielle date d'octobre 1972.
```

Texte n°3 :
```
Le World Wide Web Consortium, abrégé par le sigle W3C, est un organisme de standardisation à but non lucratif, fondé en octobre 1994 chargé de promouvoir la compatibilité des technologies du World Wide Web telles que HTML5, HTML, XHTML, XML, RDF, SPARQL, CSS, XSL, PNG, SVG et SOAP. Fonctionnant comme un consortium international, il regroupe au 26 février 2013, 383 entreprises partenaires.
Le leitmotiv du W3C est « Un seul web partout et pour tous ».
```

Texte n°4 :
```
L’idée d’un réseau informatique permettant à différents ordinateurs de communiquer s'est développée étape par étape jusqu'au « réseau des réseaux » (network of networks) que nous connaissons aujourd’hui sous le nom d'Internet.

L'histoire commence dans les années 1960 avec la mise au point des premières communications numériques (premiers modems, premiers protocoles de communication, puis le premier réseau appelé ARPANET).

Internet s'ouvre au grand public dans les années 1990 avec la naissance du World Wide Web (système de pages hypertextes accessibles sur des sites par l'intermédiaire d'Internet) et sa mise dans le domaine public.

Dans les années 2000, l'essor d'Internet se poursuit grâce au développement des technologies (du matériel et des protocoles), ainsi qu'au regroupement progressif des infrastructures réseau.

Aujourd'hui Internet est mondial, donnant un accès généralisé à l'information et aux communications.
```

Texte n°5 :
```
• Ordinateur : Un ordinateur est une machine électronique de traitement de l'information, capable de classer, calculer et mémoriser, exécutant à grande vitesse les instructions d'un programme.

• Internet : Internet est le réseau informatique mondial, accessible au public. Il est composé de millions de réseaux interconnectés, sans centre névralgique. L'information y est transmise grâce à un ensemble standardisé de protocoles qui permettent une grande variété d'applications : courriels, messagerie, World Wide Web...

• Réseau informatique : Un réseau informatique est un ensemble d'équipements informatiques reliés entre eux pour échanger des informations.
```

Texte n°6 :
```
L'intelligence artificielle est historiquement définie par l’un de ses créateurs, Marvin Lee Minsky, comme « la construction de programmes informatiques qui s’adonnent à des tâches qui sont, pour l’instant, accomplies de façon plus satisfaisante par des êtres humains car elles demandent des processus mentaux de haut niveau tels que : l’apprentissage perceptuel, l’organisation de la mémoire et le raisonnement critique ».
```

a) En expliquant votre choix, classez les textes du plus pertinent au moins pertinent si la requête était "les réseaux".

b) En expliquant votre choix, classez les textes du plus pertinent au moins pertinent si la requête était "les ordinateurs".

c) Pourquoi est-il important pour une page web d'être en tête d'un classement de recherche ?

## II. Des robots pour classer

Pour classifier les pages, les moteurs de recherche envoient des robots informatiques (programmes) sur le web.

Ces robots explorent en visitant les pages du web, trient et classifient les pages selon certaines informations.

Il existe trois méthodes de classement :

- Le *classement par pertinence*, qui évalue entre autres le nombre de fois que le mot-clé recherché apparaît dans une page web.

- Le *classement par popularité*, comme le `PageRank` de Google, qui note la popularité d'une page web.

- Le *classement par rapport à l'audiance*, qui évalue le temps resté par l'internaute sur une page web.
 
## III. Activité

Par groupe de deux.

L'objectif de l'activité est de comprendre comment l'algorithme `PageRank` de Google parvient à trier les pages web selon leur popularité.

### Algorithme PageRank

*Matériel : un plateau, un dé et un pion.*

L'algorithme de `PageRank` consiste :

```
1. Choisir une page de départ aléatoirement entre toute les pages du web en lançant le dé et placer le pion sur la page correspondante.

2. Lancer le dé. Si le numéro tiré correspond à une page directement accessible (en ne traversant qu'une seule flèche), alors :

  + Visiter cette page en déplaçant le pion dessus.

  + Augmenter le nombre de visite à cette page de $1$, et le noter.

3. Répéter l'étape 2.

Si un seul choix est possible, ne lancez pas le dé et allez directement sur la page. 
```

### Questions

a) Recopier sur votre feuille le plateau contenant six pages web, les flèches indiquent qu'il est possible de passer d'une page à une autre en cliquant sur un hyperlien présente sur celle-ci.

b) Recopier également le tableau des visites.

c) Appliquer l'algorithme de `PageRank` sur le plateau pendant une dizaine minutes.

d) Donner l'ordre de popularité des pages.

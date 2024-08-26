# Page Rank

## I. Résultats d'une recherche

a) Sur votre téléphone portable, effectuer la recherche `"Apollo 11"` sur les trois moteurs de recherche proposés et compléter le tableau suivant avec vos résultats de recherche :

| Moteur de recherche | Présence d'une annonce de publicité en tête des résultats| Position du lien vers Wikipédia  | Position du premier lien vers le film "Apollo 11" |
| --- | --- | --- | --- |
| Google | | | | 
| Qwant | | | | 
| DuckDuckGo | | | | 

b) Essayer d'expliquer pourquoi le classement des résultats est différent selon les moteurs de recherche.

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

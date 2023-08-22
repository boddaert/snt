# Moteurs de recherche

## a) Définition

Un *moteur de recherche* est une application web.

Les moteurs de recherche permettent de trouver des informations dans des pages web dont nous ne connaissons pas l'adresse, voire dont nous ignorons l'existance.

Usuellement, nous tapons quelques mots-clés dans la barre de recherche et plusieurs liens hypertextes sont affichés.

Voici ci-dessous un graphique présentant la part du marché des différents moteurs de recherche en France en 2020 :

![Moteurs de recherche les plus utilisés en France, en février 2020 - Statcounter.com](./img/graphique_moteurs_de_recherche.png)

## b) Activité 1

a) Effectuer la recherche `Apollo 11` sur les trois moteurs de recherche proposés et compléter le tableau suivant avec vos résultats de recherche :

| Moteur de recherche | Présence d'une annonce de publicité en tête des résultats| Position du lien vers Wikipédia | Position du premier lien vers un média culturel | Position du premier lien vers le film Apollo 11 |
| --- | --- | --- | --- | --- |
| Google | | | | |
| Qwant | | | | |
| Yahoo! | | | | |
| DuckDuckGo | | | | |

b) Essayer d'expliquer pourquoi le classement des résultats est différent selon les moteurs de recherche.

c) Quel moteur de recherche conseillerez-vous ?

d) Pourquoi est-il important pour une page web d'être en tête d'un classement de recherche ?

## c) Des robots pour classer

Pour classifier les pages, les moteurs de recherche envoient des robots informatiques (programmes) sur le web.

Ces robots explorent en visitant les pages du web, trient et classifient les pages selon certaines informations.

Ces algorithmes de classement ne sont pas connus exactement puisqu'ils sont considérés comme des secrets industriels.

Il existe trois méthodes de tri :

- Le *tri par pertinence*, qui évalue entre autres le nombre de fois que le mot-clé recherché apparaît dans une page web.

- Le *tri par popularité*, comme le `PageRank` de Google, qui note la popularité d'une page web.

- Le *tri par rapport à l'audiance*, qui évalue le temps resté par l'internaute sur une page web.
 
## d) Activité 2

Par groupe de deux ou trois.

L'objectif de l'activité est de comprendre comment l'algorithme `PageRank` de Google parvient à trier les pages web selon leur popularité.

Ci-dessous plusieurs plateaux représentant schématiquement le web.

Les sommets représentent les pages web, et les liens entre les sommets représentent les liens hypertexte vers cette page.

### Plateau 1

```mermaid
  graph LR;
      1-->2;
      2-->1;
      1-->3;
      3-->1;
      3-->2;
```

### Plateau 2

```mermaid
  graph LR;
      1-->2;
      2-->2;
      1-->3;
      3-->2;
      3-->1;
      3-->4;
```

### Plateau 3

```mermaid
  graph LR;
      1-->2;
      2-->1;
      1-->3;
      3-->1;
      3-->2;
      4-->2;
```

### Algorithme PageRank

L'algorithme de `PageRank` consiste :

1. Premièrement à choisir une page aléatoirement entre toute les pages du web.

2. Choisir aléatoirement la prochaine page en fonction des références.

3. Visiter cette page.

4. Augmenter le nombre de visite à cette page de 1, et le noter.

5. Reprendre à partir de l'étape 2.

### Questions

a) Dessiner suffisamment grand les trois plateaux sur une feuille.

b) Appliquer l'algorithme de `PageRank` sur le plateau 1 pendant cinq minutes et donner vos résultats.

c) Il n'est pas impossible qu'une page web ne fasse référence vers aucune autre. Quelle page est concernée sur le plateau 2 ?

d) Proposer une légère modification à l'algorithme pour pallier à ce problème.

e) Appliquer de nouveau l'algorithme de `PageRank` modifié pendant cinq minutes sur le plateau 2 et donner vos résultats.

f) Il n'est pas impossible qu'aucune page web fasse référence vers une autre page en particulier. Quelle page est concernée sur plateau 3 ?

g) Proposer une légère modification à l'algorithme pour pallier à ce problème.

h) Appliquer de nouveau l'algorithme de `PageRank` modifié pendant cinq minutes sur le plateau 3 et donner vos résultats.

_______________

Leçon 5 : [Navigateurs](./Navigateurs.md)
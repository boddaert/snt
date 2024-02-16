# Fonctionnement Internet

## I. Définitions

a) Compléter les définitions ci-dessous à l'aide des mots suivants :

`routage`, `adresse symbolique`, `repérer`, `rapidement`, `protocole DNS`, `adresse`, `itinéraire`

1. Sur Internet, les équipements informatiques possèdent une ............  pour pouvoir les ............  dans le réseau.

Nous appelons cette adresse : l'*adresse IP*.

2. Le ............ des données est le calcul de l'............  le plus efficace pour que les données arrivent à destination le plus ............ possible.

3. Une  ............ (aussi appelée *URL*) est une adresse constituée de mots et menant vers une ressource web. Par exemple : https://fr.wikipedia.org/wiki/Informatique est une adresse symbolique.

4. Les adresses symboliques sont en réalité des adresses IP et le ............ (pour *Domain Name System*) se charge de les transformer en adresses compréhensibles par les utilisateurs d'Internet.

## II. Routage des données

Le routage des données est très similaire au routage d'un courrier sur le réseau postal.

b) Mettre dans l'ordre les différentes étapes de l'acheminement d'un courrier de l'émission jusqu'à la reception de celui-ci :

- Calcul de l'itinéraire à emprunter.

- Acheminement du courrier vers la ville de destination.

- Écriture du courrier.

- Acheminement du courrier vers le centre de tri le plus proche de la destination.

- Écriture de l'adresse de destination sur l'enveloppe et collage du timbre sur l'enveloppe.

- Récupération du courrier par le destinataire.

- Acheminement du courrier vers le centre de tri le plus proche de chez vous.

- Déposition du courrier dans la boîte aux lettres de votre rue.

- Déposition du courrier dans la boîte aux lettres du destinataire par le facteur.

- Récupération du courrier par votre facteur.

c) En déduire la similitude avec les équipements informatiques du réseau Internet :

| ---------Internet---------| ---------Postal----------- |
| :--- | ---: |
| **Réseau Internet -** | **- Adresse postale** |
| **Routeur -** | **- Boîte aux lettres** |
| **Commutateur -** | **- Courrier** |
| **Données -** | **- Réseau postal** |
| **Adresse IP -** | **- Centre de tri** |

## III. Calcul du meilleur itinéraire

À l'aide du document projeté au tableau, répondre aux questions suivantes :

1. Que peuvent représenter les nombres à côté des connexions ? Donner au moins deux exemples.
......................................................................................................................

2. Dans cette question, on considère que le meilleur chemin est celui qui passe par le moins d'arêtes possible. Indiquer le meilleur itinéraire à suivre depuis la machine `A` vers la machine `B`.
......................................................................................................................

3. Dans cette question, on considère que le meilleur chemin est celui pour lequel la somme des poids des arêtes est la plus petite. Indiquer le meilleur itinéraire à suivre depuis la machine `A` vers la machine `B`.
......................................................................................................................

## IV. Adressage des machines

Une adresse IP est une suite de quatre nombres allant de `0` à `255` et s'écris sous la forme : `128.76.0.2`

Chaque adresse est unique.

L'adressage des adresses IP est le fait d'attribuer une adresse IP à un ensemble d'ordinateurs.

d) L'adressage des numéros de téléphone fixe en France fonctionne :

Le premier numéro de téléphone fixe représente la région où nous nous trouvons.

Le deuxième numéro de téléphone fixe représente le département où nous nous trouvons.

Le troisième, la ville, etc ...

Donner une stratégie similaire à celle des numéros de téléphone fixe permettant d'attribuer une adresse IP unique pour chaque élève de la classe.
............................................................................................................................................................................................................................................

## V. Protocole TCP

Le protocole TCP est un protocole permettant de ne pas surcharger le réseau en découpant les données à envoyer en plusieurs morceaux appelés *paquets*.

Par groupe de deux, l'un jouant le rôle d'expéditeur et l'autre jouant le rôle de destinataire.

L'expéditeur doit envoyer une image au destinataire via Internet.

Des probèmes peuvent survenir pendant l'échange.

e) Proposer des solutions aux questions suivantes :

1. L'image est trop lourde pour être envoyée d'un seul coup, comment l'expéditeur peut-il envoyer l'image ?
......................................................................................................................

2. Comment l'expéditeur peut-il être sûr que le destinataire a bien reçu le message ?
......................................................................................................................

3. Comment le destinataire peut-il savoir qu’il a tout reçu ?
......................................................................................................................

4. Comment D peut-il savoir que le message reçu est correct ?
......................................................................................................................

5. Que faire si un paquet se perd ?
......................................................................................................................

6. Que faire si les paquets arrivent dans le désordre ?
......................................................................................................................

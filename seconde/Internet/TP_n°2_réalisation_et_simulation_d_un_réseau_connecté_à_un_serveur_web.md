# TP n°2 : Réalisation et simulation d'un réseau connecté

Pour ce TP, nous utiliserons le logiciel libre et gratuit : Filius.

Filius permet de construire et simuler un réseau. Une fois lancé, nous disposons de plusieurs modes :

- *Mode construction* : permet d'ajouter des composants réseaux, de les paramétrer et de les relier entre eux.

- *Mode simulation* : permet de lancer une simulation et de voir les données circuler dans le réseau.

En mode construction, nous pouvons sélectionner un composant réseau et le faire glisser dans la zone de dessin.

Pour relier deux éléments , nous cliquons sur l'icône du câble, puis sur chacun des deux éléments à relier.

## Exercice 1

![](./img/exo2.PNG)

a) En mode construction, reproduire le réseau de la figure ci-dessus dans un fichier nommé `reseau_ex2.fls`.

Les machines M1 et M2 ont respectivement les adresses IP ``192.168.10.1`` et ``192.168.30.5``.

Le serveur possède l'adresse IP ``8.8.8.1``.

b) Il faut désormais relier ces deux réseaux, pour cela configurer le routeur :

- L'adresse IP du routeur du port relié au réseau A est ``192.168.0.1``.

- L'adresse IP du routeur du port relié au réseau B est ``8.8.8.254``.

c) Modifier le masque de sous-réseau en `255.255.0.0` sur le port du routeur relié au réseau A et en `255.255.255.0` sur le port du routeur relié au réseau B.

d) Depuis M1, lancer un ``ping`` vers le serveur. Que se passe t-il ? Les machines sont-elles connectées ?

L'erreur survient du fait qu'il manque une information à M1, il ne sait pas où envoyer la donnée. La passerelle est l'interface qui permet aux paquets de sortir du réseau.

e) Dans la configuration de M1, ajouter dans `Passerelle` l'adresse IP du routeur relié au réseau A.

f) Dans la configuration du serveur, ajouter dans `Passerelle` l'adresse IP du routeur relié au réseau B.

g) Refaire la commande `ping` vers le serveur depuis M1. Les machines sont-elles connectées ?

La commande `traceroute`permet de visualiser quels équipements les données traversent.

h) Depuis M1, effectuer la commande `traceroute` suivie de l'adresse IP du serveur. A quoi correspondent les adresses affichées ?

On décide de faire héberger sur le serveur une page Web.

i) Pour cela, installer sur le serveur le logiciel **Serveur web** et sur M1 le logiciel **Navigateur web**.

S'assurer que le serveur web est bien démarré, puis faire clic droit sur M1 et choisir **Afficher les échanges de données**.

Enfin, sur M1, ouvrir le navigateur et à la suite de ``https://`` : écrire l'adresse IP du serveur.

j) En visualisant les échanges effectués entre le navigateur et le serveur web, donner en précisant les couches, les protocoles utilisés.

______________

[Sommaire](./../README.md)

# TP n°1 : Réalisation et simulation d'un réseau local

Pour ce TP, nous utiliserons le logiciel libre et gratuit : Filius.

Filius permet de construire et simuler un réseau. Une fois lancé, nous disposons de plusieurs modes :

- *Mode construction* : permet d'ajouter des composants réseaux, de les paramétrer et de les relier entre eux.

- *Mode simulation* : permet de lancer une simulation et de voir les données circuler dans le réseau.

En mode construction, nous pouvons sélectionner un composant réseau et le faire glisser dans la zone de dessin.

Pour relier deux éléments , nous cliquons sur l'icône du câble, puis sur chacun des deux éléments à relier.

## Exercice 1

![image](./../img/exo1.PNG)

a) En mode construction, reproduire le réseau de la figure ci-dessus dans un fichier nommé `reseau_ex1.fls`.

b) Renommer le premier ordinateur portable en `M1` et le second en `M2`.

c) En cliquant sur `configurer`, donner :

- l'adresse IP `192.168.0.1` à `M1`.

- l'adresse IP `192.168.0.2` à `M2`.

d) En cliquant sur `configurer`, donner :

- le masque de sous réseau `255.255.0.0` à `M1`.

- le masque de sous réseau `255.255.0.0` à `M2`.

La commande `ping` permet d’envoyer des données vers une adresse IP. Si la
machine de destinatation les reçoit, elle répond en envoyant un accusé de réception. Cette commande permet de vérifier si deux machines peuvent communiquer entre-elles.

e) Passer en mode simulation. Cliquer sur l'un des deux ordinateurs, puis sur **Installation de logiciels** et installer le logiciel **Ligne de commande**.

Sur ce logiciel, exécuter la commande `ping` suivie de l'adresse IP du second ordinateur. Les deux machines sont-elles connectées ?

f) A quoi correspond le temps affiché à côté de chaque accusé de réception ?

___________________

[Sommaire](./../README.md)
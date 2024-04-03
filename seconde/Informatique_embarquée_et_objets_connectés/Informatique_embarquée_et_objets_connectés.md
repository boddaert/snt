# Informatique embarquée et objets connectés

# I. Introduction

Répondre aux questions suivantes à l'aide de la [vidéo d'introduction](https://ladigitale.dev/digiview/#/v/660d2189b3dab) :

1) Quels sont les trois éléments que compose un système embarqué ?

......................................................................................................................

2) Expliquer en une ligne comment fonctionne un système embarqué :

......................................................................................................................

3) Donner trois exemples de systèmes embarqués :

......................................................................................................................

4) Comment de l'informatique embarquée peut-elle devenir un objet connecté ?

......................................................................................................................

5) Donner trois exemples d'objets connectés :

......................................................................................................................

## II. Définitions 

a) Compléter les définitions ci-dessous à l'aide des mots suivants :

`actionneurs`, `embarqué`, `mesure`, `capteurs`, `autonome`, `internet des objets`, `Internet`, `services`, `clients`, `programme informatique`

1) Un système informatique ............ est défini comme un système électronique et ............, souvent en temps réel, spécialisé dans une tâche précise.

Un système embarqué est composé de ............, d’actionneurs et d’un programme informatique.

2) Un capteur permet de réaliser une ............, et selon sa valeur : calcule à l'aide d'un ........................ l'action que doit effectuer l'actionneur.

3) Un objet connecté est un système embarqué muni de ............ et/ou de capteurs pouvant échanger des données sur un réseau d’information. Ce réseau est appelé ........................ ou en anglais *Internet of Things*.

Les ............ se connectent à lui à travers ............ pour obtenir ses ............

## II. Repères historiques

b) En cherchant les informations sur Internet (sur votre téléphone portable), relier ci-dessous les dates avec leur évènement.

| ----------------Date----------------- | ---------------Évènement----------------- |
| :------ | ------: |
| **1971 -** | **- Mise en service du premier métro informatisé sans conducteur** |
| **1998 -** | **- Arrivée du smartphone**|
| **1984 -** | **- Sortie de l'AirbusA320, premier avion équipé de commandes electriques informatisées**|
| **2007 -** | **- Premier système embarqué de guidage lors de la mission Apollo** |
| **1967 -** | **- Premier processeur Intel** |

## III. Exemple : Le système de freinage ABS

Lors d’un freinage, il est important pour la sécurité de ne pas bloquer les roues. Cela permet de conserver de bonnes conditions d’adhérence avec la route et d’éviter la perte du contrôle du véhicule en cas de changement de trajectoire.

Chaque roue doit être contrôlée indépendamment des autres car les conditions de contact des roues avec le sol peuvent être différentes (une roue sur une flaque d’eau et les autres sur le bitume sec).

Un véhicule est équipé sur chacune de ses roues d'un mesureur de vitesse de rotation de la roue. Si, lors d'un freinage, la vitesse mesurée en temps réel d’une des roues est presque nulle, l'information est transmise au calculateur qui va alors commander de relâcher la pression hydraulique sur le frein de cette roue afin qu’elle se remette à tourner.

Lorsque le chauffeur appuie sur la pédale de frein, le maître-cylindre alimente en huile le groupe hydraulique qui régule la pression d’huile dans le circuit hydraulique. Les pistons portés par les étriers de frein de chaque roue et disposés de part et d’autre des disques sont poussés par l’huile sous pression. Ils pincent fortement le disque solidaire de chaque roue qui ralentissent. 

Si le pincement est trop fort, une ou plusieurs roues peuvent se bloquer. Pour éviter cela, un capteur détecte la vitesse de chaque roue et délivre cette information au calculateur. Si la vitesse d’une des roues devient trop faible et proche du blocage, le calculateur donne l’ordre au groupe hydraulique de diminuer la pression sur l’étrier de la roue correspondante.

Ainsi, grâce à l’ensemble capteur de vitesse-calculateur-groupe hydraulique, la pression est régulée lors d’un appui sur la pédale de frein pour obtenir la meilleure efficacité du freinage sans blocage.

Le système va ainsi, jusqu'à vingt-quatre fois par seconde, bloquer et débloquer les freins de chaque roue, quand bien même le conducteur continue à appuyer le plus fort possible sur la pédale de frein. Ces réajustements répétés peuvent être ressentis par le conducteur au niveau de la pédale de freinage.

c) À l'aide du document précédent, répondre aux questions suivantes :

1) Citer les capteurs du système ABS.
................................................................................................................................................................

2) Citer les actionneurs du le système ABS.
................................................................................................................................................................

3) Expliquer pourquoi il est indispensable de doter les quatre roues d’un capteur de vitesse
................................................................................................................................................................

4) Compléter l'algorithme suivant du système ABS :

```
Tant que la ........... de la voiture est non nulle et que le conducteur appuie sur le ...........:
    Pour chaque roue de la voiture :
        Si la ........... est proche de ..........., alors :
            ........... la pression sur ........... de la roue
        ........... :
            augmenter la pression sur l’étrier de frein de la roue
```
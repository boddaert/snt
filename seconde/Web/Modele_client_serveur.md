# Modèle Client-Serveur

## a) Introduction

Lorsque nous cliquons sur un lien hypertexte ou que nous entrons une adresse web sur la barre d'adresse, une page web s'affiche à l'écran.

- La page qui vient de s'afficher ne se trouve pas en réalité sur notre ordinateur, mais sur une autre machine appellée *serveur web*. Il y a donc eu une communication entre notre machine et le serveur pour récupérer les données de la page.

- Deuxièmement, notre machine n'est pas reliée directement au serveur : il n'y a pas de câble reliant directement notre ordinateur au serveur.

- Troisièmement, si nous répétons l'expérience depuis des lieux différents avec des machines différentes, la page web s'affiche pareillement.

Il y a en fait un modèle de communication, des règles auquelles les deux entités (ordinateur et serveur) se sont mises d'accord pour communiquer efficacement.

Nous appelons ce modèle : le modèle Client-Serveur.

## b) Principe

Le *client* (le navigateur) et le serveur sont deux entités qui communiquent.

Le client souhaite accèder à une ressource présente sur le serveur.

Le modèle Client-Serveur repose sur le protocole de communication HTTP (*HyperText Tansfer Protocol*) qui permet d'envoyer des requêtes HTTP et de recevoir une réponse du serveur :

```mermaid
    graph LR;
        CLIENT--Requête HTTP-->SERVEUR;
        SERVEUR--Ressource-->CLIENT;
```



__________

Leçon 8 : [Langages HTML et CSS](./HTML-CSS.md)
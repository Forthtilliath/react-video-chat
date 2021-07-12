# Introduction

Ce projet suit la vidéo suivante : [React Video Chat App | WebRTC Video Chat Zoom Clone](https://www.youtube.com/watch?v=oxFr7we3LC8). Le but du projet est de développer une application permettant de lancer un appel vidéo avec un autre interlocuteur. Le projet est fait en réact, avec un back en Nodejs et utilise les sockets pour communiquer.

# Intérêts du projet

Ce projet m'intéresse pour apprendre à faire communiquer une application entre plusieurs utilisateurs. Dans le cas de cette application, j'apprendrais à partager des données vidéos entre deux utilisateurs.

Le plus étant que tout ceci est avec Réact !

# Difficultés rencontrées

Rien à signaler de ce coté là.

# Ce que m'a apporté ce projet

## Socket

Comme prévu, j'ai pu découvrir les sockets et comment m'en servir avec Réact. J'ai constaté que pour faire fonctionner une communication entre plusieurs utilisateurs, il était essentiel d'avoir un serveur back afin de formatter les données à envoyer.

## Context

J'avais découvert les contextes lors du projet MERN pour faire un réseau social. J'avais rencontré des difficultés à apporter les améliorations souhaitées. Ce projet m'a donc aussi permis de réutiliser les contextes.

Toutefois, l'utilisation ici est bien plus poussée. L'ensemble du context est géré directement dans le fichier ``Context.js``, ce qui simplifie sont utilisatinos dans les fichiers adjacents.

# Conclusion

Ce fût un projet rapidement, mais qui m'a d'une part permis de faire un rappel sur des éléments que j'avais découvert lors d'un projet précédent, et d'autre part m'a permis de découvrir les sockets, élément utile dès le moment où l'on souhaite faire communiquer des données entre plusieurs utilisateurs sans avoir besoin de les stocker sur un serveur.

# Screenshots

![home](/screenshots/home.png)

![calling](/screenshots/calling.png)

Exemple d'un appel (avec soi-même, à défaut d'avoir une autre personne avec qui tester)
![calling_myself](/screenshots/calling_myself.png)
---
title: "Documentation des niveaux d'Arty Slot"
date: 2022-12-25T16:57:42+01:00
draft: false
---

## Créer ses niveaux pour Arty Slot

J'ai essayer de document un minimum le fonctionnement des niveaux sur le jeu Arty Slot. Le contenu n'est pas opérationnel à 100% mais il s'agit d'un début.  
Les niveaux sont stocké dans des fichier map_XX.txt
> Le XX correpond au numero du niveau (par défaut, mettre 1 pour le premier niveau et être sur que ca marchera)

Le fichier est composé d'une chaine de caractère s'apparente à un passage de type HTTP GET, chaque élément est séparer par un &.

Composition de la chaine de caractère:

- champ 1: w, il s'agit de la largeur de la map (nombre de cases)
- champ 2: h, il s'agit de la hauteur de la map (nombre de cases)
- champ 3 et 4: posx et posy, il s'agit de la position de départ du personnage
- A partir du champ 5: il s'agit du contenu des cases, le nom du champ est &cXX= où XX est le numéro de la case. Il y a champ 1 * champ 2 case sur la map, ici, il s'agit de l'image a afficher pour chaque case, a prioris, il faut un nombre entre 1 et 3 inclus, cependant dans le fichier original il y a d'autres valeurs
- Après les champs c, il y a le champ ques, il s'agit d'une question à laquelle doit répondre le joueur, sous la forme d'énigme.

Je ne sais pas trop où aller après, néanmoins il y a déja un bon départ d'information.

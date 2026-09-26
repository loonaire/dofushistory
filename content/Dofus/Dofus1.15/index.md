---
title: "L'importance de la mise à jour 1.15"
date: 2026-09-26T14:37:55+02:00
draft: false
---

## Introduction

Pour les 20ans de dofus 1.15 j'ai décidé d'écrire une petite page sur cette version qui est importante dans le virage qu'à pris le jeu. Même si plus globalement toutes les versions de dofus sorties au mois de septembre de 2003 à 2009 sont importantes. Nous v1b en octobre 2003 puis la 1.0 en septembre 2004 qui marque la fin de la beta, en 2005 la 1.9 marque un tournant vers une internationalisation du jeu en ajoutant le coté multi langue et multi serveur tout en gardant les mécanismes de la 1.0. En 2007 nous avons l'ajout de l'ile d'otomai avec des retrait d'anciennes mécaniques héritées de la 1.0 et l'ajout de sorts niveaux 6 et en 2008 la 1.25 marque l'obligation de passer par le launcher pour les mises à jour tout en mettant à jour d'anciennes mécaniques. Enfin en septembre 2009 la mise à jour 1.29 marque la fin de dofus 1 avec la dernière grosse mise à jour de cette version en apportant un équilibrage pré 2.0 dans le but de repartir sur des bases plus saines.  
Malheureusement je n'ai pas de changelog précis pour cette version, il peux donc y avoir des confusion entre la 1.14, la 1.15 et la 1.16.  
Ce poste est un résumé de [cet article](https://web.archive.org/web/20070320223332/http://dofus.jeuxonline.info:80/articles/2761/Notes_de_version_1.15.2)

## Un client mieux conçu

Coté technique cette version 1.15 est intéressante sur beaucoup de points, déjà car elle fait suite à la 1.14 qui reprenais complètement la partie serveur du jeu (chaque serveur à sa base de donnée). Le chantier du client a été démarré avec la nouvelle interface de connexion de la 1.13.2 puis sur la 1.14 avec l'interface de choix de serveur, la 1.15 marque la fin de ce chantier avec la refonte de l'interface de choix de personnage.  
A partir de la version 1.10 tout un ensemble d'outil a été ajouté pour manipuler plus facilement le client via la console admin du jeu, il est par exemple possible de changer la taille du personnage via une commande. Ces ajouts ont été fait pour ajouter du RP.  
Techniquement la base de code de cette version est plus moderne, la plupart du code a été nettoyé et amélioré pour être plus robuste, la base sera la même jusqu'à dofus 1.29 même si d'importantes modifications seront effectuées plus tard.
Un des plus intéressant changement de cette version est l'ajout des fichiers lang au client dans le dossier data. Dans un premier temps il a été ajouté rapidement et de manière étrange sur la 1.14 puis modifié avec les correctifs 1.14.1 et 1.14.2. Cette modification est entièrement revue avec la version 1.15 et son dossier data qui contient la plupart des informations auparavant stockées uniquement sur un serveur, ce serveur existe toujours mais seulement pour mettre à jour les fichiers en cas de mises à jour des traductions.

## Une modification des interfaces

Cette mise à jour à eu beaucoup de modifications qui sont encore aujourd'hui utilisées sur dofus rétro.  
L'interface de sorts à changée avec le passage de la 1.15.2 à 1.15.3 pour passer sur la même que celle de dofus retro, elle permet d'avoir un nombre théoriquement infini de sort sur le personnage.  
Il y a également une légère modification de l'inventaire avec la possibilité de voir les recettes liées à un objet.  

## Les montures

L'un des ajouts significatifs de cette version est l'ajout des dragodindes avec tout le système d'élevage.
Longtemps réfléchis, on trouve des traces de sprites de monture à partir de dofus 1.11 avec un feca qui chevauche un Bouftou et un Abraknyde, ce sont des traces de ce qui était envisagé à la place des dragodindes, surement un système plus similaire à celui des familiers mais finalement c'est le système dragodinde avec l'élevage qui a été choisi.  
Sur la 1.15 on voit donc des cartes ajoutées à Bonta et Brakmar pour la mise en place de zones destinées à l'élevage de monture en enclos, d'autres enclos sont ajoutés dans le monde.
L'élevage correspond au métier d'éleveur mais le métier n'a pas été crée pour rendre le coté élevage plus passif et non lié à des restrictions.

## La montagne des koalaks 

La sous zone de la montagne des koalaks est apparue avec cette mise à jour, cette zone est grande avec différents environnements plutôt intéressants. L'ajout de cette permet l'arrivée de 3 donjons: Le donjon Koulosse qui permet l'obtention du sort capture de monture, le donjon skeunk qui permet d'obtenir le dofus kaliptus et le donjon des familiers.  
Le donjon des familiers offre un nouveau moyen pour ressusciter les familiers mort avec une mécanique originale: Les joueurs sont transformés en familier pour faire le donjon.  
En dehors de ces ajouts, je ne trouve pas qu'il y ai beaucoup de chose à dire sur cette zone, la zone est intéressante, ajoute des spots pour les familiers (alchimiste, bucheron, pêcheur) mais ca s'arrête la: Le marécage est une zone intéressante mais les résistances rendent les combats compliqués, les l'accès au cimetière primitif est compliqué mais offre un bon lieu d'xp, la vallée de la mort est difficilement accessible car il faut faire une grande partie du chemin vers le donjon koulosse avec des monstres qui agressent et enfin il y a peu de quêtes malgré la taille de la zone.
Enfin pour terminer sur ce sujet, le métier de bricoleur fait son arrivée en jeu pour crée des items dédiés à l'élevage de Dragodinde.

## Le château d'amakna et ses alentours

Cette zone est rendue bien plus attirante pour tout le monde: la zone qui n'a jamais été officiellement accessible est désormais accessible, la banque est retirée ainsi que d'autres lieux qui auraient pu être intéressant, à la place nous retrouvons un château complètement refait avec une série de quête, des cartes avec des maisons, des enclos, un zaap, des pnjs pour rendre vivant le château et des sous zones dans les alentours (le sous terrain ainsi que la zone de l'élevage de bouftou du château d'Amakna). 

## Des nouvelles mécaniques de jeu

La version 1.15 c'est aussi l'ajout de donjons dans les anciennes zones. Ces donjons permettent de combattre plus simplement les boss, l'ancien système consistait en un repop aléatoire du boss dans une zone, désormais le boss sera dans un donjon que les joueurs pourront faire en boucle et le boss sera toujours présent dans son donjon. Introduit avec le donjon Bouftou puis popularisé avec la sortie de pandala durant les versions 1.12 et 1.13 cette mise à jour ajoute le donjon Craqueleur, c'est également l'occasion d'ajouter des items de panoplie en jeu (pano craqueleur). 
Pour ce nouveau donjon une clé est nécessaire pour entrer, à cette époque pas de trousseau de clé et je ne suis pas sur que le système de clé était en place.  
Une autre apparition de cette version est l'arrivée des protecteurs de ressources, une des premières mesures anti bot.  
Enfin un des changements de cette version est l'ajout d'hdv de rune et de créatures à Bonta et Brakmar ce qui participe à renforcer l'utilité des cités dans le jeu.
En prévision de l'avenir et de la 1.16, Beaucoup de contenu sont ajoutés client de la 1.15 ce qui pose beaucoup de confusion entre le fait qu'il n'y a pas de vraie liste des changements depuis la 1.14.2 et qu'une grande partie du contenu ajouté sortira avec la 1.16.2 après 2 betas.

## Pour conclure

Cette version est une tournure pour le jeu, elle permet de se séparer des restes des dernières betas du jeu (boss en liberté, ancien chateau d'amakna) tout en ajoutant beaucoup de contenu (donjons, dragodindes, montagne des koalaks). Nous retrouvons également des grosses modifications sur le client avec tout un système unifié de chargements des données depuis les serveurs web de dofus (dossier lang, appels à divers fichiers "propres" pour les interfaces (news du client)), 
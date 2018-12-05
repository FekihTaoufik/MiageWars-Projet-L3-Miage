

# MIAGE WARS - *Le jeu de la L3 Miage*
![Miage wars](https://image.ibb.co/kUWZkL/Logo.png)
## Proposition de nom du jeu :

Nous avons réfléchie à 3 noms possibles pour notre jeu :

- Miage Wars - Battle Royale
- Star Miage - le jeu de la L3 Miage
- Medal of Miage  *ou*  Call of Miage

Nous avons choisi (à l’unanimité) : MIAGE WARS
## Brainstorming :

### Les bases de notre projet :
- Un multi-joueur
- Type shooter
- Les types d'armes a définir (Pistolet, Fusil a pompe, Lance flammes, ...)

### Les règles du jeu :
- Objectif: être le dernier survivant de la partie
- Chacun pour soi
Au lancement du lien :
- choix d'un pseudo ainsi que d'un skin
- pour la version 1, on pourra apparaître dans la map à n'importe quel moment de la partie (en cours donc)

### Déroulement d'une partie :
- Apparition aléatoire dans la map au début du jeu
- Armes aléatoirement répartis dans la map
- Au bout de 2min : apparition d'une tempête et toutes les 3mins, la tempête se rétrécit.
- On doit éliminer les autres joueurs et rester hors de portée de la tempête

### Système d'armes :
- 3 lots d'armes (faibles, moyennes, fortes)
- armes faibles : pistols, matter, mg (50%)
- armes moyennes : shotguns, spazer, cannon (40%)
- armes fortes : rockets, flamthrower, laser (10%)

### Les joueurs :
- une barre de vie (100 hp)
- possibilité de porter 3 armes maximum
- pas de kit de soin et pas de shield pour la version 1

## Démo

Une démo est disponible sur le site [www.miagination.fr](www.miagination.fr), mais elle n'est pas toujours a jour.
*Il est préférable de cloner le dépôt et de lancer l'application sur l'une des branches master/game_dev.*

## Installation et usage

### Requis

 - [Nodejs](https://nodejs.org/en/)

###Commande pour démarrer la démo 

Pour faire marcher notre application il faut lancer le serveur de développement pour compiler les fichiers ( .vue principalement ) et notre serveur principale qui va servir les fichiers assets pour le jeu et socketio pour le système de multijoueur.



> 1) Installation des dépendances du client et du serveur
> `npm run install_dep`
    

> 2) Démarrage du serveur de développement
>  `npm run dev`
> 
> 
> 3) Démarrage du serveur principale (dans une autre console)
> `npm run server` 

  4) Il vous suffit de rentrer dans votre moteur de recherche favori "http://loclahost:8080/"

## Equipe de travail :
Professeur encadrant : [M. Michel BUFFA](https://github.com/micbuffa)
- [Taoufik FEKIN](https://github.com/FekihTaoufik)
- [Rémi FELIN](https://github.com/RemiFELIN)
- [Sirine BEN AHMED](https://github.com/Sirine-BenAhmed)

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018-present, FEKIH Taoufik - FELIN Rémi - BEN AHMED Sirine
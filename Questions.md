# Questions pour le projet d'année:

## Compréhension globale de l'énoncé

* Que doit on rendre dans le *squelette* du code ?

## Implémentation du programme
### Inscriptions & débuts
* Cartes reçues par les nouveaux inscrits sont-elles toujours les mêmes ? Combien ?
* Un *deck* peut-il contenir plus ou moins de 20 cartes ?
* Les *duels* sont-ils joués avec 2 joueurs d'a peu près le même niveau, ou est-ce purement aléatoire ?
* Peut-on modifier ces données personnelles & visibilité de celles-ci aux autres joueurs ?

### Durant une partie
* Il y a t-il un maximum de cartes que le joueur peut avoir ? Si non, comment gérer le sur-plus ?
* Quel est la signification de *retirer du jeu* ? Une fois retirer, peux t-elle être récupérable ? Il y a t'il une nuance avec *défausser* (qui est donné dans l'énoncé) ?
* Comment gérer l'absence d'activité d'un joueur pendant une partie ? (implémentation d'un timer ?)
* Comment gérer le cas ou une partie dure indéfiniment, si par exemple un joueur regagne plus de PV qu'il en perd (même en l'absence de pioche ou il perd 5 PV/tour) ?
* Un joueur a-t'il la possibilité d'abandonner un match? Si oui considère t'on que l'adversaire "gagne" (risque de triche pour gagner des cartes rapidement) ?
* Le plateau a t-il une limite par rapport au nombre de monstre d'un joueur qu'il peut contenir ?

### Fin de partie
* Il y a t'il une nuance dans la victoire, pour avoir gagner contre un adversaire meilleur qu'un autre ? (gain de cartes plus rares ?)

### Gestion des amis
* Est-ce possible de pouvoir discuter avec ses amis pendant une partie ? Et avec l'adversaire s'il est un de nos amis ?
* Comment se gère la gestion des amitiés (bloquer, supprimer, inviter, etc.) ? 
* Peut on défier ses amis directement ? Si oui considère t-on que c'est une victoire "classique" (gain de cartes etc.) ?
* Peut-on assister au match d'un ami (spectateur) ? Si oui, quel visibilité a t-il (voir la main de son ami et de l'adversaire (que s'il est lui même dans ses amis éventuellement))?
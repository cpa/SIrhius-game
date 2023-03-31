# SIrhius-game

Ce serious game est principalement à destination des agents publics. Il permet de découvrir à la fois quelques fondamentaux du développement d'un système d'information au sein de la fonction publique et d'entrevoir quelques situations ou événements de nature à accélérer ou ralentir les développements.

Il s'inspire de la mécanique de [Built-in quality game](https://github.com/philou/built-in-quality-game) de [Philippe Bourgau](https://philippe.bourgau.net/) dont il partage la license et a été créé avec [Arno Amabile](linkedin.com/in/amabile-arno) et Charles Duchêne à l'occasion d'un cours sur les systèmes d'information au corps des mines.

# Objectif
C'est un jeu collaboratif : les joueurs doivent gérer collectivement leurs priorités et coopèrent pour développer le plus de fonctionnalités possibles et les mettre en production le plus rapidement possible.

# Déroulement d'une partie
## Mise en place
Placer devant soi :
- 1 tableau [kanban](https://fr.wikipedia.org/wiki/Kanban_(d%C3%A9veloppement))
- Les cartes "Oh non" (faire une pile face vers le bas)
- Les cartes "Zut" (faire une pile face vers le bas)
- Les cartes "Bonne pratique de développement" (faire une pile face vers le bas)
- Les cartes "Intérêt général" (faire une pile face vers le bas)
- Préparer des morceaux de post-it pour symboliser les fonctionnalités
- Préparer une feuille de suivi
 
## À chaque tour
- Faire avancer d'une colonne toutes les fonctionnalités et bonnes pratiques
- Les bonnes pratiques sont automatiquement acquises (les poser devant soi) lorsqu'elles arrivent dans la colonne TODO
- Tenter de mettre en production les fonctionnalités arrivées dans la colonne TODO (cf _infra_)

- Quatre possibilités pour l’équipe :
  - Lancer le développement d'une nouvelle fonctionnalité (poser un postit dans la colonne la plus à gauche)
  - Lancer une bonne pratique de développement (tirer une carte bonne pratique et la poser dans la colonne la plus à gauche)
  - Faire vivre sa relation avec les sponsors politiques et métiers (tirer une carte sponsors et la poser devant soi)
  - Poser une carte qui permet de gagner des points « intérêt général »

## Mise en production
Pour déployer une fonctionnalité, tirer deux dés :
- Si le chiffre est entre 1 et 6, alors il y a un événement « Zut »
- L’évènement peut être évité si une bonne pratique de dév a été adoptée
- Noter sur une feuille de suivi le numéro du tour et le nombre de fonctionnalités mises en production

## Tous les 5 tours
Tirer deux dés :

- Si le chiffre est entre 1 et 6, alors il y a un événement « Oh non »
- L’événement peut être évité s’il y a assez de points de relation avec les sponsors

## Fin de la partie
La partie s'arrête après le 20° tour.

# Discussion
Le jeu est surtout un prétexte pour susciter des discussions. C'est une partie importante de son déroulement !

Idées d'animation :

Quelles métriques pourrait-on utiliser pour mesurer l'avancement dans le jeu ?
- Délai de mise en prod de la première fonctionnalité
- Nombre de fonctionnalités mises en production
- La somme, pour chaque fonctionnalité, du nombre de jours où elle a été en production (20 - date de mise en prod)
- Délai moyen entre deux mises en production
- …

Quelle est la stratégie qui vous pourrait la plus efficace / que feriez-vous différemment ? Si vous aviez eu 40 tours ? 10 tours ?

Quelle sont les aspects du jeu qui vous paraissent les plus irréalistes ? réalistes ?

Quelles bonnes pratiques de développement (et carte zut associée) pourrait-on ajouter ? Quelles autres cartes (Oh non, intérêt général)

# Contribuer
N'hésitez pas à contribuer en proposant de nouvelles cartes via ce repo ou en nous contactan directement

# SIrhius-game

Ce serious game a été conçu à destination des agents publics. Il a pour objectif :
- de découvrir quelques fondamentaux du développement d'un produit numérique ;
- d'entrevoir quelques situations ou événements de nature à accélérer ou ralentir les développements, dont certains sont spécifiques à la fonction publique ;
- de sensibiliser les participants à l'importance d'un investissement dans la qualité de l'équipe et du code produit ;
- d'amorcer une discussion sur les arbitrages à réaliser (rapidité, qualité technique, sponsor, etc.)

Il s'inspire de la mécanique de [Built-in quality game](https://github.com/philou/built-in-quality-game) de [Philippe Bourgau](https://philippe.bourgau.net/) dont il partage la license et a été créé par [Charles-Pierre Astolfi](https://www.linkedin.com/in/charles-pierre-astolfi/), [Arno Amabile](linkedin.com/in/amabile-arno) et Charles Duchêne à l'occasion d'un cours sur le développement de systèmes d'informations au sein de la majeure numérique de la formation des ingénieurs du Corps des Mines.

Afin de se concentrer sur la partie développement, il n'évoque donc pas de façon approfondie la conception des produits numérique (design thinking, ateliers utilisateurs).

# Objectif
C'est un jeu collaboratif : les joueurs doivent gérer collectivement leurs priorités et coopèrent pour développer le plus de fonctionnalités possibles et les mettre en production le plus rapidement possible.

# Matériel

# Déroulement d'une partie
## Mise en place

Placer devant soi le tableau kanban [(télécharger)](https://drive.google.com/file/d/1wGi8Xu0C-6Jjlt0IHSm7kxlWoMk4xvjO/view?usp=sharing)

Placer devant soi deux piles, _face vers le haut_ :
- Les cartes "Bonne pratique de développement" [(télécharger)](https://drive.google.com/file/d/1krD4a3zmCbHdpnUfi4VMAwe8SUEqEgmW/view?usp=sharing)
- Les cartes "Zut" [(télécharger)](https://drive.google.com/file/d/1krD4a3zmCbHdpnUfi4VMAwe8SUEqEgmW/view?usp=sharing)

Placer devant soi deux piles, _face vers le bas_ :
- Les cartes "Le mail du jour" [(télécharger)](https://drive.google.com/file/d/1s8OxSbn2YW19glQ-PJANoqE4VVnyY7Tj/view?usp=sharing)
- Les cartes "Intérêt général" [(télécharger)](https://drive.google.com/file/d/1s8OxSbn2YW19glQ-PJANoqE4VVnyY7Tj/view?usp=sharing)

Préparer également :
- Des morceaux de post-it pour symboliser les fonctionnalités
- Une feuille de suivi avec en abcisses le nombre de tours et en ordonnées le nombre de fonctionnalités mises en production.
 
## Ice-breaker (optionnel)

Afin d'incarner le jeu, et d'amorcer la dynamique, un ice-breaker peut être fait pour déterminer le produit numérique qui sera développé par l'équipe (le choix est sans conséquence sur la dynamique du jeu). Par exemple :
- Chaque participant pose trois post-its devant lui
- Il a une minute pour trouver un problème à écrire sur le premier post-it, puis une minute pour le 2e, et idem pour le 3e
- Les post-its sont mélangés
- Chaque participant tire deux post-its au hasard, et a deux fois une minute pour trouver un nom au produit qui résoudrait le problème
- Les participants mettent en commun les problèmes & noms et choisissent celui qu'ils préfèrent (ou un autre !)
 
## À chaque tour

Quatre possibilités s'offrent au groupe :
- Lancer le développement d'une nouvelle fonctionnalité (poser un postit dans la colonne la plus à gauche)
- Lancer l'apprentissage d'une bonne pratique de développement (choisir une carte bonne pratique et la poser dans la colonne la plus à gauche)
- Faire vivre sa relation avec les sponsors politiques et métiers (tirer une carte sponsors et la poser devant soi)
- Réaliser une action "intérêt général" en tirant une carte 

Une fois la décision prise, plusieurs événements ont lieu :
- Le développement des fonctionnalités et l'apprentissage des bonnes pratiques progresse : les faire avancer d'une colonne chacune
- Si une bonne pratique était déjà dans la colonne "test & intégration" : elle est acquise et mise à l'extérieur du plateau 
- Si au moins trois fonctionnalités sont déjà dans la colonne "test & intégration" : tenter de les mettre en production (cf. _infra_)
- Un "mail du jour" arrive (tirer une carte)

## Mise en production
Pour déployer une fonctionnalité, tirer deux dés :
- Si le chiffre est entre 1 et 6, alors il y a un événement « Zut » (cf. carte associée)
- L’évènement peut être évité si une bonne pratique de dév a été adoptée
- Noter sur une feuille de suivi le numéro du tour et le nombre de fonctionnalités mises en production

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

Quelle est la stratégie qui vous paraît la plus efficace / que feriez-vous différemment ? Si vous aviez eu 40 tours ? 10 tours ?

Quelle sont les aspects du jeu qui vous paraissent les plus irréalistes ? réalistes ?

L'équipe commence sans aucune bonne pratique de développement. Est-ce réaliste ? Que feriez-vous pour changer cela ?

Quelles bonnes pratiques de développement (et carte zut associée) pourrait-on ajouter ? Quels autres mails du jour ?

Les points d'intérêt général n'ont pas d'impact sur la réussite de la partie. Pourquoi sont-ils là ?

# Contribuer
N'hésitez pas à contribuer en proposant de nouvelles cartes via [ce lien](https://docs.google.com/spreadsheets/d/1pD_ptL2mSqI8b2kogyoLT2_RpSPFCCoGUml8oFNLRDQ/edit#gid=0), ou en nous contactant directement !

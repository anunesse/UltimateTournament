###Formation Java EPF Project GuideLines
>EPF 2015 by Alexandre N & Christophe D

####TournamentManager
Le but de ce projet est de créer un gestionnaire de tournoi pour sport collectif ou inviduel. Ce gestionnaire de tournoi doit permettre d'organiser les rencontres de saisir les scores et de sauvegarder les informations relatives aux équipes.

####User stories
>Les "user stories" permettent de décrire une fonctionnalité que vous devez créer du point de vue d'un utilisateur quelconque.

* Je suis capable de créer un nouveau tournoi en choisissant le nombre d'équipe et l'organisation de celui-ci.
>2 types d'organisation de tournoi doivent être créer au minimum : élimination directe ou phase de poule/ phase finale.

* Je suis capable de modifier les informations relatives à chaque équipe du tournoi et ce à tout moment.
>Les équipes sont formées d'un certain nombre de joueur, ont un nom, une description et d'autres paramètres (à définir), lors de la création d'un tournoi elles sont créées avec des valeurs par défaut.

* Je suis capable de lancer mon tournoi et de saisir les informations sur les matchs à la volée.
>Je peux renseigner le résultat de n'importe quel match, et une fois tous les résultats d'un tour renseignés, on passe au tour suivant.

* Je peux choisir l'organisation du tournoi parmi deux disponibles.
>Les deux types de tournoi sont : 
Élimination directe sous forme d'arbre/
Poules de 4 équipes, toutes les équipes se rencontrent et les deux meilleures continuent le tournoi. (Une victoire vaut trois points, un nul un point, et une défaite zéro

####Clients
Il faudra faire deux clients pour ce projet, un premier client console (gestion complète du projet en utilisant la classe Scanner de java), puis un deuxième client avec une interface graphique (en utilisant SWING)

####Notes
* Lorsqu'il y a un nombre impair d'équipe ou de poule les équipes le passage au tour suivant doit être géré automatiquement.
* Il est conseillé d'utiliser vos propres types d'erreur pour que votre code soit plus propre et ait plus de sens

####Bonus
* Gérer les scores des équipes et conserver un "goal average"
* Créer une interface de Web Services JAX-WS pour permettre d'accéder à votre application.

####Rendu
Ce document sera mis à jour pour vous informer des dates et modalités de rendus. Il est susceptible d'évoluer.
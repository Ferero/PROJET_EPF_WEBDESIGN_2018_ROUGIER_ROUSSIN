# PROJET_EPF_WEBDESIGN_2018_ROUGIER_ROUSSIN
Projet Web Design 2018 ROUGIER ROUSSIN

Sujet choisi: les merveilles du monde.

Le site comprend 4 pages : une page menu, une page des anciennes merveilles, une page des nouvelles et une dernière page contenant un quizz :
Le site contenant des requetes http vers un fichier JSON, le fichier du site doit etre placé dans le repertoire d'un serveur web.

Le menu permet de charger une des trois autres pages.
Les pages des anciennes et nouvelles merveilles fonctionnent de la meme manière, seules les données affichées varient. 
Les pages contiennent un tableau des merveilles et une google map. 
L'utilisateur a la possibilité de visualiser en détails les informations d'une merveille en particulier.
La page de quizz permet a l'utilisateur de passer un quizz qui lui attribuera la merveille qui lui correspond.

Pour naviguer sur le site, commencez par ouvrir le fichier menu.html.

DATA SOURCE:

Nous avons décidé d'utiliser un fichier au format JSON contenant des informations sur les 14 merveilles du monde. 
Ces informations sont le nom, l'url des images, la date de construction, la date de disparition, le maitre d'ouvrage et une breve description des merveilles.
La recherche d'informations a été faite sur deux sites: Wikipedia et fracademic.com. 
Les données ont été séparées en deux tableaux pour les deux types de merveilles.
Nous avons aussi utilisé une api google map afin d'afficher la location des merveilles.

ANGULAR JS:

A propos des attributs Angular, nous avons utilisé tous les attributs requis suivant:
ng-model, ng-if, ng-show, ng-repeat, ng-class, ng-click, ng-submit

En complément, nous avons utilisé les attributs suivant : ng-change, ng-attr-id, ng-init, ng-src.
Des librairies ont aussi été utilisées : Angular, bootstrap, jquery.

Angular pour angular JS, bootstrap pour la partie responsive et le style, et Jquery pour le carousel d'image.
Nous utilisons deux fichiers JS pour les deux pages de merveilles et le quizz.
En complément de l'AngularJS le code contient deux scripts JS pour gérer la google map et un pour gérer un carousel d'image.

DESIGN ET STYLE:

Nous utilisons trois fichiers css, un pour le menu, un pour les deux types de merveilles et un pour le quizz.
De plus, l'utilisation de Bootstrap permet de styliser certains éléments comme le carousel d'image.

RESPONSIVENESS

La librairie Bootstrap permet de rentre le site responsive. Celui-ci reste utilisable sur smartphones et tablettes, les informations restant visibles.

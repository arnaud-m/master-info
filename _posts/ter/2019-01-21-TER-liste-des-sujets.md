---
layout: page-fullwidth
#
# Content
#
subheadline: "M1 INFO et MIAGE"
title: "Liste des sujets de TER 2019"
teaser: "Le TER (Travail d’Étude et de Recherche) est un stage sous la direction d’un encadrant universitaire ou industriel qui s’effectue par groupe de 2 à 4 étudiants (ingénierie) ou seul (recherche). Il sanctionne la fin du Master 1 et s’étend sur environ 3-4 mois (2 jours par semaine)."
categories:
  - TER
tags:
  - NEWS
#
# Styling
#
# image:
#  thumb: "scrappy.jpg"
#  homepage: "scrappy.jpg"
#  caption: "https://unsplash.com/"
# url: "https://unsplash.com/"
header:
#  image_fullwidth: "header-scrappy.jpg"
#    caption: This is a caption for the header image with link
#  caption_url: https://unsplash.com/
---

1. TOC
{:toc}


### Extension WebAudio pour Firefox ### 
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Michel Buffa](mailto:micbuffa@gmail.com).

Firefox va supprimer une partie importante pour WebAudio de ses devtools (console de debug). 
Michel Buffa est en contact avec les devs de Firefox qui sont d'accord pour vous aider à transformer ce qui existait en extension.
Les extensions sont maintenant codées en RUST, plus en JS.  
Il s'agit d'une opportunité rare de travailler avec les développeurs d'une application avec presque 300 millions d'utilisateurs.

### Scanner 3D 
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Enrico Formenti](mailto:enrico.formenti@unice.fr) et [Marie Pelleau](mailto:marie.pelleau@unice.fr).
 - Prérequis : savoir coder en C ou C++.

Dans ce TER on s'intéresse à la création d'un scanner 3D. Pour cela, on modélisera une plateforme rotative sur laquelle sera déposé l'objet à scanner. Un Arduino contrôlera le moteur pour la rotation du plateau et un appareil photo ou une webcam afin de photographier sous plusieurs angles l'objet à scanner.

### Robot explorateur
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Enrico Formenti](mailto:enrico.formenti@unice.fr) et [Marie Pelleau](mailto:marie.pelleau@unice.fr).
 - Prérequis : savoir coder en C ou C++.

Ce TER s'inscrit dans un projet de robot explorateur capable de détecter et éviter des obstacles. Une [première version]( http://i3s.unice.fr/master-info/ter/TER-Scrappy/) avec des senseurs à ultrasons a été réalisée. L'objectif ici est de réaliser une flottille de robots explorateurs afin d'effectuer une carte de l'espace exploré.
Ce TER a plusieurs objectifs, à savoir :
- L'étude des techniques existantes pour l'exploration d'un espace.
- La mise en place d'un protocole efficace de communication entre les différents robots.
- Conception d'un châssis pour les robots en plexiglas ou modélisation et impression 3D.

### Bras Robot pour jeu de plateau
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Philippe Renevier](mailto:philippe.renevier@unice.fr) et [Marie Pelleau](mailto:marie.pelleau@unice.fr).
 - Prérequis : savoir coder en C ou C++.

Ce TER s'inscrit dans un projet de jeu de plateau physique multi-joueurs en ligne ou contre une IA. Par exemple, vous jouez avec le vrai jeu de Takenoko contre votre IA. Il faut pouvoir déplacer les éléments du jeu pour l'IA, c'est pourquoi vous utiliserez un bras robotique.
Ce TER a plusieurs objectifs, à savoir :
  - L'étude des caractéristiques et des librairies disponibles pour l'utilisation des bras robotiques en général et en particulier pour le [Joy-It ROBOT02](https://www.gotronic.fr/art-bras-robotique-joy-it-robot02-26637.htm).
  - Développer une librairie de commande du bras de robot Joy-It ROBOT02, ou améliorer une librairie existante.
  - Mettre en œuvre quelques mouvements dans un jeu réel, en fixant les emplacements ou en utilisant une librairie de reconnaissance pour les éléments d'un jeu.

### Localisation des éléments d'un jeu de plateau
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Philippe Renevier](mailto:philippe.renevier@unice.fr) et [Marie Pelleau](mailto:marie.pelleau@unice.fr).
 
 
Ce TER s'inscrit dans un projet de jeu de plateau physique multi-joueurs en ligne ou contre une IA. Par exemple, vous jouez avec le vrai jeu de Takenoko contre votre IA. Il faut pouvoir localiser les éléments du jeu pour qu'ils puissent être manipuler par l'IA.
Ce TER a plusieurs objectifs, à savoir :
  - L'étude des techniques et des librairies disponibles pour la localisation d'éléments sur un plateau de jeu.
  - Développer une librairie de localisation d'élément, ou améliorer / adapter une librairie existante.
  - Mettre en œuvre le suivi des éléments d'un jeu lors d'une partie entre humains ou entre humains et IA dotée d'un bras robotique.

### Création d'une mini ferme de calcul basées sur des Raspberry Pi 2
 - Nombre d'étudiants souhaités : entre 2 et 4
 - Encadrants : [Arnaud Malapert](mailto:arnaud.malapert@unice.fr) et [Marie Pelleau](mailto:marie.pelleau@unice.fr)

En 2015, un étudiant du Master Informatique a créé une mini ferme de calcul de Raspberry Pi 2 contenant une vingtaine de Raspberry Pi 2 rangés dans un rack en bois et en aggloméré. L'une des difficultés était de faire courir les câbles d'alimentation dans le rack.
Le but de ce projet est donc d'améliorer le rack grâce à l'impression 3D et à la découpe Laser. Le nouveau rack devrait être mieux conçu : plus compact ; mieux aéré ;  plus élégant.


### Utilisation de la programmation par contraintes pour la détermination des paramètres de modèles dynamiques
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Jean-Paul Comet](mailto:comet@unice.fr) et [Marie Pelleau](mailto:marie.pelleau@unice.fr).
 - Prérequis : savoir coder en OCaml et connaître la logique de Hoare est un plus.

Ce TER a pour but d'utiliser la programmation par contraintes dans le cadre de la recherche de paramètres lors de la modélisation d'un réseau génétique.
Un réseau génétique peut être vu comme un graphe étiqueté dont les sommets sont les gènes et les arcs les interactions signées entre gènes. Lorsqu'on cherche à comprendre le fonctionnement d'un réseau génétique, la modélisation est nécessaire car les expériences sont trop coûteuses et parfois impossibles. Mais le goulot d'étranglement de l'étape de modélisation est de manière récurrente la détermination des paramètres qui gouvernent la dynamique du modèle.
Nous avons depuis plusieurs années développé une approche basée sur la logique de Hoare, initialement dédiée à la question de la correction des programmes impératifs. L'idée est de considérer une trace observée du système biologique comme une succession d'étapes élémentaires assimilable à un programme impératif, puis d'utiliser le calcul de la plus faible condition de la logique de Hoare pour calculer les contraintes sur les paramètres du modèle afin qu'il soit compatible avec la trace observée.
On utilisera le solveur continu-discret AbSolute pour trouver les solutions du problème. Ce problème étant compliqué de part sa nature, il faudra aussi envisager de développer et d'implanter des heuristiques de recherche au sein du solveur afin d'aider la détermination de certaines solutions.


### Generation automatique de texte ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Jean-Charles Régin](mailto:jcregin@gmail.com) et [Élena Cabrio](mailto:elena.cabrio@unice.fr).
 - Prérequis : bien programmer en java.


Ce projet a pour objectif la mise en œuvre de techniques pour engendrer automatiquement du texte sous contraintes.  
On reprogrammera une technique existante et on la testera sur de nombreux problemes, puis on essaiera d'introduire des contraintes de plus en plus complexes pour donner de plus en plus de sens au texte

### Utilisation du cloud pour du calcul haute performance ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Jean-Charles Régin](mailto:jcregin@gmail.com).
 - Prérequis : bien programmer en java pour éviter autant que possible l'utilisation de librairies annexes.

Le cloud est souvent utilisé pour heberger des serveurs. Dans le cas présent on souhaite l'utiliser pour faire du calcul intensif, ce que propose de plus en plus les fournisseurs de cloud computing, comme Google avec les Google compute engine. Néanmoins, entre la « theorie » et la pratique il y a souvent une grande différence. L'objectif de ce TER est la mise en place d'une solution (autrement dit d'un ensemble d'outils en Java) permettant d'executer un programme Java sur une machine sur le cloud et de communiquer avec cette machine. 

### Apprentissage de stratégies statiques ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Jean-Charles Régin](mailto:jcregin@gmail.com).
 - Prérequis : bien programmer en java ; un interet en programmation par contraintes est un plus.

De nombreuses methodes de resolution de problemes d'optimization combinatoires utilisent des methodes dynamiques, telle que la selection de variables ayant le plus d'impact.

L'idee est d'essayer de voir si on ne pourrait pas remplacer ces strategies dynamiques par des strategies statiques. Cela signifie qu'au lieu d'avoir une evaluation permanent des variables par rapport à un critère, on fait des precalculs puis on détermine un ordre de choix de variable a priori qui n'est plus remis en cause.


### Cabane à oiseaux connectée ###
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Gaetan Rey](mailto:gaetan.rey@univ-cotedazur.fr).
 
Le but de ce projet est d'instrumenter une grande cabane à oiseaux, à l'aide d'une plateforme de type Raspberry Pi et de capteurs pour transformer cette grande cabane en bois en un objet connecté offrant différents services. 

Cette cabane à vocation à rester toute l'année à l'extérieur à proximité (20 mètres) d'une habitation. 
On pourra donc connecter la plateforme au Wifi de la box de la maison. La liste des services et des capteurs n'est pas définie et pourra intégrer des idées provenant des étudiants. 
Actuellement les idées prévues sont :
 - Intégration d'une caméra pour une vision par-dessus pour visualiser tout ce qui est dans le plateau.
 - Utilisation de cette vidéo pour détecter l'absence de nourriture pour les oiseaux.
 - Intégration d'une ou plusieurs caméra latérale (au niveau de poteaux) pour observer les oiseaux.
 - Conception d'une interface permettant de visualiser en temps réel une ou plusieurs caméras.
 - Ajout de fonction d'enregistrement d'images, de séquences vidéo avec possibilité de synchronisation des différents flux.
 - Détection du type d'oiseaux ou à minima possibilité d'explorer une base de données des espèces pour identifier les espèces présentes.
 - Mise en place de statistiques (nombres d'oiseaux, fréquences, heures de passages, ...) avec possibilités d'exports des données et de visualisation de celle-ci au format graphique.
 - Une modélisation de coques de protection des capteurs pourra être envisagée pour impression en 3D.

Deux types de plateformes sont envisagées pour être utilisée dans ce projet. 
Soit une plateforme à base de Raspberry Pi (accompagner de capteur Grove), soit une plateforme à base de Phidget.


###  Défi orthographique ###
 - Nombre d'étudiants souhaités : entre 2 et 4.
 - Encadrants : [Serge Miranda](mailto:miranda.serge@gmail.com).

S'approprier sa langue est un enjeu humain, culturel et citoyen. Son apprentissage peut être soutenu par l'utilisation d'outils.
Le Conseil départemental 06 et le rectorat de Nice souhaitent s'associer autour d'une manifestation visant à promouvoir la réflexion linguistique des élèves chez les élèves de 6ème. Cela se manifestera au final par un "défi orthographique" qui se déroulera en présence d'un ensemble d'acteurs et de partenaires.

Le projet a deux niveaux : 
 - 3 mois sur une application web de correction de dictées (avec IPR Littérature ) avec un "defi orthographique" les 23 et 24 Mai (concours pedagogique) à Villeneuve Loubet (200 élèves de collège).
 - Stage de 3 mois en suivi par le CG06 dans le cadre de la diffusion IA en collège sur utilisation d'outils de Deep Learning, par exemple Tensor Flow, pour l'aide pédagogique à partir de milliers de dictées pour aiguiller les élèves sur des exercices adaptés.


### Ordonnancement sous contraintes ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Arnaud Malapert](mailto:arnaud.malapert@univ-cotedazur.fr).
 - Prérequis : programmer en c++ ; un intérêt en programmation par contraintes.

Ce travail porte sur l'étude d'un problème d'ordonnancement de tâches sur des machines parallèles avec des contraintes de qualification des machines. Une machine perd sa qualification pour une famille de tâche si cela fait trop longtemps qu'elle n'a pas exécuté une tâche de cette famille. 

L'objectif de ce TER est de continuer les travaux en cours sur ce sujet, notamment en développant des contraintes dédiées pour aider à la résolution du problème.

### Optimisation multiobjectif pour l'ordonnancement ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Arnaud Malapert](mailto:arnaud.malapert@univ-cotedazur.fr).
 - Prérequis : bien programmer en java ; un intérêt en programmation par contraintes.

Le but de ce TER est d'étudier des problèmes d'optimisation multiobjectif sur un réseau de contraintes temporelles de type PERT/CPM. L'optimisation multiobjectif a été très peu étudiée dans ces réseaux et tout reste donc à faire. Par contre, le problème d'ordonnancement est facile et très étudié. Beaucoup de variantes sont polynomiales.

 Les méthodes PERT/CPM ou diagrammes de Gantt sont fréquemment utilisées dans l'industrie. 
 Il existe de nombreux logiciels pour appliquer ces méthodes, par exemple Microsoft Project.
  
### Front de Pareto en programmation par contraintes ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Arnaud Malapert](mailto:arnaud.malapert@univ-cotedazur.fr).
 - Prérequis : bien programmer en java ; un intérêt en programmation par contraintes.

Ce travail porte sur la construction du front de Pareto en programmation par contraintes. 
En bref, le front de Pareto correspond à l'ensemble des solutions non dominées d'un problème multiobjectif.

L'objectif de ce TER est de développer des contraintes globales et des stratégies de recherche pour la construction du front de Pareto. La contrainte globale doit filtrer les solutions dominées alors que les stratégies de recherche doivent permettre de trouver efficacement des solutions non dominées. 


### Intégration de méthodes d'optimisation dans PlanetOptim ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [Arnaud Malapert](mailto:arnaud.malapert@univ-cotedazur.fr) et [Assia Kamal Idrissi](assia.elafouani@milanamos.com).
 - Prérequis : bien programmer en java ; connaître les bases de données.

Ce travail porte sur l'intégration de méthodes d'optimisation développées par les encadrants dans le logiciel PlanetOptim développé par l'entreprise Milanamos à Sophia Antipolis.

L'objectif est de concevoir les requêtes que l'application PlanetOptim développé en Python sur une base MongoDB doit envoyer à une base de données orientée graphe Neo4j. 
Cette communication passera par une queue de message RabbitMQ.

### Exploration exhaustive du Redi Cube ###
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [ Julien Bensmail](Julien.Bensmail@unice.fr)

Il existe de nombreuses variantes du Rubik's Cube, dont la complexité peut être évaluée via une exploration exhaustive de tous les mélanges possibles et de la manière de passer de l'un à l'autre. Un exemple parlant est celui du Rubik's Cube, pour lequel il est connu que le « Nombre de Dieu » est 20, ce qui signifie que tout mélange peut être résolu via une combinaison d'au plus 20 mouvements.

Le but de ce projet sera de mener une étude similaire sur une variante récente du Rubik's Cube, le Redi Cube, pour laquelle le nombre de Dieu n'est, à ma connaissance, pas encore connu. En plus de l'aspect « exploration exhaustive », on pourra s'intéresser à des aspects annexes, comme la recherche de méthodes pour résoudre le Redi Cube, la création d'une interface graphique pour faciliter l'utilisation, etc.


### ∆-Debugger de solveur de satisfiabilité en logique propositionnelle
 - Nombre d'étudiants souhaités : 1.
 - Encadrants : [ Valentin Montmirail](valentin.montmirail@univ-cotedazur.fr) et [ Marie Pelleau](marie.pelleau@unice.fr)
 
 L'écriture de solveur de satisfiabilité, qu'importe la logique, est une tâche extrêmement compliquée. 
Le développement peut donc impliquer des bugs très difficile à découvrir.

Une manière de déboguer automatiquement un solveur est de réaliser ce que l'on appelle un débogage delta.
Une seule hypothèse est effectuée : nous connaissons à l'avance le résultat attendu sur un jeu de tests t.

Nous lançons donc le solveur bogué sur le test t. Seulement, le solveur ne renvoie pas le résultat attendu.
Nous pouvons donc simplifier le test t, en supprimant certaines parties par exemple, afin d'obtenir un test t' qui a moins de chance de déclencher le bug dans le solveur. Si ce coup-ci le solveur répond correctement, alors le plus petit problème qui déclenche le bug est t, sinon nous avons trouvé un nouveau problème t', plus petit, qui déclenche le bug. Nous pouvons donc considéré que t = t' et recommencer ainsi toute la procédure. Cette procédure boucle tant que nous pouvons supprimer des parties dans t et que le solveur répond toujours de manière incorrecte.

- Références:
  - [Zel01] Andreas Zeller. Automated debugging : Are we close. IEEE Computer, 34(11) :26–31, 2001.
  - [Zel05] Andreas Zeller. Why Programs Fail : A Guide to Systematic Debugging. Morgan Kauf- mann Publishers Inc., San Francisco, CA, USA, 2005.


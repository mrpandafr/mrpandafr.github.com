---
layout: post
title: "Kivy   La découverte"
description: "Premier pas sur le framework Kivy."
category: "Kivy"
tags: [kivy,python,developpement]
---
{% include JB/setup %}
Ahhh, le but ultime de tout programmeur, trouver une solution simple, rapide et puissante de developpement.
Personnelement, Python répond en de nombreux points à cette demande, enfin tant que l'on ne cherche pas à faire une programmation orientée mobile. Là, les choses se compliquent, mais pas tant que cela.

### Kivy, wabon ?
{% highlight python %}
from kivy.app import App
{% endhighlight %}
voilà c'est gagné, il ne manque plus que la compilation pour votre terminal et vous avez une appli.
(en faite c'est simple de faire un tuto, je devrais en faire plus souvent).
Blague a part, kivy a tout de la solution de rève pour developper vite sur mobile.
Une syntaxe proche de python (oui, il y a un seul petit twist autour de cela, un langage propre de présentation); une documentation propre, un paquet d'exemples fournis ... une jeune communauté.

### HTML5 (Phonegap, AppAccelerator, etc ...) ou Flash Builder c'est pas mieux ?
non mais tu voix coco soit tu prends un truc qui à fait ses preuves (actionscript3 et air) et tu dev à la vitesse de l'éclair, soit tu vas passer un mauvais moment ...
non mais tu voix coco soit tu prends des solutions "open source" et de "demain" javascript et css3 tu vois c'est de la balle, il te faut juste une boite magique pour faire tourner le tout, et de la confiance.

Mouais, je connais les deux, pour avoir pratiquer les deux.
AS3 + Air (+ robotleg :)) ça dépote, mais l'executable final est ... pas beaucoup mieux qu'une 'application' en html+css+js, la boite noire pèse enormement au regard de la partie programmation, et même si les performances sont au rendez vous... je sais pas toute cette lourdeur...
Je dirais bien cela dépand du client, et de l'amour que l'on porte au ;
Moi, je ne l'aime pas plus que cela, affaire de gout.

Il n'empêche, coco tu as raison, c'est facile, et très très pénible (surtout html+css+js). Pas difficile, non, juste pénible et ennuyant.

### Donc kivy ça rocks du poney et code à ta place ?
Non, c'est la galère dès que l'on sort du code, vraiment l'étape de compilation pour Android (dans mon cas) a fahit me faire abandonner. (Tips, le chanal IRC est remplit de gens supers cools, faut y aller). (Tips, y a une jolie imagine d'un Ubuntu 12 toute jolie prète pour vous faire le boulot.).
J'ai plusieurs fois visé le mur, et me suis dis, bon c'est rigolo, mais pas moyen c'est trop casse gueule.
Heureusement, on a tous le droit de se tromper.
Déjà, l'executable (Apk, ami fan de la Pomme je pense à toi (et à moi) je t'enterrais l'experience un jour juste pour toi, et moi, mais pas avant 2 mois au moins) il est légé, pas un Fat Ass de 20 Mo.
Sur les terminaux testés pas de lag ... pas de lag graphiques, ou d'interaction avec l'utilisateur... c'est fluide et ce sorti de la boite.
C'est compilé, et pas un Warpeur magique, donc résultat à t0 = résultat à t+toutes les majs magiques prévu par M.Google. Moi je dors mieux depuis ce moment.

### Et t'as fait plein de trucs ?
Non, deux trois trucs persos, autour de Kivy et Numpi (oui, numpi tourne très bien).
Ce qui va débouller à un jeu autour de ces deux là. Je vais pouvoir mesurer de façon empirique qui des solutions de RAD que je connais est la plus rapide, et m'accompagnera cette année.
(dernier tips du post est le plus important, changer de temps en temps de compilateur, de langage ... ça ouvre de nouvelles perspectives, et on ne s'encrace pas).

### Donc tu vas faire un gros truc ?
Oui, c'est le but (et gros gros c'est vite dit). Une application, qui sera un jeu écrit en Python/Kivy, avec un leaderboard, des interractions en réseaux, et distribué sur les stores d'appli.
...
Et oui, je me dis que des plats du ventre, je vais en avoir pas mal... :) Alors stay tune.
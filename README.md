# alinasreise

J'ai fait ce site pour ma petite nièce de 10 ans, Alina.

Elle vit à Berne (donc germanophone) et est parti faire un Tour du Monde avec ses parents :)

Alinas Reise : le voyage de Alina.


Je lui ai fait ce petit site pour qu'elle prenne conscience de la distance en km qui la sépare de chez elle (de Berne donc).


Fonctionnement

Le site utilise l'API de google maps.

Au lancement du site, un premier point est marqué comme référence (ici Berne du coup)

On clique sur le bouton pour lancer la géolocalisation. On autorise alors le navigateur à accéder à l'information.

La fonction récupère les coordonnées et marque le 2e point qui est la position de l'utilisateur.

La fonction calcule ensuite la distance à vol d'oiseau (distance sphérique) en mètres puis est convertie en km puis arrondie à l'entier (parce qu'il faut pas déconner)

Ce résultat est affiché dans le rectangle violet.

Si la géolocalisation n'est pas autorisée, un pop-up d'alerte renvoie "pas de localisation" en allemand ;)

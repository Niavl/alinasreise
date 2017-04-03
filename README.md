# alinasreise

J'ai fait ce site pour ma petite nièce de 10 ans, Alina.

Elle vit à Berne (donc germanophone) 

Elle et ses parents sont partis faire un Tour du Monde :)
Je lui ai fait ce petit site pour qu'elle prenne conscience de la distance en km qui la sépare de chez la ville où elle vit (Berne).


"Alinas Reise : le voyage de Alina."


Fonctionnement

Le site utilise l'API de google maps.

Au lancement du site, un premier point est marqué comme référence (ici Berne du coup).

On clique sur le bouton pour lancer la géolocalisation. Le navigateur demande l'autorisation d'accéder à l'information.

La fonction récupère les coordonnées de l'utilisateur et marque le 2e point.

La fonction calcule ensuite la distance à vol d'oiseau (distance sphérique) entre ces 2 points en mètres puis est convertie en km puis arrondie à l'entier (parce qu'il faut pas déconner).

Ce résultat est affiché dans le rectangle violet.

Si la géolocalisation n'est pas autorisée, un pop-up d'alerte renvoie "pas de localisation" en allemand ;)

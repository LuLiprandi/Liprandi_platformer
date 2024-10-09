# Liprandi_platformer
Pour ce projet jai fais en classe: 
l'utilisation du gameinstance pour la persistance des données simples.
un système de collecte d'objets.
un système d'affichage de score
un système d'interaction avec des éléments du décors / environnement.

Ce que j'ai rajouté par moi même: 

-Un deuxième éléments collectable, que j'ai nommé "Money" et qui augmente de 100 par 100, j'ai fait en sorte qu'il s'affiche sur l'écran via un HUD, et j'ai demandé au gameinstance de garder la valeur en mémoire dès que la partie est active. Une fois le niveau fermé et recommencé, le compteur se met à 0. 

- J'avais créé une interaction de base en appuyant sur E, avec une lumière et la porte que j'ai mis a la tout fin de mon niveau.

- J'ai créé un niveau deux qui est relié par un portail.

- J'ai crée des boutons qui sont reliés à des lumières (0. 1. 2) qui une fois allumé permettent d'ouvrir la porte de fin de niveau. Les boutons s'activent avec E et restent enregistrer dans le gameinstance, il y a un bouton qui se trouve dans le niveau deux, une fois le bouton activer les autres lumières reste allumer, mais les collectibles respaw, toutefois, le score ne se reset pas d'un niveau a l'autre. Une fois toutes les lumières allumées, la porte final s'ouvre et c'est la fin du "jeu"

- J'ai créé une plateforme qui bouge, elle bouge tout le temps et suit la direction d'une variable que j'ai mis en "Vector", car ça va me permettre de plus facilement décider de la position et de la direction de ma plateforme. 

- J'ai enfin fait un level design type side scroller, j'ai enlevé le blueprint dans le Parent de mon BP_Player qui permettait de bouger la camera et j'ai fais un petit level design rapide pour présenter toutes les fonctionnalités demandées.  
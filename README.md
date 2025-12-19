# BAE_ERW_Plat
## Platformer 3D dans le style de Mario Galaxy avec des changements de gravité et des petites planètes enrichissant les éléments de platformer
### Contrôles : 
|Action|Touches|
|---|---|
|Déplacements|ZQSD|
|Saut|Barre espace|
|Regarder autour de soi|Souris|

Astuce : Pour vous déplacer avec plus de facilité lorsque la gravité n'est pas vers le bas, regardez dans la direction dans laquelle vous voulez aller et avancez avec z

Mes difficultés : 
- Je n'ai pas réussi à tourner la caméra quand la gravité change pour faciliter les déplacements malgré de nombreuses tentatives
- Le personnage est un peu tordu quand on marche vers le haut sur un mur ou une planète
- J'ai eu du mal à faire les bonnes collisions pour la planète cubique (les coins étaient soit pointus soit creux) mais en jouant avec le auto convex collision, j'ai trouvé une bonne collision
- Je me faisais parfois avoir avec les Components des blueprints des pièges en mettant les spikes en enfant du cube, ils héritaient du scale du cube et étaient donc étirés. Pour le régler, il suffisait de mettre les spikes en enfant de la Scene Component du Blueprint

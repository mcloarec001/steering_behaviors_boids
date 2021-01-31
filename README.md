# steering_behaviors_boids

Ce projet simule le déplacement d'une foule, ou plus précisément des animaux comme un groupe d'oiseaux. Trois types de déplacements sont implémentés :
- La cohésion : le groupe se rapproche vers son centre
- La séparation : le groupe s'explose vers son exterieur
- Le mouvement droit : le groupe se déplace en ligne droite dans un des 4 axes, directions possibles : left, right, up, down, up_left, up_right, down_right, down_left

Une grande partie du code est inspirée du tutoriel accessible à ce lien : 
https://alan-turing-institute.github.io/rsd-engineeringcourse/ch01data/084Boids.html?fbclid=IwAR1GV0aOF4BujxLXeJ0TvN65MG728NONVlPpJNJfIt-11tC-5tj-ThSHW7c

## Execution

Les librairies à installer sont dans le fichier `requirements.txt`. 
Pour executer le code il faut lancer le notebook `main.ipynb`.

## Paramètres
- boid_count : nombre de boïds
- limits : dimension de la carte
- alert_distance : distance maximale entre les boïds
- move_strength : force du mouvement
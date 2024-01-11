# Pré-prototype / programmation de l'interaction

L'impression 3d de ma structure lancée au début des vacances est prête. Je me rend compte qu'il y a certains éléments à ajuster ainsi qu'une autre impression à lancer au vue des défauts présents sur celle-ci.
En parallèle, je me lance sur la programmation de mon interaction sur Arduino. Je commence à explorer les else/if. Je me rends compte que mes conditions sont trop complexes et se chevauchent. Je décide donc d'utiliser les states machine. À la fin de la journée, Pierre me conseille de travailler avec millis(); plutôt que delay(); et d'oublier state machine car trop complexe pour le peu d'états présents dans mon projet.

Je recommence donc mon code en utilisant switch/case ainsi qu'Enum.
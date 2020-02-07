# Compte rendu TP1: Admin Système

## Exercice 2:

*Manuel*
1. La commande *which* permet de localiser une commande à partir de ses arguments.
2. &pattern affiche seulement les lignes contenant le terme (ici pattern), /pattern permet de mettre en surligné le terme recherché.
3. On quitte le manuel avec la touche q.
4. man 6 intro avec le numero 6 correspondant à la section que l'on voulait.

*Navigation dans l’arborescence des fichiers*

5. On a un refus de permission afin d'acceder au mode root.
6. Si on passe en mode sudo un mdp est demandé pour accéder au root mais la commande n'est quand même pas acceptée. Il faut taper sudo -i pour aller directement dans root.
8. Tout ce passe bien( commande sudo rm).
9. Toujours avec rm.
10. Cela ne marche pas car le dossier 2 n'est pas vide.
11. On rajoute l'extension -r de rm.

*Commandes importantes*

1. Avec date on obtient la date et l'heure. Time permet de determiner la durée(real: temps réel, user: temps cpu,sys: temps utilisé par le système) d'une tâche.
2. ls permet d'afficher les dossiers du répertoire, mais la permet d'afficher tout les dossiers y compris ceux commencant par un point qui était "caché" avec ls. ls -a permet donc d'afficher les dossiers cachés.
3. 
4. Il n'y a pas d'entrée sur ll. Alias nous renseigne sur les raccourcis de commandes dont l, ll correspond donc a l -alF a:dossier caché, F:accepte des caractères spéciaux et l:accepter un format long.
5. ls /bin
6. ls permet d'afficher les dossiers dans le répertoire en cours. Si des arguments d'entrées sont données ls affichera les dossiers contenu dans les arguments.
10. Donne le type de document.
11. Quand on ouvre titi on ouvre toto reelement donc lorsque toto est modifié, titi affiche aussi la modification. Lorsque l'on supprime toto, titi est toujours un lien vers le même document, seulement l'acces direct a toto est supprimé.
12. Le lien d'un lien continue d'afficher les modifications et inversement. Cependant lorsque l'on tue le lien "mère" titi, tutu affiche un document vide.
15. Affiche un contenu lié à l'ordinateur, on le fait défiler quand on appuie sur enter.
16. Il contient les info de l'utilisateur. man passwd

## Exercice 4:
On a appris a actualiser directement (avec source) sans redemarrer la machine puis à modifier les couleurs de la police(trentaine) et du fond(quarantaine). Voici notre config : \033[31m\][\A]\[\033[32m]]\u@\h\...
31:rouge 32:vert 34:bleu u@:user A:heure

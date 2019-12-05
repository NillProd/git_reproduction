# git_reproduction
Reproduction du fonctionnement de GIT (github) en local

Ceci est un script dynamique réalisé en PHP POO.
Pour lancer le script assurez-vous d'utiliser Linux ( Debian, ubuntu ou autres )

***-**-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-**-***
<IMPORTANT> NE PAS UTILISER LE SCRIPT DANS UN DOSSIER AVEC DES FICHIERS QUE VOUS NE SOUHAITEZ PAS SUPPRIMER !!!<!IMPORTANT>
***-**-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-**-***

- Mettez le fichier "mygitlight.php" dans un dossier <! VIDE !>
- Lancer le script : php mygitlight.php

Vous entrez dans la dimension binaire orienté objet celle ou beaucoup d'humanoide continue.
Voici leurs histoires :
[][]
mgl --help      ==> AFFICHE LE MAN de myGitLight ( mgl )
[][]
- mgl init      ==> "Congratulation ! Your Repository has been save in /home/thomas-dev/Documents/git/git_reproduction"

Un dossier caché à été créer à la racine du dossier ( oui il est caché mais bien existant )
Ayant pour contenu :
- un dossier ADD
- un dossier commit ( stockant tous les commit compressé avec un id aléatoire)
- un fichier log ( enregistrant l'id des commit avec le message entré par l'utilisateur )
- le fichier myGitLight.php sauvegardé !

Faites un test !
- Créer un fichier et un répertoire à la racine
- CRTL + C ==> quitte le programme et retourne sur le terminal
- touch filetest.txt | mkdir repositorycopy
- php myGitLight.php
- mgl add *
OU
mgl add filetest.txt repository/ OU repository
( ajoute tous les fichiers dans ADD )


- mgl commit *
OU
mgl commit repository/ OU repository
(Créer une archive compressé avec un id aléatoire et écris sur le fichier .log l'id + le message de l'utilisateur)

- mgl rm *
OU
mgl rm filetest.txt repository/ ou repository
( Efface tous les fichiers dossier dans le répertoire )

Voila C'est tout :)
C'est une version pré-alpha !
Code source disponible donc si vous souhaitez l'améliorer n'hésitez pas !

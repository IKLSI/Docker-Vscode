## SAE 2.03 Equipe 12

## Présentation du projet

* Pour ce projet nous avons décider de mettre en place un éditeur de texte afin d'obtenir vscode dans un navigateur.

## Prérequis pour lancer le container 

* Avoir docker d'installer sur sa machine
* Avoir git d'installer sur sa machine

## Lancement du container

* Cloner le repository git à l'aide de la commande suivante : <b>git clone git@github.com:IKLSI/docker-sae-203-equipe12-vscode</b>
* Se placer dans le dossier docker-sae-203-equipe12-vscode
* Lancer la commande suivante : <b>docker build -t nom_du_container -f DockerFile chemin/absolu</b>
* Puis a commande suivante : <b>docker run -p 8443:8443 -v $(pwd)/src_docker:/home/Docker nom_du_container</b> sous Linux
* Sous Windows : <b>docker run -p 8443:8443 -v chemin/absolu/src_docker:/home/Docker nom_du_container</b>
* Enfin, ouvrir un navigateur et taper l'adresse suivante : <b>localhost:8443</b>

## Autres projets 

* `gh-pages` : <a href="https://iklsi.github.io/docker-sae-203-equipe12/">Lien</a>
* `dépôt` : <a href="https://github.com/IKLSI/docker-sae-203-equipe12-depot">Lien</a>
* `chat` : <a href="https://github.com/IKLSI/docker-sae-203-equipe12-chat">Lien</a>

## LEVESQUE Kyliann, LE BRETON Kyllian, MENARD Esteban
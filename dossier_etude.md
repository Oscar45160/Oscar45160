| Besoin                                                                             | Nombre d'outils différents demandés | Logiciels proposés |
| ---------------------------------------------------------------------------------- | :----------------------------------:| -------------------|
| Avoir des Gestionnaires de bureau/fenêtre (dont un qui vous plaise)                | 4                                   | xfce4 i3 lxde OpenBOx|
| Avoir deux utilisateurs: vous et "stagiaire"                                       |                                     | ospimpaud stagiaire|
| Compiler un programme C                                                            | 2                                   | gcc llvm           |
| Regarder les pages de man de la libC                                               | 2                                   |manpages-fr       manpages-fr-dev|
| Lancer un `make`                                                                   |                                     |                    |
| Éditer du code source                                                              | 4                                   |nano vi geany bluefish|
| Déboguer du code                                                                   | 2                                   |gdb ddd             |
| Naviguer sur le Web                                                                | 2                                   |firefox-esr chromium|
| Éditer une image matricielle (png...)                                              | 2                                   |gimp krita          |
| Éditer une image vectorielle (svg)                                                 | 1                                   |inkscape            |
| (Dé)Compresser les formats `targz` et `7z` et `rar`                                | 1                                   | p7zip unzip        |



### Gestionnaire de paquets
* Installer un paquet

`apt-get install <NomDuPaquet>`

* Désinstaller un paquet

`apt-get uninstall <NomDuPaquet>`

* Rechercher un paquet

`apt-cache search`

* Mettre a jour un paquet

`apt upgrade`

* Lister les fichiers installés par un paquet

`apt-file list <NomDuPaquet>`

* Trouver le paquet associé a un fichier

`dpkg -S <CheminAccès>`

### Réseau
* Pouvoir se connecter en `ssh`

`ssh <login>@<ipAdress>`

### Sauvegardes


### Services
* Savoir démarrer/stopper un service

`systemctl start nom_du_service.service`

`systemctl stop nom_du_service.service`

* Savoir vérifier l'etat d'un service

`systemctl status nom_du_service.service`

* Savoir afficher les messages d'erreur

`dmesg | grep -i error`


### Choix des solutions

#### Gestionnaires de bureau
Pour ce qui est des gestionnaires de bureau j'ai installé xfce4 car je le trouve assez simple d'utilisation et assez légé à télécharger et une interface assez compréhensive.

Pour i3 je l'ai choisi car je le connaissais de nom et j'ai des amis qui l'utilisent quotidiennement même si je sais que c'est peut être plus avancé comme utilisation de linux j'ai tenu à le mettre dans ma machine.

Pour LXDE j'ai vu sur internet que c'était assez ressemblant à xfce4 avec une interface un peu différente alors c'est pour jouer entre les deux que j'ai fait ce choix.

Et le dernier qui est OpenBox c'est en cherchant sur internet que j'ai vu qu'il était assez connu je ne l'avait jamais testé avant mais j'ai trouvé ça plutot pas mal

#### Compiler un programme C
J'ai d'abord installé GCC (GNU Compiler Collection) qui est certainement un des plus connus et que j'utilise pendant mes études ça m'a donc paru normal de le mettre sur ma machine

Ensuite j'ai mis llvm qui est un programme qui ressemble asser a gcc et qui fonctionne très correctement

#### Editer du source code
J'ai mis VI car c'est l'éditeur de base quand on en a besoin il est toujours là il est donc très important malgré le fait qu'il soit assez peu intuitif au début

J'ai après mis nano qui est un éditeur ressemblant a VI mais qui est plus simple peut être plus moderne.

J'ai installé geany qui est beaucoup plus pratique lorsque l'on a de plus gros projets de développement avec une interface graphique assez bien donc plus lisible

Et ensuite j'ai installé bluefish qui ressemble un peu à geany et qui aura la même utilisation c'est à dire pour des plus gros projets

#### Deboguer du code

J'ai d'abord installé gdb qui est le seul que je connaissait au départ qui est plutot simple d'utilisation 

Ensuite en faisant des recherches j'ai installé ddd qui se rapproche assez de gdb avec la même facilité d'utilisation

#### Naviguer sur internet

J'ai tout d'abord installé firefox-esr car c'est celui que j'utilise quotidiennement donc la question ne s'est pas vraiment posé

Et comme deuxième navigateur j'ai opté pour Chromium qui je trouve à une plus belle interface

#### Editer une image matricielle

J'ai installé gimp en premier lieu car c'est un très bon logiciel d'édition d'images, parfois comparé a photoshop mais en libre de droit donc mieux

Et ensuite krita car c'était le seul autre que je connaissais et je sais qu'il fait bien le travail

#### Editer une image vectorielle

J'ai installé inkscape car c'était le seul que je connaissais déjà et je sais qu'il fonctionne 

#### Décompresser des formats

J'ai installé p7zip car je le connaissais d'avant je sais qu'il fonctionne très bien et il est assez intuitif

J'ai aussi mis unzip car c'est beaucoup plus parlant comme logiciel

---
Notice d'installation d'un linux sur VirtualBox
---



### Partie VirtualBox
Créez une nouvelle machine

Mettre le nom

Entrer le repertoire ou sera stocké la machine virtuelle dans /home/scratch/login

Type: linux

Version: Debian
-> Suivant:

Mettre 2048mb de mémoire vive
-> Suivant:

cocher Créer un disque dur virtuel maintenant
-> Suivant:

Cocher VDI
-> Suivant:

Cocher dynamiquement allouer
-> Suivant:

mettre 8.00Gio

Appuyer sur Créer:


Cliquer sur Configuration:

Cliquer sur stockage:

Cliquer sur le disque bleu a coté de lecteur optique:

Cliquer sur choose a disk file:

Ajouter votre .iso d'une version de debian

Cliquer sur Démarrer:

### Partie machine virtuelle:

Cliquer sur install:

Choisissez votre langue ici francais

Choisissez votre pays ici France

Choisissez votre clavier ici Français

Choisissez le nom de la machine (pas d'espaces)-> Continuer:

configurer le reseau laissez vide -> Continuer:

Entrez le mot de passe voulu pour super utilisateur -> Continuer:

Confirmez le mot de passe -> Continuer:

Créez un autre utilisateur ici ospimpaud -> Continuer:

Choisissez l'identifiant ici ospimpaud -> Continuer:

Entrez le mot de passe de l'utilisateur -> Continuer:

Confirmez le mot de passe -> Continuer:

Dans partitionner les disques choisissez Assisté- Utiliser un disque entier

Confirmez votre disque a partitionner

Choisissez Tout dans une seule partition:

Selectionnez Terminer le partitionnement et appliquer les changements

Choisissez OUI:

Selectionnez NON

Selectionnez France

Selectionnez ftp.fr.debian.org

Entrez le proxy ici: `http://193.49.118.36:8080/`

Dans l'écran popularity-contest cliquez NON

Dans Selection des logiciels tout déselectionner sauf utilitaires usuels du système -> Continuer

Installer le programme de démarrage GRUB -> Oui:

Choisir le disque dur /dev/sda

Dans Terminer l'installation -> Continuer:

Redemarrage de la VM
Choisir dans Grub debian
entrez les identifiants de root

`apt-get update`

`apt-get upgrade`

#### Installation d'une interface graphique
`apt-get install xfce4`

taper 'O' pour Oui

Redemarrer la VM

Installation de i3

`apt install i3`

taper 'O' pour Oui

Installation de OpenBox

`apt install openbox`

taper 'O' pour Oui

Installation de LXDE

`apt instal lxde`

taper 'O' pour Oui

#### Ajout d'un utilisateur stagiaire

`adduser stagiaire`

choisir le mdp:

Confirmer ajouter des informations supplémentaires si vous voulez


#### Compiler programme

`apt install gcc`

taper 'O' pour Oui

`apt install llvm`

taper 'O' pour Oui

#### Installer man libC

`apt install manpages-fr`

`apt install manpages-fr-dev`

#### Lancer un make



#### Editer du source code
`nano`

`vi`

`apt install geany`

taper 'O' pour Oui

`apt install bluefish`

taper 'O' pour Oui


#### Debogguer du code

`apt install gdb`

taper 'O' pour Oui

`apt install ddd`

taper 'O' pour Oui

#### Naviguer sur internet

`apt install firefox-esr`

`apt install chromium`

taper 'O' pour Oui

#### Editer une image matricielle

`apt install gimp`

taper 'O' pour Oui

`apt install krita`

taper 'O' pour Oui

#### Editer une image vectorielle

`apt install inkscape`

taper 'O' pour Oui

#### Decompresser

`p7zip` - `unzip`

#### Installer un serveur web

`apt install apache2 php libapache2-mod-php mariadb-server php-mysql`

Ouvre firefox regarde 127.0.0.1 si ca marche ca affiche It Works

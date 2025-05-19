# Projet_IA : Polytech Labyrinthe

## Préface
La procédure d'installation qui va vous être donnée est conçue pour utiliser le jeu avec un environnement Linux. 
Il est recommandé de créer un dossier qui va contenir tous les éléments

## Guide de pré-installation

Pour Utiliser les bibliothèque qui vont être utilisée dans le jeu, vous aurez besoin d'installer, dans le répertoire créer pour contenir le jeu, la bibliothèque d'interface graphique SDL2 voici les étapes d'installation :
1. git clone https://github.com/libsdl-org/SDL.git -b SDL2
2. cd SDL
3. mkdir build
4. cd build
5. ../configure
6. make
7. sudo make install

Une fois les fonctions principales de la bibliothèque graphique installé, vous aurez besoin des fonctions complémentaire. Suivez la procédure suivante : 
1. sudo apt update
2. sudo apt install libsdl2-dev libsdl2-image-dev libsdl2-ttf-dev libsdl2-mixer-dev \
                 libavformat-dev libavcodec-dev libavutil-dev libswscale-dev \
                 libswresample-dev libavdevice-dev libavfilter-dev

En supposant que toutes les installations de fonctions ont réussi, vous devrez être en mesure de faire fonctionner le jeu.

## Installation du jeu

Le dossier zip contnu dans cette page contient tout les éléments relatifs au jeu : Les fichier source, les scripts et les éléments importés comme les images.
Vous devez extraire les éléments de ce dossier et les téléchargé dans le même dossier où vous avez installé SDL.

## Exécution du jeu

Pour exécuter le jeu, il faut utiliser l'invite de commande sous linux et de se placer dans le répertoire qui contient le jeu.
Exemple : Mon dossier est dans mon espace mémoire de windows donc pour y accèder je me place dans le répertoire /mnt/c/Users/johan/Documents/cours/Projet_IA/Jeu qui me permet d'accèder à ce document : 
![Dossier](https://github.com/user-attachments/assets/28b6eef6-d73e-439b-b583-044c19c1501d)

utiliser la commande make pour compiler avec le makefile et ./jeu pour exécuter le jeu. 

Vous devriez arriver sur ce menu : 


![menu](https://github.com/user-attachments/assets/58e4487b-9315-4207-b1d8-318ccdfe8818)

Cliquer sur jouer pour commencer la partie.
Vous commmencez dans le coin en haut à gauche du labyrinthe, comme ceci :


![Départ](https://github.com/user-attachments/assets/87111dbe-1306-4365-ad0f-2278a6fe77d0)

Et le but est d'arriver dans le coin en bas à gauche du labyrinthe en évitant de vous faire attraper par la créature.


![gameplay](https://github.com/user-attachments/assets/ab9cd739-27b6-4e38-9c2d-ec4760edb28d)

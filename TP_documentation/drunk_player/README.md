# Drunk_player

## Description


Drunk_player est un système de lecture de vidéos qui a trop bu. Il lit les vidéos contenues dans un dossier par morceaux, aléatoirement et parfois en transformant l'image.

Drunk_player utilise la bibliothèque de traitement d'image OpenCV et est composé :

* d'une bibliothèque (drunk_player) contenant le code de base
* d'un programme graphique (drunk_player_gui) qui affiche le résultat à l'écran
* d'un programme console (drunk_player_cli) qui sort le résultat dans un fichier

## Dépendances 

* openCV
* Boost

## Compilation 

<span style="color: blue">mkdir</span> build
**cd** build
cmake ..
**make**

## Utilisation

./drunk_player_gui.out ../**data**/ 

![Image of gui](./drunk_player_gui.png)


# Projet-Taha-Hassan-GoL-5.0

## Mode Texte

* Pour compiler en Mode Texte, entrez la commande suivante:

```
make MODE=TEXTE
```

* Pour lancer le jeu en mode texte, entrez la commande suivante:

```
./bin/main grilles/<Nom-grille.txt>
```

Quand le jeu est lancé, on utilises les touches suivants:

* touche entrer qui permet d'évoluer la grille
* touche c pour activer/désativer le voisinage cyclique
* touche v pour activer/désactiver le viellissement
* touche o pour afficher la periode
* touche q pour quitter le jeu
* touche n pour charger une nouvelle grille, puis entrez la commande suivante:
```
grilles/nom_de_grille.txt
```

## Mode Graphique 

* Pour compiler en Mode graphique, entrez la commande suivante:

```
make 
```

* Pour lancer le jeu en mode graphique, entrez la commande suivante:

```
./bin/main_cairo grilles/<Nom-grille.txt>
```
Quand le jeu est lancé, on utilises les touches suivants:

* Clic gauche qui permet d'évoluer la grille
* Clic droit pour quitter le jeu
* touche c pour activer/désativer le voisinage cyclique
* touche v pour activer/désactiver le viellissement
* touche o pour afficher la periode
* touche n pour charger une nouvelle grille, puis entrez la commande suivante:
```
grilles/nom_de_grille.txt
```

Pour créer une archive, il faut entrer la commande:

```
make dist
```
Pour créer une documentation, il suffit d'entrer la commande suivante:
```
make docs
```

Pour effacer tous les fichiers objets,l'executable et la librairie, il suffit d'entrer la commande suivante:

```
make clean
```
#Version 5.0 correspond au code du niveau 5
#Version X.0 correspond au code du niveau X






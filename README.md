# Réalisation de slides avec Marp

## Installation

1. Installer VS Code [(lien)](https://code.visualstudio.com/download)
1. Installer l'extension **Marp for VS Code** [(lien)](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

## Marp for VS Code

Dans un projet Marp, deux icônes apparaissent lors de l'édition d'un fichier `.md` :

- ![](./README_images/apercu.jpg) : permet d'ouvrir le panneau d'aperçu en temps réel,
- ![](./README_images/marp.jpg) : permet d'exporter votre travail en fichier **PDF** par exemple (bien choisir le format d'export, par défaut : **HTML**).

## Thème

Un thème vous est fourni.

Vous pouvez le modifier en éditant le fichier `theme/ece.css`.

Vous pouvez également créer un nouveau thème en créant un nouveau fichier et en indiquant son nom grâce à la ligne suivante :

```CSS
/* @theme nomDuTheme */
```

Vous devez également rajouter votre thème à la liste des thèmes dans le fichier `.vscode/json`.

### Aide 

Pour vous aider à styliser les éléments, vous pouvez cliquer sur `Help` > `Toggle Developer Tools`.  
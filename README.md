# SFIPACK README

## Working with Markdown
## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
Pack d'extensions de base pour les développeurs de SFI.

### Réglage pour le PHP
Aller dans Extensions.
Rechercher @builtin php
Désactiver Fonctionnalités de Langage PHP. Laisser Concepts de base du langage PHP activé pour le highlighting.
Rajouter le code suivant dans le fichier settings.json accessible en allant dans Fichier -> Préferences -> Paramètres. Puis en cliquant sur l'icone en haut à droite "Afficher les paramètres (en JSON)";

    "[php]": {
        "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?",
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
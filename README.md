# Aide pour Utiliser Emacs et Rendre les Devoirs de l'IED

Pour une assistance à la prise en main d'Emacs et pour rendre les devoirs de l'IED, voici deux fichiers qui pourront être utiles :

- `init.el` : fichier de configuration pour Emacs (optionnel)
- `ied-latex-standard.org`
- `[fichier devoir à ajouter]`

## Installation

Pour utiliser Emacs :

1. Installer Emacs
    #+end_src
    $ sudo apt-get install emacs
    #+begin_src 
2. Installer LaTeX
    #+end_src
    $ sudo apt-get install texlive-full
    #+begin_src 
3. Lancer Emacs
    #+end_src
    $ emacs &
    #+begin_src 

## Les Commandes

Il est conseillé de parcourir le tutoriel pour apprendre les commandes de base. Sinon, voici quelques commandes de base :

- `Ctrl-g` : pour quitter
- `Ctrl-f`, `Ctrl-b`, `Ctrl-p`, `Ctrl-n` : pour avancer, reculer, monter, descendre le curseur respectivement.
- `Ctrl-x Ctrl-f` : pour ouvrir un fichier
- `Ctrl-x Ctrl-s` : pour sauvegarder
- `Ctrl-x Ctrl-c` : pour quitter

## Les Devoirs

Pour rendre un devoir en utilisant Org-mode, vous devez copier le fichier `ied-latex-standard.org` sur votre machine, en notant le chemin d'accès qui sera utilisé plus tard.

Pour rédiger un devoir, suivez ces étapes :

1. Ouvrez une copie du fichier "devoir". Deux solutions possibles :
    - Si vous êtes déjà dans Emacs, utilisez la commande `Ctrl-x Ctrl-f` et entrez le nom de votre fichier dans le dossier choisi,
    - Ou bien, à partir de la ligne de commande, exécutez `emacs [COPIE FICHIER] &` pour ouvrir une fenêtre avec un fichier du même nom.

2. Rédigez votre devoir sous la marque "New page", en utilisant la notation avec Org-mode.

3. Imprimez votre devoir en PDF avec la commande `Ctrl-c Ctrl-e l p`, et votre devoir est prêt.
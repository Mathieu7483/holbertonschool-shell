<img src= "https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/holberton%20modif.png">

# 🐚 Projet : Les Fondamentaux du Shell - Naviguer et Manipuler le Système
Bienvenue dans ce projet d'initiation au Shell (Bash), l'interface en ligne de commande de Linux ! Ce projet est la première pierre angulaire de ma formation, me permettant de comprendre et d'interagir directement avec le système d'exploitation. J'ai exploré ici les commandes essentielles pour naviguer dans le système de fichiers, manipuler fichiers et répertoires, et comprendre les bases du fonctionnement des commandes.

Ce que l'on appelle souvent "terminal" ou "console" est en réalité une interface pour interagir avec le Shell. Maîtriser le Shell, c'est acquérir une autonomie précieuse et une efficacité accrue pour le développement et l'administration système.

# 🎯 Objectifs d'Apprentissage
À la fin de ce projet, je suis capable d'expliquer à quiconque, sans l'aide de Google :

Concepts Généraux
Qu'est-ce que "RTFM" signifie et pourquoi c'est important.

Le rôle d'un Shebang (#!) dans les scripts.

Ce qu'est le Shell et sa différence avec un terminal.

La shell prompt et son utilité.

Les bases de l'utilisation de l'historique des commandes.

Navigation dans le Système de Fichiers
Les commandes ou "built-ins" cd, pwd, ls et leur fonction.

Comment se déplacer efficacement dans le système de fichiers.

Le rôle des répertoires spéciaux . (répertoire courant) et .. (répertoire parent).

Définition du répertoire de travail (working directory), comment l'afficher et le modifier.

Différence entre le répertoire racine (/) et le répertoire personnel (home directory).

Caractéristiques des fichiers cachés et comment les lister.

L'utilité de la commande cd -.

Inspection du Système
Les commandes ls, less, file et leur utilisation.

Comment utiliser les options et arguments avec les commandes.

Comprendre le format long de ls (ls -l) et ce qu'il affiche.

Manipulation de Fichiers et Répertoires
Les commandes cp (copie), mv (déplacement/renommage), rm (suppression), mkdir (création de répertoire).

Le concept et l'utilisation des "wildcards" (*, ?, []).

Les liens symboliques (symlinks) et les liens physiques (hard links), et leurs différences.

Travailler avec les Commandes
Les commandes type, which, help, man et leur rôle pour comprendre les commandes.

Les différents types de commandes (exécutables, built-ins, alias).

Ce qu'est un alias et son utilité.

Quand utiliser help plutôt que man.

Comment lire une page de manuel (man page) et comprendre ses sections.

Raccourcis Clavier et LTS
Les raccourcis clavier courants pour Bash.

La signification de LTS (Long Term Support).

# 🛠️ Technologies et Environnement
Interpréteur de commandes : Bash

Système d'exploitation : Ubuntu 22.04 LTS

Éditeurs de texte : vi, vim, emacs

# 📖 Structure du Projet et Scripts
Ce dépôt contient une série de scripts Bash, chacun étant une solution à un exercice spécifique visant à maîtriser les commandes de base du Shell. Chaque script est conçu pour être exactement deux lignes de long et commence par le shebang #!/bin/bash.

README.md : Ce fichier, décrivant le projet et les objectifs.
* **[Lien vers le dossier basics](https://github.com/Mathieu7483/holbertonschool-shell/tree/main/basics)**
* **[Lien vers le dossier init_files_variables_and_expansions](https://github.com/Mathieu7483/holbertonschool-shell/tree/main/init_files_variables_and_expansions)**
* **[Lien vers le dossier io_redirections_and_filters](https://github.com/Mathieu7483/holbertonschool-shell/tree/main/io_redirections_and_filters)** 
* **[Lien vers le dossier permissions](https://github.com/Mathieu7483/holbertonschool-shell/tree/main/permissions)**



# 💡 Contraintes et Bonnes Pratiques
Ce projet adhère à des règles strictes pour garantir la qualité et la conformité des scripts :

Shebang Obligatoire : La première ligne de chaque script doit être #!/bin/bash.

Deux Lignes Maximum : Chaque script doit être composé d'exactement deux lignes.

Fin de Fichier : Tous les fichiers doivent se terminer par une nouvelle ligne.

Exécutable : Tous les scripts doivent être rendus exécutables (ex: chmod u+x mon_script).

Restrictions de Commandes : Interdiction d'utiliser les backticks (`), &&, || ou ;.

Style Betty : Le code (si applicable) doit respecter le style Betty.

# 👨‍💻 Comment Exécuter les Scripts
Pour exécuter ces scripts, assure-toi d'être sur un système Ubuntu 22.04 LTS.

Rendez le script exécutable (une seule fois par script) :

```bash

chmod u+x NOM_DU_SCRIPT
Par exemple : chmod u+x 0-current_working_directory

Exécutez le script :
```
```bash

./NOM_DU_SCRIPT
Par exemple : ./0-current_working_directory
```

# ✍️ Auteur
Mathieu GODALIER - Élève en programmation

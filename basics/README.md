<img src= "https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/holberton%20modif.png">

# 🐚 Projet : Les Fondamentaux du Shell (Bash) - Maîtrise de la Ligne de Commande
Bienvenue dans ce projet d'initiation au Shell Bash ! Ce module est le point de départ pour interagir efficacement avec un système Linux. J'ai exploré ici les commandes essentielles pour naviguer dans le système de fichiers, manipuler fichiers et répertoires, et comprendre les bases du fonctionnement des commandes.

Maîtriser le Shell, c'est acquérir une autonomie précieuse et une efficacité accrue, que ce soit pour le développement ou l'administration système.

# 🎯 Objectifs d'Apprentissage
À la fin de ce projet, je suis capable d'expliquer clairement à quiconque :

Concepts Généraux
Le sens de l'expression "RTFM".

Qu'est-ce qu'un Shebang (#!) et son rôle.

Ce qu'est le Shell et sa distinction avec un terminal.

La shell prompt et les bases de l'historique des commandes.

Navigation & Exploration
Les commandes cd, pwd, ls et leur utilisation.

La navigation dans le système de fichiers et les répertoires spéciaux (. et ..).

Le répertoire de travail, le répertoire racine, et le répertoire personnel (home directory).

Les fichiers cachés et la commande cd -.

L'utilisation de less et file pour examiner le contenu et le type des fichiers.

L'utilisation des options et arguments avec les commandes, notamment le format long de ls.

Manipulation de Fichiers et Liens
Les commandes cp, mv, rm, mkdir.

Comprendre et utiliser les "wildcards" (*, ?, []).

Les liens symboliques (symlinks) et les liens physiques (hard links), ainsi que leurs différences.

Comprendre les Commandes
Les commandes type, which, help, man pour obtenir des informations.

Les différents types de commandes (exécutables, built-ins, alias).

Lire une page de manuel (man page) et identifier ses sections.

Les raccourcis clavier courants pour Bash.

Autres Concepts
La signification de LTS (Long Term Support).

# 🛠️ Technologies et Environnement
Interpréteur de commandes : Bash

Système d'exploitation : Ubuntu 22.04 LTS

Éditeurs de texte : vi, vim, emacs

# 📖 Structure du Projet et Scripts
Ce dépôt contient une série de scripts Bash, chacun résolvant un problème spécifique lié aux bases du Shell. Chaque script est conçu pour être exactement deux lignes de long et commence par le shebang #!/bin/bash.

README.md : Ce fichier.

* **[Lien vers 0-current_working_directory](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/0-current_working_directory)** : Affiche le chemin absolu du répertoire de travail actuel.

* **[Lien vers 1-listit](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/1-listit)** : Liste le contenu du répertoire courant.

* **[Lien vers 2-bring_me_home](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/2-bring_me_home)** : Change le répertoire de travail vers le répertoire personnel de l'utilisateur.

* **[Lien vers 3-listfiles](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/3-listfiles)** : Affiche le contenu du répertoire courant au format long.

* **[Lien vers 4-listmorefiles](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/4-listmorefiles)** : Affiche le contenu du répertoire courant, y compris les fichiers cachés, au format long.

* **[Lien vers 5-listfilesdigitonly](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/5-listfilesdigitonly)** : Affiche le contenu du répertoire courant au format long, avec les IDs numériques des utilisateurs et groupes, y compris les fichiers cachés.

* **[Lien vers 6-firstdirectory](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/6-firstdirectory)** : Crée un répertoire nommé my_first_directory dans /tmp/.

* **[Lien vers 7-movethatfile](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/7-movethatfile)** : Déplace le fichier betty de /tmp/ vers /tmp/my_first_directory.

* **[Lien vers 8-firstdelete](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/8-firstdelete)** : Supprime le fichier betty de /tmp/my_first_directory.

* **[Lien vers 9-firstdirdeletion](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/9-firstdirdeletion)** : Supprime le répertoire my_first_directory de /tmp/.

* **[Lien vers 10-back](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/10-back)** : Change le répertoire de travail vers le répertoire précédent.

* **[Lien vers 11-lists](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/11-lists)** : Liste tous les fichiers (y compris cachés) du répertoire courant, du répertoire parent et de /boot, au format long.

* **[Lien vers 12-file_type](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/12-file_type)** : Affiche le type du fichier nommé iamafile (situé dans /tmp/ lors de l'exécution).

* **[Lien vers 13-symbolic_link](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/13-symbolic_link)** : Crée un lien symbolique __ls__ vers /bin/ls dans le répertoire courant.

* **[Lien vers 14-copy_html](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/14-copy_html)** : Copie les fichiers HTML du répertoire courant vers le répertoire parent, mais uniquement s'ils sont plus récents ou inexistants.

* **[Lien vers 15-lets_move](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/15-lets_move)** : Déplace tous les fichiers commençant par une majuscule vers le répertoire /tmp/u.

* **[Lien vers 16-clean_emacs](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/16-clean_emacs)** : Supprime tous les fichiers du répertoire courant se terminant par le caractère ~.

* **[Lien vers 17-tree](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/basics/17-tree)** : Crée une structure de répertoires imbriqués : welcome/, welcome/to/ et welcome/to/school.



# 💡 Contraintes et Bonnes Pratiques
Ce projet adhère à des règles strictes pour garantir la qualité et la conformité des scripts :

Shebang Obligatoire : La première ligne de chaque script doit être #!/bin/bash.

Deux Lignes Maximum : Chaque script doit être composé d'exactement deux lignes ($ wc -l file doit afficher 2).

Fin de Fichier : Tous les fichiers doivent se terminer par une nouvelle ligne (pourquoi ? Pour la conformité POSIX et éviter les problèmes lors de la concaténation ou du traitement par d'autres outils).

Exécutable : Tous les scripts doivent être rendus exécutables (chmod u+x NOM_DU_SCRIPT).

Restrictions de Commandes : Interdiction d'utiliser les backticks (`), &&, || ou ;.

Style Betty : Le code (si applicable) doit respecter le style Betty.

# 👨‍💻 Comment Exécuter les Scripts : Un Aperçu Pratique
Pour exécuter ces scripts, assure-toi d'être sur un système Ubuntu 22.04 LTS.

Rends le script exécutable (une seule fois par script) :

```bash

chmod u+x NOM_DU_SCRIPT
Par exemple : chmod u+x 0-current_working_directory

Exécute le script :
```
```bash

./NOM_DU_SCRIPT
Exemple dans un Terminal :
```
```bash

# Simule l'environnement initial
julien@ubuntu:/tmp$ pwd
/tmp

# Rendre le script 0-current_working_directory exécutable
julien@ubuntu:/tmp$ chmod u+x 0-current_working_directory

# Exécuter le script
julien@ubuntu:/tmp$ ./0-current_working_directory
/tmp
# Le script a bien affiché le répertoire de travail actuel.

# Créons un fichier pour l'exemple 12-file_type
julien@ubuntu:/tmp$ touch iamafile

# Rendre le script 12-file_type exécutable
julien@ubuntu:/tmp$ chmod u+x 12-file_type

# Exécuter le script 12-file_type
julien@ubuntu:/tmp$ ./12-file_type
/tmp/iamafile: empty
# Le script a bien affiché le type du fichier, qui est "empty" car nous venons de le créer.

julien@ubuntu:/tmp$
```
# ✍️ Auteur
Mathieu GODALIER - Élève en programmation


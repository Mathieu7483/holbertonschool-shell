# ⚙️ Projet : Redirection d'E/S et Filtres Shell - La Ligne de Commande en Action
Bienvenue dans ce projet fondamental sur la redirection d'entrée/sortie (E/S) et l'utilisation des filtres dans le Shell Bash ! Ce module est essentiel pour automatiser des tâches, transformer des données et créer des scripts puissants. J'ai exploré ici comment diriger le flux d'informations entre les commandes et les fichiers, et comment manipuler du texte avec des outils courants.

Comprendre ces concepts permet de débloquer le véritable potentiel de la ligne de commande, en transformant des tâches complexes en opérations simples et chaînées.

# 🎯 Objectifs d'Apprentissage
À la fin de ce projet, je suis capable d'expliquer clairement à quiconque, sans l'aide de Google :

Redirection d'E/S
Le rôle des commandes head, tail, find, wc, sort, uniq, grep, tr.

Comment rediriger la sortie standard vers un fichier (>).

Comment obtenir l'entrée standard à partir d'un fichier au lieu du clavier (<).

Comment envoyer la sortie d'un programme à l'entrée d'un autre programme via un pipe (|).

Comment combiner des commandes et des filtres avec des redirections.

Caractères Spéciaux
Ce que sont les caractères spéciaux dans le Shell.

La signification et l'utilisation des espaces blancs, guillemets simples ('), guillemets doubles ("), backslash (\), commentaires (#), pipe (|), séparateur de commandes (non autorisé dans ce projet), tilde (~).

Autres Commandes et Fichiers
Comment afficher une ligne de texte (echo).

Comment concaténer des fichiers et imprimer sur la sortie standard (cat).

Comment inverser une chaîne de caractères (rev).

Comment supprimer des sections de chaque ligne de fichiers (cut).

La structure et le format des fichiers /etc/passwd et /etc/shadow.

# 🛠️ Technologies et Environnement
Interpréteur de commandes : Bash

Système d'exploitation : Ubuntu 20.04 LTS

Éditeurs de texte : vi, vim, emacs

# 📖 Structure du Projet et Scripts
Ce dépôt contient une série de scripts Bash, chacun démontrant des concepts de redirection d'E/S et d'utilisation de filtres. Chaque script respecte les contraintes strictes du projet (deux lignes, shebang, pas de sed/awk, etc.).

README.md : Ce fichier.

* **[Lien vers 0-hello_world](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/0-hello_world)** : Imprime "Hello, World" suivi d'un retour à la ligne.

* **[Lien vers 1-confused_smiley](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/1-confused_smiley)** : Affiche un smiley confus "(Ôo)'.

* **[Lien vers 2-hellofile](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/2-hellofile)** : Affiche le contenu du fichier /etc/passwd.

* **[Lien vers 3-twofiles](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/3-twofiles)** : Affiche le contenu de /etc/passwd et /etc/hosts.

* **[Lien vers 4-lastlines](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/4-lastlines)** : Affiche les 10 dernières lignes de /etc/passwd.

* **[Lien vers 5-firstlines](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/5-firstlines)** : Affiche les 10 premières lignes de /etc/passwd.

* **[Lien vers 6-third_line](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/6-third_line)** : Affiche la troisième ligne du fichier iacta.

* **[Lien vers 7-file](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/7-file)** : Crée un fichier nommé exactement *\'"Best School"\'*\?\*\*\*\*\*: ) contenant le texte "Best School".

* **[Lien vers 8-cwd_state](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/8-cwd_state)** : Écrit le résultat de ls -la dans le fichier ls_cwd_content, écrasant le fichier s'il existe ou le créant sinon.

* **[Lien vers 9-duplicate_last_line](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/9-duplicate_last_line)** : Duplique la dernière ligne du fichier iacta.

* **[Lien vers 10-no_more_js](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/10-no_more_js)** : Supprime tous les fichiers réguliers (pas les répertoires) avec l'extension .js dans le répertoire courant et ses sous-dossiers.

* **[Lien vers 11-directories](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/11-directories)** : Compte le nombre de répertoires et sous-répertoires (y compris cachés) dans le répertoire courant, excluant . et ...

* **[Lien vers 12-newest_files](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/12-newest_files)** : Affiche les 10 fichiers les plus récents du répertoire courant, un par ligne, triés du plus récent au plus ancien.

* **[Lien vers 13-unique](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/13-unique)** : Prend une liste de mots en entrée et n'imprime que les mots qui apparaissent exactement une fois, triés.

* **[Lien vers 14-findthatword](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/14-findthatword)** : Affiche les lignes du fichier /etc/passwd qui contiennent le motif "root".

* **[Lien vers 15-countthatword](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/15-countthatword)** : Affiche le nombre de lignes du fichier /etc/passwd qui contiennent le motif "bin".

* **[Lien vers 16-whatsnext](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/16-whatsnext)** : Affiche les lignes du fichier /etc/passwd contenant le motif "root" et les 3 lignes qui les suivent.

* **[Lien vers 17-hidethisword](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/17-hidethisword)** : Affiche toutes les lignes du fichier /etc/passwd qui ne contiennent pas le motif "bin".

* **[Lien vers 18-letteronly](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/18-letteronly)** : Affiche toutes les lignes du fichier /etc/ssh/sshd_config qui commencent par une lettre (majuscules incluses).

* **[Lien vers 19-AZ](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/19-AZ)** : Remplace tous les caractères 'A' et 'c' de l'entrée par 'Z' et 'e' respectivement.

* **[Lien vers 20-hiago](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/20-hiago)** : Supprime toutes les lettres 'c' et 'C' de l'entrée.

* **[Lien vers 21-reverse](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/21-reverse)** : Inverse son entrée.

* **[Lien vers 22-users_and_homes](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/22-users_and_homes)** : Affiche tous les utilisateurs et leurs répertoires personnels, triés par nom d'utilisateur, basé sur /etc/passwd.

* **[Lien vers 23-empty_casks](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/23-empty_casks)** : Trouve tous les fichiers et répertoires vides dans le répertoire courant et ses sous-répertoires, affichant seulement leurs noms (y compris cachés), un par ligne.

* **[Lien vers 24-gifs](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/24-gifs)** : Liste tous les fichiers .gif (y compris cachés) du répertoire courant et de ses sous-répertoires, sans extension et triés par valeur d'octet (insensible à la casse).

* **[Lien vers 25-acrostic](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/25-acrostic)** : (Description de la tâche à compléter, si nécessaire pour le script).

* **[Lien vers 26-The_biggest_fan](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/io_redirections_and_filters/26-the_biggest_fan)** Script qui

💡 Contraintes et Bonnes Pratiques
Ce projet adhère à des règles strictes pour garantir la qualité et la conformité des scripts :

Shebang Obligatoire : La première ligne de chaque script doit être #!/bin/bash.

Deux Lignes Maximum : Chaque script doit être composé d'exactement deux lignes ($ wc -l file doit afficher 2).

Fin de Fichier : Tous les fichiers doivent se terminer par une nouvelle ligne.

Exécutable : Tous les scripts doivent être rendus exécutables (chmod u+x NOM_DU_SCRIPT).

Restrictions de Commandes : Interdiction d'utiliser les backticks (`), &&, || ou ;.

Filtres Interdits : Tu n'es pas autorisé à utiliser sed ou awk pour ce projet.

👨‍💻 Comment Exécuter les Scripts : Un Aperçu Pratique
Pour exécuter ces scripts, assure-toi d'être sur un système Ubuntu 20.04 LTS.

Rends le script exécutable (une seule fois par script) :

```bash

chmod u+x NOM_DU_SCRIPT
Exécute le script :
```
```bash

./NOM_DU_SCRIPT
Certains scripts nécessiteront une entrée (via pipe ou redirection de fichier) ou des fichiers spécifiques pour fonctionner comme prévu.

Exemple dans un Terminal :
```
```bash

# Exécuter le premier script : 0-hello_world
julien@ubuntu:/tmp/h$ chmod u+x 0-hello_world
julien@ubuntu:/tmp/h$ ./0-hello_world
Hello, World
# Le script affiche bien "Hello, World"

# Créons un fichier pour l'exemple 6-third_line
julien@ubuntu:/tmp/h$ cat > iacta << EOF
Ligne 1
Ligne 2
Ceci est la troisième ligne.
Ligne 4
EOF

# Rendre le script 6-third_line exécutable
julien@ubuntu:/tmp/h$ chmod u+x 6-third_line

# Exécuter le script 6-third_line
julien@ubuntu:/tmp/h$ ./6-third_line
Ceci est la troisième ligne.
# Le script a extrait correctement la troisième ligne.

# Exemple de pipe avec 13-unique
julien@ubuntu:/tmp/0x02$ cat > list << EOF
C#
C
Javascript
Perl
PHP
PHP
ASP
R
Go
C#
C++
R
Perl
Javascript
Javascript
Javascript
Javascript
Javascript
Java
Java
Python
Javascript
Javascript
Javascript
ASP
EOF

julien@ubuntu:/tmp/0x02$ chmod u+x 13-unique
julien@ubuntu:/tmp/0x02$ cat list | ./13-unique
C
C++
Go
# Les mots uniques et triés sont affichés.

julien@ubuntu:/tmp/h$
```

# ✍️ Auteur
Mathieu - Élève en programmation

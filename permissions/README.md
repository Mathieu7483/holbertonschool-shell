<img src= "https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/img/holberton%20modif.png">

# 🔐 Projet : Permissions - Maîtrise des Droits d'Accès Linux
Ce projet explore un pilier central de tout système d'exploitation basé sur Unix/Linux : les permissions de fichiers et de répertoires. Comprendre comment les permissions fonctionnent et comment les gérer est indispensable pour la sécurité, l'administration système et même le développement.

J'ai appris à manipuler les droits d'accès des fichiers, à changer les propriétaires et les groupes, et à comprendre l'impact de l'utilisateur courant et du superutilisateur (root). Ce projet m'a permis de solidifier mes connaissances sur les commandes essentielles pour interagir avec le système de fichiers de manière sécurisée et efficace.

# 🎯 Objectifs d'Apprentissage
À la fin de ce projet, je suis capable d'expliquer clairement à quiconque, sans l'aide de Google :

Permissions de Fichiers
Le rôle des commandes chmod, sudo, su, chown, chgrp.

Les permissions de fichiers Linux (lecture, écriture, exécution).

Comment représenter chaque ensemble de permissions (propriétaire, groupe, autres) en tant que chiffre unique (notation octale).

Comment modifier les permissions, le propriétaire et le groupe d'un fichier.

Pourquoi un utilisateur normal ne peut pas utiliser chown sur un fichier qui ne lui appartient pas.

Comment exécuter une commande avec les privilèges root.

Comment changer d'utilisateur ID ou devenir superutilisateur.

Autres Pages de Manuel
Comment créer un utilisateur (adduser / useradd).

Comment créer un groupe (addgroup / groupadd).

Comment afficher les IDs utilisateur et groupe réels et effectifs (id).

Comment afficher les groupes auxquels un utilisateur appartient (groups).

Comment afficher l'UID effectif (id -un).

🛠️ Technologies et Environnement
Interpréteur de commandes : Bash

Système d'exploitation : Ubuntu 22.04 LTS

Éditeurs de texte : vi, vim, emacs

# 📖 Structure du Projet et Scripts
Ce dépôt contient une série de scripts Bash, chacun démontrant un aspect spécifique de la gestion des permissions de fichiers et des utilisateurs.

README.md : Ce fichier.

* **[Lien vers 0-iam_betty](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/0-iam_betty)** : Script qui change l'utilisateur courant vers betty. (8 caractères + nouvelle ligne).

* **[Lien vers 1-who_am_i](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/1-who_am_i)** : Affiche le nom d'utilisateur effectif de l'utilisateur actuel.

* **[Lien vers 2-groups](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/2-groups)** : Affiche tous les groupes dont fait partie l'utilisateur actuel.

* **[Lien vers 3-new_owner](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/3-new_owner)** : Change le propriétaire du fichier hello à l'utilisateur betty. (Nécessite sudo et doit être dans /tmp en sandbox).

* **[Lien vers 4-empty](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/4-empty)** : Crée un fichier vide nommé hello.

* **[Lien vers 5-execute](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/5-execute)** : Ajoute la permission d'exécution au propriétaire du fichier hello.

* **[Lien vers 6-multiple_permissions](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/6-multiple_permissions)** : Ajoute la permission d'exécution au propriétaire et au groupe, et la permission de lecture aux autres utilisateurs, pour le fichier hello.

* **[Lien vers 7-everybody](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/7-everybody)** : Ajoute la permission d'exécution au propriétaire, au groupe et aux autres utilisateurs pour le fichier hello (sans utiliser de virgules).

* **[Lien vers 8-James_Bond](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/8-James_Bond)** : Définit les permissions du fichier hello à : propriétaire (aucune), groupe (aucune), autres (toutes). (Sans utiliser de virgules).

* **[Lien vers 9-John_Doe](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/9-John_Doe)** : Définit le mode du fichier hello à -rwxr-x-wx. (Sans utiliser de virgules).

* **[Lien vers 10-mirror_permissions](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/10-mirror_permissions)** : Définit le mode du fichier hello identique au mode du fichier olleh.

* **[Lien vers 11-directories_permissions](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/11-directories_permissions)** : Ajoute la permission d'exécution à tous les sous-répertoires du répertoire courant pour le propriétaire, le groupe et les autres utilisateurs (les fichiers réguliers ne sont pas modifiés).

* **[Lien vers 12-directory_permissions](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/12-directory_permissions)** : Crée un répertoire nommé my_dir avec les permissions 751 dans le répertoire de travail.

* **[Lien vers 13-change_group](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/13-change_group)** : Change le groupe propriétaire du fichier hello à school. (Nécessite sudo et doit être dans /tmp en sandbox).

* **[Lien vers 14-change_owner_and_group](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/14-change_owner_and_group)** : Change le propriétaire à vincent et le groupe propriétaire à staff pour tous les fichiers et répertoires du répertoire de travail. (Nécessite sudo et doit être dans /tmp en sandbox).

* **[Lien vers 15-symbolic_link_permissions](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/15-symbolic_link_permissions)** : Change le propriétaire et le groupe de _hello (un lien symbolique) à vincent et staff respectivement. (Nécessite sudo et doit être dans /tmp en sandbox).

* **[Lien vers 16-if_only](https://github.com/Mathieu7483/holbertonschool-shell/blob/main/permissions/16-if_only)** : Change le propriétaire du fichier hello à vincent seulement si son propriétaire actuel est guillaume. (Nécessite sudo et doit être dans /tmp en sandbox).



# 💡 Contraintes et Bonnes Pratiques
Ce projet adhère à des règles strictes pour garantir la qualité et la conformité des scripts :

Shebang Obligatoire : La première ligne de chaque script doit être #!/bin/bash.

Deux Lignes Maximum : Chaque script doit être composé d'exactement deux lignes ($ wc -l file doit afficher 2).

Fin de Fichier : Tous les fichiers doivent se terminer par une nouvelle ligne.

Exécutable : Tous les scripts doivent être rendus exécutables (chmod u+x NOM_DU_SCRIPT).

Restrictions de Commandes : Interdiction d'utiliser les backticks (`), &&, || ou ;.

Attention Sandbox : Les tâches 3, 13, 14, 15, 16 doivent être réalisées à l'intérieur de l'environnement sandbox pour être corrigées correctement. Elles nécessitent des privilèges élevés (sudo) et des modifications du système de fichiers ou des utilisateurs qui ne sont pas toujours souhaitables en dehors d'un environnement contrôlé.

# 👨‍💻 Comment Exécuter les Scripts : Un Aperçu Pratique
Pour exécuter ces scripts, assure-toi d'être sur un système Ubuntu 22.04 LTS ou un environnement compatible.

Rends le script exécutable (une seule fois par script) :

```bash

chmod u+x NOM_DU_SCRIPT
Exécute le script :
```
```bash

./NOM_DU_SCRIPT
Certains scripts, notamment ceux impliquant la modification de propriétaires ou de groupes (comme chown ou chgrp), nécessiteront des privilèges root et devront être exécutés avec sudo (par exemple : sudo ./3-new_owner).

Exemple dans un Terminal :
```
```bash

# Pour 0-iam_betty (simulation de l'exécution en tant que betty)
julien@ubuntu:/tmp/h$ tail -1 0-iam_betty | wc -c
9
julien@ubuntu:/tmp/h$ # Le script 0-iam_betty contient "su - betty"

# Pour 1-who_am_i
julien@ubuntu:/tmp/h$ chmod u+x 1-who_am_i
julien@ubuntu:/tmp/h$ ./1-who_am_i
julien
# Le script affiche l'utilisateur courant.

# Pour 5-execute (ajout de permission d'exécution au propriétaire)
julien@ubuntu:/tmp/h$ touch hello # Créons un fichier pour l'exemple
julien@ubuntu:/tmp/h$ ls -l hello
-rw-rw-r-- 1 julien julien 0 Sep 20 14:25 hello
julien@ubuntu:/tmp/h$ chmod u+x 5-execute
julien@ubuntu:/tmp/h$ ./5-execute
julien@ubuntu:/tmp/h$ ls -l hello
-rwxrw-r-- 1 julien julien 0 Sep 20 14:25 hello
# La permission d'exécution a été ajoutée pour l'utilisateur.

# Pour 12-directory_permissions (création de répertoire avec permissions spécifiques)
julien@ubuntu:/tmp/h$ chmod u+x 12-directory_permissions
julien@ubuntu:/tmp/h$ ./12-directory_permissions
julien@ubuntu:/tmp/h$ ls -ld my_dir
drwxr-x--x 2 julien julien 4096 Sep 20 14:59 my_dir
# Le répertoire a été créé avec les permissions 751.

julien@ubuntu:/tmp/h$
```

# ✍️ Auteur
Mathieu GODALIER - Élève en programmation à la Holberton School

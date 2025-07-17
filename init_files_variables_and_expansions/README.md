# 🐚 Projet : Fichiers d'Initialisation, Variables et Expansions du Shell
Ce projet est une plongée au cœur du Shell Bash, explorant les mécanismes qui régissent son comportement, de l'initialisation à la manipulation des données. J'ai appris comment le Shell se configure au démarrage, comment stocker et utiliser des informations avec des variables, et comment les expansions transforment les commandes avant leur exécution.

Cette exploration m'a donné une compréhension plus approfondie de l'environnement Bash, essentielle pour écrire des scripts plus efficaces et diagnostiquer les problèmes.

# 🎯 Objectifs d'Apprentissage
À la fin de ce projet, je suis capable d'expliquer clairement à quiconque, sans l'aide de Google :

Général
Ce qui se passe lorsque vous tapez $ ls -l *.txt et appuyez sur Entrée.

Fichiers d'Initialisation du Shell
Le rôle du fichier /etc/profile et du répertoire /etc/profile.d.

Le rôle du fichier ~/.bashrc.

Variables
La différence entre une variable locale et une variable globale (environnement).

Ce qu'est une variable réservée.

Comment créer, mettre à jour et supprimer des variables Shell.

Les rôles des variables réservées suivantes : HOME, PATH, PS1.

Ce que sont les paramètres spéciaux.

Le rôle du paramètre spécial $?.

Expansions
Ce qu'est une expansion et comment les utiliser.

La différence entre les guillemets simples (') et les guillemets doubles (") et comment les utiliser correctement.

Comment effectuer une substitution de commande avec $() et les backticks (`).

Arithmétique du Shell
Comment effectuer des opérations arithmétiques avec le Shell.

La commande alias
Comment créer un alias.

Comment lister les alias.

Comment désactiver temporairement un alias.

Autres Pages d'Aide
Comment exécuter des commandes à partir d'un fichier dans le Shell courant (. ou source).

🛠️ Technologies et Environnement
Interpréteur de commandes : Bash

Système d'exploitation : Ubuntu 20.04 LTS

Éditeurs de texte : vi, vim, emacs

# 📖 Structure du Projet et Scripts
Ce dépôt contient une série de scripts Bash, chacun illustrant un concept clé lié aux fichiers d'initialisation, aux variables et aux expansions du Shell.

README.md : Ce fichier.

* **[Lien vers 0-alias]()** : Crée un alias nommé ls dont la valeur est rm -f *.

* **[Lien vers 1-hello_you]()** : Affiche hello user, où user est le nom d'utilisateur Linux actuel.

* **[Lien vers 2-path]()** : Ajoute /action à la variable d'environnement PATH, en s'assurant qu'il est le dernier répertoire recherché.

* **[Lien vers 3-paths]()** : Compte le nombre de répertoires dans la variable PATH.

* **[Lien vers 4-global_variables]()** : Liste toutes les variables d'environnement (globales).

* **[Lien vers 5-local_variables]()** : Liste toutes les variables locales, variables d'environnement et fonctions.

* **[Lien vers 6-create_local_variable]()** : Crée une nouvelle variable locale nommée BEST avec la valeur School.

* **[Lien vers 7-create_global_variable]()** : Crée une nouvelle variable globale nommée BEST avec la valeur School.

* **[Lien vers 8-true_knowledge]()** : Affiche le résultat de l'addition de 128 avec la valeur de la variable d'environnement TRUEKNOWLEDGE.

* **[Lien vers 9-divide_and_rule]()** : Affiche le résultat de POWER divisé par DIVIDE (variables d'environnement).

* **[Lien vers 10-love_exponent_breath]()** : Affiche le résultat de BREATH à la puissance LOVE (variables d'environnement).

* **[Lien vers 11-binary_to_decimal]()** : Convertit un nombre de la base 2 (stocké dans BINARY) à la base 10.

* **[Lien vers 12-combinations]()** : Affiche toutes les combinaisons possibles de deux lettres minuscules (de 'a' à 'z'), une par ligne, par ordre alphabétique, en excluant oo.

* **[Lien vers 13-print_float]()** : Affiche un nombre (stocké dans NUM) avec deux décimales.

* **[Lien vers 14-decimal_to_hexadecimal]()** : Convertit un nombre de la base 10 (stocké dans DECIMAL) à la base 16.

* **[Lien vers 15-rot13]()** : Encode et décode du texte en utilisant l'algorithme ROT13 (ASCII).

* **[Lien vers 16-odd]()** : Affiche une ligne sur deux à partir de l'entrée, en commençant par la première ligne.

* **[Lien vers 17-water_and_stir]()** : Additionne deux nombres stockés dans les variables d'environnement WATER (base "water") et STIR (base "stir"), et affiche le résultat en base "bestchol". (Tâche avancée, nécessite une compréhension des bases personnalisées).




# 💡 Contraintes et Bonnes Pratiques
Ce projet adhère à des règles strictes pour garantir la qualité et la conformité des scripts :

Shebang Obligatoire : La première ligne de chaque script doit être #!/bin/bash.

Deux Lignes Maximum : Chaque script doit être composé d'exactement deux lignes ($ wc -l file doit afficher 2).

Fin de Fichier : Tous les fichiers doivent se terminer par une nouvelle ligne.

Exécutable : Tous les scripts doivent être rendus exécutables (chmod u+x NOM_DU_SCRIPT).

Restrictions de Commandes : Interdiction d'utiliser &&, ||, ;, bc, sed, awk.

Environnement Ubuntu 20.04 LTS : Les scripts seront testés sur cette version spécifique d'Ubuntu.

# 👨‍💻 Comment Exécuter les Scripts : Un Guide Pratique
Pour exécuter ces scripts, suivez ces étapes simples :

Rendez le script exécutable (une seule fois par script) :

Bash

chmod u+x NOM_DU_SCRIPT
Exécutez le script :

Certains scripts, comme ceux modifiant des variables d'environnement (PATH), doivent être sourced (exécutés dans le Shell courant) pour que leurs effets soient persistants dans votre session actuelle.

Bash

. ./NOM_DU_SCRIPT  # ou source ./NOM_DU_SCRIPT
Les autres scripts peuvent être exécutés directement :

'''Bash

./NOM_DU_SCRIPT
Exemple dans un Terminal :
Bash

# Pour 1-hello_you
julien@ubuntu:/tmp/0x03$ chmod u+x 1-hello_you
julien@ubuntu:/tmp/0x03$ ./1-hello_you
hello julien

# Pour 2-path (modifie le PATH dans la session courante)
julien@ubuntu:/tmp/0x03$ echo $PATH
/home/julien/bin:...:/snap/bin
julien@ubuntu:/tmp/0x03$ chmod u+x 2-path
julien@ubuntu:/tmp/0x03$ source ./2-path
julien@ubuntu:/tmp/0x03$ echo $PATH
/home/julien/bin:...:/snap/bin:/action

# Pour 8-true_knowledge (utilisation d'une variable d'environnement)
julien@production-503e7013:~$ export TRUEKNOWLEDGE=1209
julien@production-503e7013:~$ chmod u+x 8-true_knowledge
julien@production-503e7013:~$ ./8-true_knowledge | cat -e
1337$
# ✍️ Auteur
Mathieu GODALIER - Élève en programmation à la Holberton School

📁 Copier un projet local vers une machine virtuelle Ubuntu
Pour transférer un répertoire de votre machine hôte (Windows) vers une machine virtuelle (Ubuntu), vous pouvez utiliser la commande scp.

🛠️ Pré-requis :
Avoir PowerShell ouvert en tant qu’administrateur.

S’assurer que la machine virtuelle est accessible via le réseau.

L’utilisateur distant (ex: oumayma) doit avoir les droits d’écriture dans le dossier cible (/var/www/html).

[[         scp -r "C:\wamp64\www\Nouveau dossier" oumayma@192.168.1.25:/var/www/html  ]]
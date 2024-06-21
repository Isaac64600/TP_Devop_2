# **TP 2 Docker**
## a. Une option de npm vous permet de n’installer que ce qui est nécessaire. Quelle est cette option ? Quelle bonne pratique Docker permet t-elle de respecter ?
L'option de npm est --only=production. Cette option permet de minimiser la taille de l'image en ne copiant que les fichiers nécessaires pour exécuter l'application en production, sans inclure les dépendances de développement.

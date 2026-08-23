
# Comment importer la base

Pour s'y faire, de cliquer sur le petit crayon dans le repositorie sur github. Aussi il y a un outil qui est spécifiquement créer pour réaliser des readme et cela s'appelle readme.so
Et quant on fait un projet open source ou un projet sur github on ajoute une FAQ qui vient s'ajouter au reste du projet et va s'afficher d'une manière qui correspond aux conventions utilisées de github. Une fois terminée cliquer sur "raw" et copier et coller sur edit file sur github puis cliquer sur "commit changes" et consulter le ripositorie. 

## Quels identifiants utiliser

Pour s'y faire, utilisez le nom d'utilisateur et le mot de passe de votre serveur de base de données (souvent MySQL ou MariaDB), ou connectez-vous d'abord à votre outil de gestion comme phpMyAdmin.

### Quelles URL tester.

Avant de lancer une migration lourde ou d'utiliser l'outil GitHub Importer, testez la validité et l'accès de l'URL distante directement depuis votre terminal avec la commande git ls-remote :

bash

git ls-remote https://gitlab.com

Si la commande retourne la liste des branches et des références (les identifiants HEAD), l'URL est valide et accessible.

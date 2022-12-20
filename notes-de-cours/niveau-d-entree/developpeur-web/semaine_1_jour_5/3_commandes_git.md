## Utilisation des commandes de base de Git pour suivre les modifications et collaborer sur des projets

Git est un outil en ligne de commande qui vous permet de suivre les modifications de votre code et de collaborer avec d'autres personnes sur des projets. Voici quelques commandes de base de Git que vous devriez connaître :

- git clone : Cette commande est utilisée pour cloner (copier) un dépôt depuis un emplacement distant (tel que GitHub) vers votre machine locale. Par exemple : `git clone https://github.com/username/repository.git`

- git add : Cette commande est utilisée pour mettre en scène (préparer) les fichiers pour la livraison. Lorsque vous ajoutez un fichier à la zone de mise en scène, vous dites à Git que vous voulez l'inclure dans le prochain commit. Vous pouvez mettre en scène des fichiers individuels ou tous les fichiers modifiés en utilisant `git add <filename>` ou `git add .`, respectivement.

- git commit : Cette commande est utilisée pour commiter (sauvegarder) vos modifications mises en scène dans le dépôt local. Vous devriez toujours inclure un message de commit pour décrire les changements que vous avez faits. Par exemple : `git commit -m "Added new feature"`.

- git push : Cette commande est utilisée pour pousser (uploader) vos commits locaux vers un dépôt distant (tel que GitHub). Par exemple : `git push origin master`.

- git pull : Cette commande est utilisée pour tirer (télécharger) les dernières modifications d'un dépôt distant vers votre machine locale. Par exemple : `git pull origin master`.

Ce ne sont là que quelques commandes de base de Git que vous pouvez utiliser pour suivre les modifications et collaborer sur des projets. Il y a beaucoup plus de commandes et de fonctionnalités Git que vous pouvez apprendre au fur et à mesure que vous vous familiarisez avec l'outil.
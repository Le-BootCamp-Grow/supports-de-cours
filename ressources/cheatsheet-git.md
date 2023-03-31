# Git Cheat sheet
## Git CSS/CSS3

> This cheat sheet is made by Growcampus.
> For entry-level to junior developers.

1.  **Les bases de Git** :

-   `git init` : initialise un nouveau dépôt Git dans le répertoire courant.
-   `git clone [url]` : crée une copie locale d'un dépôt Git distant.
-   `git status` : affiche l'état actuel du dépôt.
-   `git add [file]` : ajoute un fichier à la zone de stockage.
-   `git commit -m "[message]"` : crée un nouveau commit avec un message décrivant les changements effectués.
-   `git push` : envoie les modifications locales au dépôt distant.
-   `git pull` : récupère et fusionne les modifications du dépôt distant vers le dépôt local.
-   `git log` : affiche l'historique des livraisons du dépôt.

2.  **Branchement** :

-   `git branch` : affiche la liste des branches locales.
-   `git branch [nom de la branche]` : crée une nouvelle branche.
-   `git checkout [nom de la branche]` : bascule vers une autre branche.
-   `git merge [nom de la branche]` : fusionne une branche dans la branche courante.
-   `git push -u [remote] [nom de la branche]` : pousse une branche vers le dépôt distant.
-   `git pull [remote] [nom de la branche]` : récupère et fusionne les modifications d'une branche distante vers la branche locale.

3.  **Annulation des modifications** :

-   `git reset [file]` : supprime un fichier de la zone de transit.
-   `git checkout [file]` : annule les modifications apportées à un fichier.
-   `git revert [commit]` : crée un nouveau commit qui annule les modifications effectuées dans un commit précédent.
-   `git reset --hard [commit]` : réinitialise le référentiel à un commit spécifique, en supprimant toutes les modifications effectuées après ce commit.

4.  **Dépôts distants** :

-   `git remote` : affiche une liste des dépôts distants.
-   `git remote add [name] [url]` : ajoute un nouveau dépôt distant.
-   `git remote remove [name]` : supprime un dépôt distant.
-   `git fetch` : télécharge les modifications du dépôt distant sans les fusionner.
-   `git remote -v` : affiche l'URL de chaque dépôt distant.

5.  **Collaboration** :

-   `git branch -a` : affiche une liste des branches locales et distantes.
-   `git merge [remote]/[branch]` : fusionne une branche distante dans la branche courante.
-   `git pull --rebase` : récupère et fusionne les modifications du référentiel distant, en rebasant la branche courante sur les modifications.
-   `git push [remote] [branch]` : envoie les modifications locales au dépôt distant.
-   `git push [remote] :[branch]` : supprime une branche distante.
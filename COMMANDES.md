# COMMANDES.md - Livrable TP01 Git/GitHub

## Partie 1 & 2 : Configuration et Clonage
- `git --version` : Affiche la version de Git installée.
- `ssh-keygen -t ed25519 -C "email"` : Génère une paire de clés SSH.
- `cat ~/.ssh/id_ed25519.pub` : Affiche la clé publique SSH.
- `git config --global user.name "Nom"` : Configure le nom d'utilisateur global.
- `git config --global user.email "email"` : Configure l'adresse e-mail globale.
- `git config --global init.defaultBranch main` : Définit 'main' comme nom de branche par défaut.
- `ssh -T git@github.com` : Teste la connexion SSH avec GitHub.
- `git clone <URL>` : Clone un dépôt distant sur la machine locale.
- `git remote -v` : Affiche les URL des dépôts distants associés.

## Partie 3 : Concepts de base
- `git status` : Affiche l'état des fichiers (untracked, modified, staged).
- `git add <fichier>` : Ajoute un fichier à la zone de transit (staging area).
- `git commit -m "message"` : Enregistre les modifications de l'index dans l'historique local.
- `git push origin main` : Envoie les commits locaux vers la branche 'main' du dépôt distant.
- `git diff` : Affiche les modifications non encore indexées.
- `git log` : Affiche l'historique complet des commits.
- `git log --oneline --graph --all` : Affiche l'historique sous forme compacte et graphique.
- `git diff HEAD~1 HEAD` : Compare les différences entre deux commits.
- `git show HEAD` : Affiche le détail et les modifications apportées par le dernier commit.

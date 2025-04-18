# How-to GIT


## Prérequis
Sur mac, installation de git via homebrew
créer une paire de clé SSH
Si en mode 2FA alors créer un token d'authentification (commandes en local en mode HTTPS)

git config --global user.name "Sam Smith"
git config --global user.email sam@example.com


## Usage avec Github

1. Créer un repository via le site web Github
2. git clone https://github.com/user/repo.git
3. git add *
4. git commit -m "Commit message"
5. git push -u origin master

Si le dépot est existant en local
git remote add origin https://github.com/ThomasRoueche/Test2.git
git push -u origin master


## Usage en local seulement

git init
git add README.md
git commit -m "tagada"
git push -u origin master


## Références
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
https://www.kernel.org/pub/software/scm/git/docs/giteveryday.html

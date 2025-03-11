# Cours de GIT

## Notions de base

- un dossier qui travaille avec GIT s'appelle un **REPOSITORY** (**repo** pour les intimes)

## Commandes globales

- `git status` : permet de voir l'état du repo
- `git log` : permet de voir l'historique de tous les commits

## Démarrer un projet

### En local

- Aller dans le dossier qu'on veut transformer en repository
- `git init` : Permet d'initialiser un repository, en créant un dossier `.git`
- Aller créer un repo sur github (ou équivalent) (ne demandez pas de readme à github. Saisissez le nom du repo et validez !)
- Suivez les commandes de "pense-teubé" qui sont renseignées sur github.

### Depuis un repo distant

- `git clone [URL]` : Permet de copier un repo distant en local. Tout est déjà configuré pour relier le repo distant et local

## Triptyque

- `git add .` : permet d'ajouter vos modifications à l'indexation
- `git commit -m "message"` : permet de sauvegarder l'état d'indexation (=snapshot)
- `git push` : permet d'envoyer les commits au repo distant

# Aide-mémoire du terminal Linux

## Se déplacer

| Commande | Ce qu'elle fait               | Exemple    |
| -------- | ----------------------------- | ---------- |
| `pwd`    | Affiche le dossier où je suis | `pwd`      |
| `cd`     | Change de dossier             | `cd ~/dev` |
| `cd ..`  | remonte au dossier parent     | `cd ..`    |
|          |                               |            |

## Fichiers et dossiers

| Commande  | Ce qu'elle fait          | Exemple         |
| --------- | ------------------------ | --------------- |
| `mkdir`   | creer un nouveau dossier | `mkdir env-dev` |
| `mkdir-p` | creer un dossier parent  | `mkdir -p /..`  |
| `touch`   | creer un fichier         | `touch grace`   |
| `mv`      | deplacer un fichier      | `mv ... ...`    |
| `cp`      | Copie un fichier         | `cp ... ...`    |
| `rm`      | supprimer un fichier     | `rm grace`      |

## Lire et chercher

| Commande | Ce qu'elle fait                | Exemple     |
| -------- | ------------------------------ | ----------- |
| `ls`     | liste les fichiers du dossiers | `ls`        |
| `ls -a`  | liste les fichiers caches      | `ls -a`     |
| `ls -R`  |                                | `ls -R`     |
| `cat`    | lire un fichier                | `cat ...`   |
| `grep`   | affiche des lignes specifique  | `grep ".."` |

## Branches

| Commande | Ce qu'elle fait | Exemple |
| --------- | ------------------------- | ....... |
|`git branch`|

## Astuce de Awa

`git log --oneline --graph` dessine l'historique avec les branches.

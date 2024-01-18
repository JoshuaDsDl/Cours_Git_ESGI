# Cours_Git_ESGI

## Guide d'utilisation pour GIT:

Git est un système de contrôle de version décentralisé qui permet de suivre les modifications apportées à un ensemble de fichiers au fil du temps. Il est largement utilisé pour la gestion de projet et le développement collaboratif.

### Principes fondamentaux de Git

1. **Dépôt (Repository):** Un dépôt Git est un espace où vos projets sont stockés. Il peut être local sur votre machine ou distant sur un serveur.

2. **Commit:** Un commit représente une version spécifique de vos fichiers. Chaque commit est accompagné d'un message qui décrit les modifications apportées.

3. **Branch (Branche):** Une branche est une ligne de développement indépendante qui permet de travailler sur des fonctionnalités ou corrections de bugs sans perturber la branche principale (généralement `main` ou `master`).

### Commandes Git courantes

- `git init`: Initialise un nouveau dépôt Git.
- `git add <fichier>`: Ajoute des modifications pour être incluses dans le prochain commit.
- `git commit -m "Message du commit"`: Crée un nouveau commit avec un message descriptif.
- `git pull`: Récupère les modifications depuis un dépôt distant.
- `git push`: Envoie les commits locaux vers un dépôt distant.



## Guide d'utilisation pour GITHUB:

GitHub est une plateforme web construite autour de Git qui facilite la collaboration, le suivi des problèmes, et le déploiement de projets.

### Principales fonctionnalités de GitHub

1. **Repository (Dépôt):** Un espace où vos projets Git peuvent être stockés, suivi et partagés avec d'autres.

2. **Pull Request (Demande de tirage):** Permet de proposer des modifications à un dépôt et de demander à d'autres de les fusionner.

3. **Issues (Problèmes):** Utilisées pour suivre les tâches, les fonctionnalités, les bugs, etc.

4. **Forks (Fourches):** Permet de copier un dépôt existant sous votre propre compte GitHub.

5. **Branches Protégées:** Permet de restreindre les modifications à certaines branches pour maintenir la qualité du code.

### Flux de travail typique avec GitHub

1. **Cloner le dépôt:** `git clone <URL>` pour copier un dépôt sur votre machine.
2. **Créer une branche:** `git branch <nom_de_branche>` et `git checkout <nom_de_branche>` pour travailler sur une nouvelle fonctionnalité.
3. **Effectuer des modifications:** Faites des modifications dans vos fichiers et utilisez `git add` et `git commit` pour les sauvegarder localement.
4. **Pousser les modifications:** `git push origin <nom_de_branche>` pour envoyer vos modifications sur GitHub.
5. **Créer une Pull Request:** Sur GitHub, proposez vos modifications en créant une Pull Request depuis votre branche vers la branche principale.
6. **Réviser et Fusionner:** Les collaborateurs peuvent examiner les modifications, poser des questions et fusionner les modifications dans la branche principale.

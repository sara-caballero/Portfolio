---
title: "GitHub pour débutants"
date: 2023-01-22T16:13:04+01:00
draft: true
hiddenFromHomePage: true
images: ["/assets/git.jpg"]
featuredImage: "/git.jpg"
---

# Git ???

Créé en 2005 par Linus Torvalds, l'homme à l'origine du système d'exploitation Linux, **GIT est un système de contrôle de version distribué.** 

Ce type de système signifie que tout le code et l'historique sont disponibles sur l'ordinateur de chaque développeur. 

**GitHub** appartient à Microsoft et facilite l'utilisation de GIT en proposant une offre gratuite avec un nombre illimité de répertoires et d'utilisateurs, jusqu'à 500 MB de stockage.

*Si vous êtes étudiants, vous pouvez bénéficier de GitHub Team gratuitement* (40$ économisés par an quand même !) et vous aurez accès à 2 Go de stockage et d’autres bénéfices.
Pour bénéficier de GitHub Student Pack, il suffit d'être étudiant, âgé de 13 ans ou plus. Pour accéder à cette offre, il faut se rendre sur [Education.github.com/pack](/Education.github.com/pack), puis cliquer sur "En bénéficier" et renseigner votre adresse e-mail scolaire et de charger un document prouvant le statut d'étudiant.

Il est également intéressant de connaître GitHub Copilot, un outil de pair programming qui suggère en temps réel du code pendant le développement d'une application, qui peut s'intégrer à VSCode., mais je ne l’ai pas encore testé.


## Utilisation de GitHub

## Introduction à Git
## Introduction à Git
## Introduction à Git

### VSCode

Je vous propose de découvrir comment utiliser Git au sein de l'éditeur Visual Studio Code.

1. Ouvrez un projet dans VSCode.
2. Pour initialiser un projet Git (git init) : faire [Ctrl] + [Shift] + [P] pour ouvrir un panneau de commande au niveau de l'éditeur et tapez **git init**. 
3. Cliquez sur l'option **"Git: Initialize Repository"**. Cette option va avoir l'équivalent d'un git init, ça va donc initialiser Git quelque part. Je vous conseille donc d'initialiser Git dans la racine de votre projet.

![](git1.png)

Suite à l'initialisation du projet, quelques couleurs auront changé dans l'éditeur. Les fichiers en vert ne sont pas traqués.

![](git2.png)

On a aussi un nouveau panneau qui s'est activé et qui permet d'accèder au contrôle de code source.

![](git3.png)

3. On y retrouve l'ensemble de fichiers qui ne sont pas pour l'instant suivis. On aura la possibilité de les annuler, de les valider (faire un commit) 

![](git4.png)

4. Depuis la même interface, vous avez aussi la possibilité de publier sur un depôt distant, donc si vous avez un depôt GitHub pour votre projet, vous pouvez le publier en cliquant sur **"Publier Branch"** et en suivant les indications.

![](git5.png)

5. Ensuite il faudra synchoniser les changements (Pusher), soit en cliquant sur "Push", soit sur l'icône en bas de l'editeur.

![](git6.png)

![](git7.png)



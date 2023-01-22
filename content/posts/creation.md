---
title: "La création de ce site Web"
date: 2023-01-14T18:53:04+01:00
draft: false
hiddenFromHomePage: true
images: ["/assets/hugo.png"]
featuredImage: "/hugo.png"

---
Je voulais créer un site Web super simple et facile à gérer. En faisant des recherches, j'ai trouvé le framework Hugo qui se vante d'être le plus rapide pour construire des sites.


## Comment générer un site rapidement avec Hugo
Tout d'abord, téléchargez Hugo en suivant les étapes sur https://gohugo.io/installation/ en fonction de votre OS.

Ensuite, choisissez le thème de votre choix sur https://themes.gohugo.io/ . J'ai personnellement choisi le thème LoveIt.


Une fois que vous avez tout ça, il vous suffit de créer un nouveau projet en utilisant la commande magique :

**hugo new site nom-du-projet**

Ensuite, vous devez vous rendre dans le répertoire de votre projet en utilisant la commande :

**cd nom-du-projet**

Puis, vous devrez ajouter le thème LoveIt à votre projet en utilisant la commande :

**git clone https://github.com/dillonzq/hugo-theme-loveit.git themes/loveit**

Maintenant, il est temps de configurer votre projet pour utiliser le thème LoveIt en ajoutant les lignes suivantes dans le fichier config.toml :

*theme = "loveit"*

Ensuite, vous pourrez créer des pages pour votre site en utilisant les commandes suivantes :

**hugo new blog/blog1.md**
**hugo new blog/blog2.md**

Et ajouter du contenu à vos pages en éditant les fichiers blog1.md et blog2.md. Utilisez la syntaxe Markdown pour ajouter du contenu, c'est comme écrire une recette de cuisine !

Il ne vous reste plus qu'à générer votre site web en utilisant la commande :

**hugo**

Et vérifier le rendu de votre site web en lançant le serveur web interne d'Hugo à l'aide de cette commande :

**hugo server -D**

Votre site web sera disponible à l'adresse http://localhost:1313. 

Vous pouvez maintenant le personnaliser à votre goût et le déployer sur un serveur web pour le rendre accessible au public ! Et voilà, vous avez créé un superbe site avec Go Hugo et le thème LoveIt ! Facile, non ?









---
layout: article
title: Pourquoi opter pour un site statique
categories: blogue
comments: true
tags: []
image:
  feature: posts/pourquoi-statique/statique-featured.jpg
  teaser: posts/pourquoi-statique/statique-teaser.jpg
  thumb:
date: 2015-07-11
---

Depuis la première fois que j’ai créé un site Web, les technologies du Web ont littéralement explosé. Aujourd’hui, nous pouvons naviguer sur Internet à partir d’un téléphone mobile. Les techniques ont donc dû évoluer aussi rapidement que les technologies. Avec l’avènement de ces technologies, on a aussi vu les possibilités se multiplier. On n’est plus obligé de travailler avec Flash pour ajouter des animations sur un site. Avec toutes ces nouvelles technologies, il faut penser à optimiser les sites pour ces nouveaux médias.

## Pourquoi choisir un site statique?

Depuis que j’ai commencé à faire des sites Web pour les autres et à être payé pour le faire, le système de gestion de contenu que j’ai le plus utilisé est WordPress. Je dois avouer que je n’ai jamais vraiment eu de réels gros problèmes avec ce système. C’est juste que pour mon site Web personnel, je n’avais pas besoin de toutes ses fonctions et ses capacités. J’ai seulement un petit site portfolio avec quelques articles, rien de très extraordinaire. C’est pourquoi j’ai choisi de me diriger vers un site statique.

J’aurais pu créer un site en HTML et mettre mon blogue sur une autre plateforme, ce qui aurait été suffisant, mais je préférais garder tout le site sous un seul toit. J’ai donc décidé de chercher la solution la plus idéale pour ma situation, et j’ai trouvé [Jekyll](http://jekyllrb.com){:target:"_blank"}. Cela faisait un moment que j’avais entendu parler de ce générateur HTML, mais je n’avais jamais osé m’y aventurer.

### Pour plus de contrôle

Avec Jekyll, il m’est plus facile de travailler sur le visuel de mon site. Il a un serveur local qui génère et compile le site pour moi et me le rend disponible par n’importe quel navigateur installé sur mon ordinateur. J’ai donc accès aux modifications que j’ai faites sur le site, aussitôt que j’ai enregistré le fichier modifié. Ce n’est qu’une fois que j’ai terminé ma modification que je publie mon travail sur GitHub.

#### Voici les commandes que j'utilise avec Jekyll

##### Pour prévisualiser mes changements

```
jekyll serve
```

##### Pour publier le contenu 

Générer le contenu HTML ```
jekyll build
```

Ajouter les fihciers modifiés au dépôt ```
git add .
```

Enregistrer les modifications dans le dépôt avec commentaire ```
git commit -m 'Commentaire'
```

Synchroniser avec le serveur de GitHub ```
git push origin master
```

### Pour choisir tout ce que je veux, pas plus.

WordPress n’est plus qu’un simple éditeur de blogue, il est devenu un système très complet. Quand j’ai un site à faire pour un client, c’est très intéressant d’utiliser WordPress pour toutes ses fonctions, mais quand c’est pour moi, il est beaucoup trop puissant. Je n’utilise que très peu d’options de WordPress pour mon site Web. J’aime devoir ajouter juste ce dont j’ai besoin et rien de plus. Je peux ainsi mieux contrôler les scripts à charger et les fonctions que je veux ajouter. Comme je n’ai seulement un portfolio et un blogue, je ne fais que créer les publications pour mon portfolio et mon blogue. J’ai un système de commentaires ajouté et un formulaire pour me joindre. Sur WordPress, j’aurais eu à charger plusieurs scripts et installer plusieurs extensions pour y arriver. Sur Jekyll, j’ajoute deux fonctions sur deux pages et voilà!

### Ce que j’utilise

J’utilise des technologies telles que [SASS](http://sass-lang.com){:target="_blank"} et [Bourbon](http://bourbon.io){:target="_blank"} pour créer ma feuille de style pour mon site. Cela me permet d’avoir des fichiers avec des sections de code qui, une fois le site compilé, sont rassemblées dans un plus grand fichier compressé et optimisé. Je peux utiliser des modules complémentaires tels que grunt pour automatiser des tâches comme la compression d’images et compagnie.

J’utilise GitHub pour héberger le site, mais aussi pour contrôler les versions de mon site. Je peux donc facilement gérer tous les changements faits dans le contenu ou dans la structure du site. J’obtiens ainsi un site en ligne en quatre commandes dans le terminal de commandes.

## Conclusion

Jekyll me permet d’avoir beaucoup plus de contrôle sur le contenu et la structure. Je peux donc développer mon site sans connexion Internet avant de le publier grâce au terminal de commandes sur GitHub. J’ai un site optimisé de façon automatique, hébergé sur un serveur performant. Il n’a pas besoin d’aucune couche de mise en cache autre que celle du navigateur pour les images. Je pense utiliser cette technologie de plus en plus souvent pour mes clients qui n’ont pas besoin d’un site complexe et de très peu de fonctions.

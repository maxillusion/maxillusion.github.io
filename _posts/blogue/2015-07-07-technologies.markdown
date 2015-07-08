---
layout: article
title: Différentes technologies que j'utilise
categories: blogue
comments: true
tags: []
image:
  feature: posts/wpstatic/wpstatic-featured.jpg
  teaser: posts/wpstatic/wpstatic-teaser.jpg
  thumb:
date: 2015-07-07
---

Depuis que je travaille dans le domaine du Web, j'ai développé des habitudes et j'ai fait des découvertes qui m'ont permis de progresser en tant que travailleur indépendant. J'ai donc acquis des connaissances sur certaines technologies, que je partagerai ici.

## Le système de gestion de contenu

Pour la plupart des projets que j'entreprends, j'utilise un système de gestion de contenu bien connu : [WordPress](http://www.wordpress.com){:target="_blank"}. Il s'agit d'un système très stable et très répandu sur le Web. Il permet de créer un site rapidement et il offre une très vaste bibliothèque d'extensions gratuites et payantes. Le point négatif est que la qualité des extensions disponibles est souvent discutable, celles-ci créant plus de problèmes que de solutions. Il faut donc être très vigilant. WordPress peut aussi exiger l'utilisation d'un système de mise en cache, parce qu'il effectue de nombreuses requêtes vers la base de données, ce qui ralentit considérablement les performances.

Sinon, j'aime bien utiliser un générateur de sites Web statiques nommé [Jekyll](http://www.jekyllrb.com){:target="_blank"}. L'avantage de ce système est qu'il utilise des modèles en HTML et la technologie [Liquid](https://docs.shopify.com/themes/liquid-documentation/basics){:target="_blank"} pour générer le contenu à la volée. Il est aussi soutenu par [Github](https://github.com){:target="_blank"}, qui offre l'hébergement gratuit au moyen du service [GitHub Pages](https://pages.github.com){:target="_blank"}. Comme le site généré est statique, il ne demande aucune utilisation de bases de données, ce qui le rend optimal du point de vue de la performance. Il faut veiller à bien minifier tous les fichiers, ce qui est toutefois relativement facile quand on se sert de scripts comme [Grunt](http://gruntjs.com){:target="_blank"}. Le défaut est qu'il faut regénérer le site lors de tous les changements que l'on fait, ce qui peut prendre de longues minutes si le site est volumineux. Actuellement, j'utilise cette technologie pour mon site, parce qu'elle me donne l'avantage d'être rapide à gérer.

## Les hébergeurs

Pour les sites Wordpress, je fais appel à différents hébergeurs. Voici une liste de mes fournisseurs favoris de cloudhosting : 

* [DigitalOcean](https://www.digitalocean.com/?refcode=58a806019d88){:target="_blank"} [^1]
* [Linode](https://www.linode.com/?r=801ba80497440f5a67417376d6d3494ba8a4e112){:target="_blank"} [^1]
* [Vultr](http://www.vultr.com/?ref=6818252){:target="_blank"} [^1]

Sinon, il existe de très bonnes options d'hébergeurs spécialisés WordPress :

* [SiteGround](https://www.siteground.com/index.htm?afcode=639db597481a4e7e94631b6c1350e41f){:target="_blank"}[^1]
* [GetFlyWheel](http://www.getflywheel.com){:target="_blank"} [^1]


### Les technologies serveurs

Lorsqu'il s'agit d'héberger les sites de mes clients, je préfère gérer le serveur moi-même pour des raisons de performance. J'utilise un système Ubuntu avec Nginx, Mariadb, HHVM, etc., ainsi qu'un script nommé [EasyEngine](https://rtcamp.com/easyengine/){:target="_blank"} qui me permet d'installer tout ce qu'il faut pour gérer les sites sur le serveur. La gestion est donc simplifiée et optimale, et je peux choisir le type de cache à utiliser selon le type de site que je développe.

## Les CDN

J'utilise un CDN sur 99 % des sites que je crée, afin de minimiser la bande passante utilisée sur le serveur et d'optimiser la performance des sites. Voici une courte liste des fournisseurs dont j'utilise les services :

* [Clouflare](http://www.cloudflare.com){:target="_blank"}
* [Incapsula](http://www.incapsula.com){:target="_blank"}
* [MaxCDN](http://www.maxcdn.com){:target="_blank"}

[^1]: J'utilise ici des liens promotionnels
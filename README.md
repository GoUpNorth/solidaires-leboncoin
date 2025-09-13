`solidaires-leboncoin`
=============

Le fork du boncoin du modèle de site internet de section de l'[Union syndicale Solidaires](https://solidaires.org/).
Le modèle d'origine est accessible [`ici`](https://hugolidaires.frama.io/site-template/) est est basé sur [Hugo](https://gohugo.io/).

Installation ⚙️
---------------

Pour installer ce site dans un environnement Linux, suivez ces étapes. Hugo s'[installe aussi avec d'autres OS](https://gohugo.io/installation/), mais ça ne sera pas abordé ici :

1. Installer [`hugo`](https://gohugo.io/installation/linux/) et [`git`](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git)
1. Récupérer les sources du modèle dans un répertoire de travail :
    - `git clone git@github.com:GoUpNorth/solidaires-leboncoin.git`
1. Installer le thème [`beautifulhugo`](https://github.com/halogenica/beautifulhugo) :
    - `git submodule init`
    - `git submodule update`
1. Faire tourner 🚀
    - `hugo server -D`

Voilà il y a maintenant un message qui vous indique l'adresse a utiliser dans un navigateur web pour visualiser votre nouveau _solisite_ ✨


Du contenu 📝
-------------

Vous pouvez passer ensuite à la personnalisation du contenu existant et créer le votre.

* Le contenu à personnaliser
    1. [`README.md`](https://framagit.org/hugolidaires/site-template/-/tree/stable/README.md)
    1. [`content/page`](https://framagit.org/hugolidaires/site-template/-/tree/stable/content/page)
    1. Et il restera à supprimer la publication en exemple: [`content/posts`](https://framagit.org/hugolidaires/site-template/-/tree/stable/content/posts)
* [Créer du contenu](https://gohugo.io/getting-started/quick-start/#add-content)
    1. générer le fichier vide: `hugo new posts/premiere-publication.md`
    1. ajouter du contenu: `${EDITOR} posts/premiere-publication.md`

Félicitation, votre site est prêt a être disponible publiquement 🎉


Remerciement 🤝
---------------

Ce projet est avant tout une _conversion en modèle_ et une documentation du travail réalisé par la section syndicale d'entreprise _[Solidaires OCTO](https://solidaires-octo.com/)_, qu'iels en soient _Solidairement remerciés_ !


[scotchlidaires]: https://solidaires.org/Police-de-caracteres-logo-Solidaires/

Un événement à ne pas manquer!
==============================

Bienvenue aux scientifiques, développeurs, étudiants, passionnés et/ou curieux, pour le premier événement Python à Sherbrooke. Vous voulez rencontrer des gens de toutes sortes et de tous horizons, vous faire un réseau de contact professionnel ou amical, vous trouver un stage, un stagiaire ou simplement passer du bon temps avec du bon monde? C’est à APIUS.py en octobre 2013 que ça se passe!

Technology stack
================

* Yeoman (using the webapp generator)
* Grunt
* Bower
* Sass/Compass
* sass-bootstrap
* JQuery
* Modernizr
* RequireJs

Instructions
============

Prérequis
---------

Il vous faut Nodejs, Ruby et le gem Compass d'installé sur votre environnement.

Serveur local
-------------

Pour voir le site en local, il faut cloner le projet, installer les dépendances et lancer le serveur avec grunt.

    git clone https://github.com/niclupien/apius-py.git
    cd apius-py
    npm install
    grunt server

Compilation et distribution
---------------------------

Le site web est synchronisé sur la branche gh-pages qui contient la distribution du site.

    grunt build
    git commit ...
    git subtree push --prefix dist origin gh-pages

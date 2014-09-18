boardgamebazaar
===============

[installer nvm](https://github.com/creationix/nvm)

Les commandes utiles :

```bash
## connaitre les versions de node et npm
$ node --version && npm --version

### installer yeoman
$ npm install --global yo

### connaitre les versions de yeoman, bower et grunt
$ yo --version && bower --version && grunt --version

### installer le generateur angular
$ npm install --global generator-angular@0.9.2

### appliquer le generateur angular a un dossier
$ yo angular

### lancer le serveur web en local
$ grunt serve

### chercher et installer un paquet avec bower
$ bower list
$ bower search angular-ui-sortable
$ bower install --save angular-ui-sortable
$ bower install --save jquery-ui

### lancer les tests unitaires
$ grunt test

### faire le build pour la production
$ grunt

### lancer le serveur web avec l'appli de production
$ grunt serve:dist
```
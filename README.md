# Symfony

## Configuration et initialisation

### Configuration de Composer

Composer est un outils permettant de gérer les dépendances en PHP. Symfony s'appuie sur Composer pour son installation et sa configuration.

Lancer les commandes suivantes afin d'installer Composer (pré-requis: installer PHP) :

```bash
$ php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
$ php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
```

Si vous êtes sur les PCs de l'université, vous ne pourrez pas faire l'étape suivante. Mais pas de souci, nous verrons après ensemble comment faire pour lancer tout de même Composer ლ(╹◡╹ლ) .
Pour ceux qui sont sur leur machine personnelle, lancer la commande suivante :

```bash
$ mv composer.phar /usr/local/bin/composer
```

### Initialisation du projet Symfony

Maintenant que Composer est installé, nous pouvons désormais installer Symfony. Pour créer un projet Symfony, lancer la commande suivante (vous pouvez changer "my-projet" en un autre nom) :

```bash
$ composer create-project symfony/website-skeleton my-project # Pour ceux qui sont sur leur machine
$ ./composer create-project symfony/website-skeleton my-project # Pour ceux qui sont sur les machines de l'université
```



# Symfony

## Configuration et initialisation

### Installation de Composer

Composer est un outils permettant de gérer les dépendances en PHP. Symfony s'appuie sur Composer pour son installation et sa configuration.

Lancer les commandes suivantes afin d'installer Composer (pré-requis: installer PHP) :

```bash
$ php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
$ php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
$ php composer-setup.php
```

Si vous êtes sur les PCs de l'université, vous ne pourrez pas faire l'étape suivante. Mais pas de souci, nous verrons après ensemble comment faire pour lancer tout de même Composer.
Pour ceux qui sont sur leur machine personnelle, lancer la commande suivante :

```bash
$ mv composer.phar /usr/local/bin/composer
```

### Initialisation du projet Symfony

Maintenant que Composer est installé, nous pouvons désormais installer Symfony. Pour créer un projet Symfony, lancer la commande suivante (vous pouvez changer "my-project" en un autre nom) :

```bash
# Pour ceux qui sont sur leur machine
$ composer create-project symfony/website-skeleton my-project

# Pour ceux qui sont sur les machines de l'université
$ ./composer create-project symfony/website-skeleton my-project
```

It works ! Le projet Symfony a bien été créé. Aller dans ce répertoire et paramétrons l'environnement de développement

```bash
$ cd my-project

# Pour ceux qui sont sur leur machine
$ composer require server --dev

# Pour ceux qui sont sur les machines l'université, vous devrez ré-installer Composer dans ce dossier, puis lancer la commande suivante :
$ ./composer require server --dev
```

Le lancement du serveur se fait via cette commande :

```bash
$ php bin/console server:run
```

A présent, vous pourrez accéder à votre application à l'URL suivante : http://127.0.0.1:8000

Nous allons passer à la [première partie](./BASIS.md) du TP.


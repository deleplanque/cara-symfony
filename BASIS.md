# Symfony

## Le fameux Hello World !

Commençons par le commencement, le "Hello World !".

Ce message sera afficher à l'URL http://127.0.0.1:8000/. Pour ce faire, vous devez créer un controlleur et une route qui permet à l'application d'appeler le bon controlleur en fonction de l'URL. Vous pouvez regarder la documentation [ici](https://symfony.com/doc/current/page_creation.html).

Afficher le message en utilisant le moteur de template Twig

## Un autre grand classique

Affichons maintenant le message "Hello {un_nom} !".

Ce message sera afficher à l'URL http://127.0.0.1/{un_nom}.

## Appel à une base de données

Le but ici est d'appeler une base de données et d'afficher les lignes d'une table sur l'URL http://127.0.0.1:8000/personne. En voici le MLD :

PERSON(__ID__, FISTNAME, LASTNAME, EMAIL, PASSWORD)

Symfony utilise Doctrine ORM pour travailler avec une base de données, vous avez toutes les informations [ici](https://symfony.com/doc/current/doctrine.html)

Vous pouvez aller sur ce [site](https://www.mockaroo.com/) pour générer des données aléatoirement.

## Est-ce vraiment la fin?

Vous avez enfin ce qu'il faut pour faire le [mini projet](./PROJECT.md).


Aller à la [Configuration et initialisation](./README.md)
Aller au [Mini projet](./PROJECT.md)

# Symfony

## Le fameux Hello World !

Commençons par le commencement, le "Hello World !".

Ce message sera afficher à l'URL http://127.0.0.1:8000/. Pour ce faire, vous devez créer un controlleur et une route qui permet à l'application d'appeler le bon controlleur en fonction de l'URL. Vous pouvez regarder la documentation [ici](https://symfony.com/doc/current/page_creation.html).
Bonus: Afficher le message en utilisant le moteur de template Twig

## Un autre grand classique

Affichons maintenant le message "Hello Jean !".

Ce message sera afficher à l'URL http://127.0.0.1/{le_nom}.

## Appel à une base de données

Le but ici est d'appeler une base de données et d'afficher les lignes d'une table sur l'URL http://127.0.0.1:8000/bd. En voici le MLD :

PERSONNE(__ID__, NAME, SURNAME, EMAIL, PASSWORD)

Vous pouvez aller sur ce [site](https://www.mockaroo.com/) pour générer des données aléatoirement.

## Est-ce vraiment la fin?

Vous avez enfin les bases pour faire le [mini projet](./PROJECT.md).


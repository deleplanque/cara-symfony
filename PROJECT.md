# Symfony

## Login

L'objectif de ce mini-projet est de créer un service d'authentification.

Les données seront traitées dans la table PERSON précédemment créée.

La page de connexion doit être disponible à l'URL : http://127.0.0.1:8000/connexion .

Si la connexion est un echec, un message doit apparaître sur cet URL. Sinon, si l'authentification est un succès, l'utilisateur doit être redirigé vers l'URL : http://127.0.0.1:8000 avec le message "Hello {lastname firstname} !"

Par ailleurs, le mot de passe devra être hashé en sha512.

A vous de jouer !

## I'am so fast

Pour les plus rapides, vous pouvez essayer d'utiliser [Translator](http://symfony.com/doc/current/translation.html) de Symfony permettant de traduire toutes chaînes de caractère. Vous pouvez aussi créer une page d'inscription afin de créer des personnes dans la base de données.


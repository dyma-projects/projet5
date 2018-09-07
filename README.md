# Projet 5 => chapitre 7, 8, 9

Dans ce projet nous allons nous intéresser a l'injection des dependances via l'utilisation d'un service ! Vous allez creer un service qui sera partager entre deux components, chose qui est fait constament dans une application Angular

Regarder bien les chapitres 7 8 et 9 si vous bloquez sur le projet

Bon courage :)

## Lancer le projet

Pour lancer l'application il faut d'abord installer les dépendances avec npm : 

`npm i`

Puis lancer le serveur de développement avec : 

`ng serve` ou `npm start`

## Objectifs
- [ ] Créer un service `UserService` dans le dossier shared/services
- [ ] Dans ce service, utilisez un attribut public ( `public users` ) qui sera un `BehaviorSubject` de type `string[]`. Ajoutez egalement une méthode `addUser()` pour pouvoir ajouter un nom d'utilisateur dans cette attribut.
- [ ] Injecter le service dans le component `AddUserComponent`.
- [ ] Utilisez la methode `AddUser()` du service `UserService` pour ajouter un user dans le BehaviorSubject `public users`
- [ ] Dans le component `UserListComponent`, injectez le service `UserService` et utilisez l'attribut `users` pour recuperer la liste des users et l'afficher dans la liste

      
## Avant de finir le projet

Pensez à pusher votre travail avant de cliquer sur 'terminer le projet'.

## Besoin d'aide ?

Demandez nous dans le chat on vous aidera :)

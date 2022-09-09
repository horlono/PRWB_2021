# Projet PRWB 2021 - Trello

## Notes de livraison itération 1

Full utlisation des manipulations => user Boris
Architecture globale du site web fonctionnelle pour une evaluation generale .
Points manquants importants :
-Structure html ( rendu visuel) sommaire 
-Patron PRG pleinement operationnel sur les formulaires mais sollicitement des Get à ameliorer
-Sollicitation des function private a preconiser
-Model.Card line 102 -> commentaire a lire svp
-Methode Validate a configurer
-Si user->fullName moins de 3 lettres : pas d'affichage du profile personnel mais affichage dans les boards d'autres user***
*** bug 1 fois sur 10 .
-Commentaires non implémenté à 100%: travail à faire sur le controller Card.


Manuel mouvement colonne et carte
*** bug 1 fois sur 10 ( il suffit de rappuyer sur la meme touche/icone pour que ca fonctionne)


## Notes de livraison itération 2

-Bug delete user quand celui-ci est créateur d'une carte.
-Sécurité globale reste encore à améliorer.
-Manque d'affichage de certains messages d'erreurs sur certaines pages par ex: user.
-Bug create board avec un nouvel user : à résoudre

## Notes de livraison itération 3

Site Web fonctionnel 
Nous avons ,autant que faire se peut, resolu les bugs des iterations precedentes => surtout le PRG et les nombreux bug dans nos fonctionalités

*Securité : laisse a désiré ( faute de temps dû aux retards)
*Leger soucis de layout du aux validates Java ( add card , add column)



## Installation

- Déplacez le dossier à la racine de votre serveur web (dossier `projects` ou `htdocs` en fonction de votre installation)
- Accédez à l'url [http://localhost/prwb_2021_a04/setup/install](http://localhost/prwb_2021_a04/setup/install)

## Utilisateurs

Tous les utilisateurs (`boverhaegen@epfc.eu`, `bepenelle@epfc.eu`, `brlacroix@epfc.eu` et `xapigeolet@epfc.eu`) ont le mot de passe `Password1,` (remarquez qu'il se termine par une virgule).

## Sauvegarde de la base de données

- Vérifiez le chemin de `mysql dump` dans le fichier de configuration
- Accédez à l'url [http://localhost/prwb_2021_a04/setup/export](http://localhost/prwb_2021_a04/setup/export) 
    - `database/prwb_2021_a04.sql` contient le schéma de la base de données
    - `database/prwb_2021_a04_dump.sql` contient le dump de la base de données
- Pour la restaurer, accédez à l'url [http://localhost/prwb_2021_a04/setup/install](http://localhost/prwb_2021_a04/setup/install)



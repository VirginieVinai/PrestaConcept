PrestaTechnicalTest
===================

Merci pour votre candidature chez Prestaconcept.

Toute l'équipe sera ravie de vous rencontrer si vous le réussissez.


## Le principe

Ce test permet d'évaluer le niveau technique des candidats 
lors de nos recrutements.

L'objectif consiste à installer une application permettant d'importer 
un fichier via une commande puis d'afficher les données dans une page web.

Ce test se passe dans un temps défini à l'avance, 
nous vous demandons de faire un code clair et efficace.

**Nous préférons une liste de fonctionnalitées réduites mais codées proprement plutôt que des choses imprécises.**


## Les étapes du test

- Installation de Symfony et suppression des fichiers inutiles
- Utilisation du bundle **AppBundle**
- Création du modèle : entitées `Doctrine` stockées dans une base `MySql`
  (vous déterminerez le mapping en lisant les fichiers d'import)
- Création d'une commande d'import de fichier, suivant votre niveau :
    - [/data/import/developers_simple.csv](/data/import/developers_simple.csv)
    - [/data/import/developers_middle.csv](/data/import/developers_middle.csv)
    - [/data/import/developers_big.csv](/data/import/developers_big.csv)
- Création d'une page web affichant la liste des développeurs en lazy loading :
    - la liste doit comporter les données suivantes :
        - nom : en majuscule
        - prénom : première lettre en majuscule suivie de minuscule
        - nombre de badges
    - en haut de la liste : afficher le nombre total de développeurs présents en base
    - la page doit être aux couleurs de Prestaconcept (prendre quelques couleurs de notre site sans aller trop loin)
    - ajouter un select permettant de trier la liste
- Création d'une action d'export des données de la liste en fichier CSV


## Ce que nous allons regarder

- votre code est clair, intuitif et lisible (phpDoc, PSR, etc...) 
- vous maîtrisez les fonctions de base de PHP
- vous savez utiliser Symfony
- vous êtes attentif aux performances de votre application
- vous maîtrisez les bases de HTML / CSS / JS / LESS
- vous savez utiliser git
  (séparation des commits, historique clair, détails dans vos merge requests, etc...)


## Livraisons de vos développements

Merci de nous envoyer une pull request **avant** la date limite.
Votre branche doit être formatée de la façon suivante : `AAAAMMJJ_nom_prenom`

Si vous réussissez à nous démontrer vos compétences 
et votre envie de rejoindre notre équipe à travers ce test, 
nous serons ravis de vous recontacter pour convenir d'une date d'entretien.

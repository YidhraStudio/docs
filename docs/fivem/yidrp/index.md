---
title: YidRP
description: YidRP, la base FiveM roleplay stable et évolutive.
---
# YidRP, la base FiveM stable et évolutive.

## C'est quoi l'idée ?


## Les standards et objectifs

* Principalement en JavaScript sur le standard ES2017 avec Node.js 16 LTS (surcouche TypeScript)
* Réaliser des ressources sécurisé et non-altérable que ce soit par un cheat ou par un logiciel externe.

!!! note "Integrité & Licence"
    :material-file-certificate-outline: Chaque ressource est signé et obfusqué, le code executé ne peux donc pas être altéré ou leak.

    :material-security-network: La verification de la licence s'effectue par un "handshake" avec notre serveur d'authentification.

### Fonctionnalitées et contennu des ressources

=== ":octicons-package-24: yidrp"

    ### Ressource principale, essentiel au fonctionnement de toute les autres ressources YidRP

    === "Gestion staff"
        * Gestion de la connexion
            * Vous pouvez mettre votre serveur en whitelist c'est à dire que les joueurs doivent avoir été validé par vous.
            * Il est aussi possible de rendre le serveur semi-whitelist à ce moment là les joueurs devront remplir certaines conditions (rôle discord, steam, discord, age du discord) pour se connecter. Il est possible de cummuler ce réglage avec le système de whitelist cité au dessus.

        * Gestion des sanctions
            * Les sanctions sont stocké en base de donnée, chaqune des sanction peux être composé de plusieurs éléments: identifiant unique, timestamp de création, durée de la sanction, type de sanction, commentaire, identifiant unique du joueur. Une fois que la sanction est expiré elle peux être archivé dans un salon Discord.

        * Gestion des permissions
            * Vous pouvez gérer les gardes en jeu.
            * Lors de la connexion le grade peux être attribué en fonction d'un rôle Discord.

        * Gestion de la météo et du temps
            * La météo est synchronisé et interactive, elle agit selon des cycles météo cohérents.
            * Vous pouvez modifié la météo via une commande.
            * Il est possible de passer la map en mode blackout.
            * L'heure est également synchronisé, il est aussi possible de la modifié avec une commande.
            * Les orages peuvent générer des incendies ou des coupures de courant.

        * Gestion des signalements
            * Les joueurs peuvent signalé un ou plusieurs joueur(s), il font une commande, vise la/les cible(s) en question, valide, puis un menu d'interaction s'ouvre ou celui-ci pourra remplir les renseignements.
            * Les signalements sont trier dans une liste par ordre d'arrivé avec la raison d'affiché. (le nombre de personne concerné peux être affiché)
            * Le staff peux téléporter tout les concernés puis les reconduires à leur position initiale.

        * Gestion des IA
            * La population d'IA est activable ou désactivable en configuration.
            * La quantité d'IA suit un ratio qui peux être défini en configuration.
            * Il est possible de désactiver le trafic sur le routes tout en laisant les piétons.
            * Vous pouvez nétoyer une zone des véhicules non joueur et IA en cas de problème.

        * Gestion des annonces
            * Vous pouvez réaliser des annonces staff accesible dans un menu pour informer vos joueurs.
            * Les annonces peuvent être défini sur une zone, en global avec ou sans durée.

        * Mode spéctateur

    === "Métiers & Farm"
        * Générateur de métier de farm
            * Parcours en trois étapes
            * Tarif, objet, temps, tenue, véhicule pouvant être défini.
            * Horaire IG pour réaliser l'emploi.
        * Il est possible d'activer ou désactiver des métiers dans la configuration
        * Système de mission pour les entreprises, des bâtiments sur San Andreas sont utilisé comme des marchés professionels (ex: [Marché de Rungis](https://fr.wikipedia.org/wiki/March%C3%A9_d'int%C3%A9r%C3%AAt_national_de_Rungis)) permetant au entreprise de faire des commandes ou d'acheter aux enchéres.

    === "Activitées"
        lorem

    === "Illégal"
        lorem

    === "Autres"
        loremm

=== ":material-chat-processing: yidrp-voice"
    lorem

=== ":fontawesome-solid-computer: yidrp-mdt"
    lorem


## Les abonnements

| Type d'abonnement                                    | Mensuel                                  | Mensuel +                                | Mensuel (partenaire)                     |
| ---------------------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| Prix (TTC FR) / Mois                                 | **15** :fontawesome-solid-euro-sign:     | **25** :fontawesome-solid-euro-sign:     | :octicons-comment-discussion-24: :fontawesome-solid-euro-sign: |
| Nb d'instance possible                               | :one:                                    | :three:                                  | :octicons-comment-discussion-24:         |
| Ip Lock                                              | :material-lock-check:                    | :material-lock-check:                    | :octicons-comment-discussion-24:         |
| **Les ressources**                                   |                                          |                                          |                                          |
| :octicons-package-24: yidrp                            | :material-check-bold:                    | :material-check-bold:                    | :material-check-bold:                    |
| :material-database-sync: yidrp-db                      | :material-check-bold:                    | :material-check-bold:                    | :material-check-bold:                    |
| :material-chat-processing: yidrp-voice                 | :material-check-bold:                    | :material-check-bold:                    | :material-check-bold:                    |
| :material-chat-processing: yidrp-chat                  | :material-check-bold:                    | :material-check-bold:                    | :material-check-bold:                    |
| :fontawesome-solid-computer: yidrp-mdt                 | :octicons-circle-slash-24:               | :material-check-bold:                    | :material-check-bold:                    |
| :octicons-video-24: yidrp-loadingscr                   | :material-check-bold:                    | :material-check-bold:                    | :material-check-bold:                    |

### Condition générales d'utilisation


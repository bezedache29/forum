# forum
Création d'un forum de discussion avec Laravel 8

# Back-end

## Créer et voir les roles de users (Admin / Modo / Membre)

    - L'administrateur a tous les droits
    - Le modérateur a access a certains posts cachés, peut créer de nouveau posts, répondre a un post, modifier et supprimer ses propres posts
    - Le membre n'a pas access aux posts cachés, peut créer de nouveau posts, répondre a un post, modifier et supprimer ses propres messages
    - L'invité ne peut que lire les posts non caché

## Voir les users 

(Nom user /Avatar / Mail / nb de sujets-posts / Role / Adresse / Anniversaire / Strava / Facebook / Telephone / Sexe / Reset  pwd / Signature)

    - Modération des users

    - Voir le nb de sujets totaux

    - Voir le nb de posts totaux

    - Créer un Forum
    - Créer un sous forum

    - Modération des Forums et Sous forum (Acces lecture/ecriture)

    - Ban des IPs / Users
    - Interdire des mots / mails / noms de users
 

# Front-end

## Tous les utilisateurs on access a leur profile
### changer ses options

 - Tous les users peuvent voir le profile des autres users
 - Un user peut créer et modifier un sujets/posts
 - Un user peut répondre à un post
 - Les admins et les modos peuvent epingler des sujets
 - Les admins et les modos peuvent supprimer les sujets et posts des autres users
 - Lors des posts il sera possible d'upload des fichiers (image, pdf et gpx)
 - Lors des posts il sera possible de mettre un iframe video (Yt)
 - Lors des posts il sera possible de mettre des smileys
 - Lors des posts il sera possible de mettre des liens
 - Lors des posts il sera possible de changer la typo ect
 - Lors d'une réponse, on listera les 10 derniers messages en bas de la page
 - Voir le nb de réponses d'un sujet
 - Voir le nb de vue d'un sujet
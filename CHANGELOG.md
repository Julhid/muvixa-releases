# Journal des versions

Toutes les évolutions notables de MUVIXA. Format inspiré de [Keep a Changelog](https://keepachangelog.com/fr/1.1.0/).

## 3.26 – 2026-11-26

### Ajouté
- Hors ligne : téléchargement de films, d'épisodes ou de saisons entières, lecture sans connexion (Plus › Hors ligne).
- Reprise des téléchargements interrompus ; pause automatique pendant une lecture en ligne pour ne pas occuper la connexion de l'abonnement.

## 3.25 – 2026-11-26

### Modifié
- Films et séries rangés sur le stockage (base SQLite) au lieu de la mémoire : listes lues page par page, recherche, tris et catégories calculés par la base. La mémoire ne dépend plus de la taille des abonnements.
- Première ouverture : rangement en arrière-plan, signalé par une pastille.

## 3.24 – 2026-11-26

### Ajouté
- Sur TV, téléchargement automatique des mises à jour en arrière-plan (jamais pendant une lecture), puis installation en un clic.
- Accueil Android TV : rangées « MUVIXA · TNT » et « MUVIXA · À l'affiche », en plus des favoris et de « Continuer à regarder ».

## 3.23 – 2026-11-26

### Corrigé
- La 3.22 se fermait dès l'ouverture : une règle de tri des titres était refusée par Android.

### Ajouté
- Présentation guidée au premier lancement : langue, abonnement, appareils reliés.
- Télécommande : taper 1 à 26 ouvre la chaîne de la TNT portant ce numéro, avec aperçu du nom pendant la saisie.
- Sur TV, après un plantage, le rapport s'affiche en QR code à scanner avec le téléphone.

## 3.22 – 2026-11-26

### Ajouté
- Films et séries façon plateforme : affiche qui défile, tuiles par plateforme, rangées Box-office, Nouveautés, genres.
- Direct rangé comme une box : TNT en premier avec la numérotation officielle, puis thèmes, bouquets des opérateurs et plateformes.
- Une seule version par chaîne (la meilleure qualité, les autres en secours) et une seule fiche par film ou série, avec bascule automatique vers une autre source.
- Durée des films et des épisodes, heure de fin pendant la lecture.
- Ajout d'une source en collant simplement le lien ou le message du fournisseur.
- Son AC3, E-AC3 et DTS décodé directement (FFmpeg).

### Modifié
- Français de France seulement par défaut (réglable) : beaucoup moins de mémoire utilisée.
- Catégories d'origine du fournisseur rangées à part.

### Corrigé
- Plantages sur les TV avec plusieurs gros abonnements (manque de mémoire).
- Message clair quand une adresse est bloquée par un DNS privé ou un bloqueur de publicités.

## 3.21 – 2026-11-25

### Ajouté
- Format du direct automatique : MUVIXA mesure la fluidité et garde le meilleur entre MPEG-TS et HLS, source par source.

## 3.20 – 2026-11-25

### Modifié
- Retrait du passage automatique en HLS, qui provoquait des refus « trop de connexions » chez les abonnements à une seule connexion.
- Diagnostic plus détaillé du découpage du direct par le serveur.

## 3.19 – 2026-11-25

### Corrigé
- Chromecast : le son revient sur le direct ; la lecture sur le téléphone est vraiment coupée pendant la diffusion, puis reprend au même endroit.
- Erreur HTTP 509 : attente que le fournisseur libère la connexion au lieu de réessayer en boucle.

## 3.18 – 2026-11-25

### Corrigé
- Chromecast : première correction du son absent sur le direct.

## 3.17 – 2026-11-25

### Modifié
- Un morceau de direct renvoyé à l'identique n'est plus retéléchargé.
- Le message « le flux saccade » ne s'affiche plus qu'une fois par séance.

## 3.16 – 2026-11-25

### Corrigé
- Direct sans passages répétés quand le serveur renvoie un morceau déjà vu (recalage sur l'horloge du flux).

## 3.15 – 2026-11-25

### Corrigé
- Direct : réouverture continue quand le serveur coupe la connexion toutes les 20 secondes environ.

### Modifié
- Vérification automatique des chaînes désactivée par défaut.
- Rapport de diagnostic plus court, événements récents en premier.

## 3.14 – 2026-11-25

### Corrigé
- Reconnexion automatique quand le fournisseur coupe le flux, avec reprise au même endroit pour un film ou un épisode.

## 3.13 – 2026-11-25

### Corrigé
- Épisode suivant après une reprise depuis « Continuer ».
- Catalogues environ 25 % plus légers en mémoire.

### Ajouté
- Détail du plantage affiché au lancement suivant, et mode sans échec après plusieurs plantages.

## 3.12 – 2026-11-25

### Ajouté
- Mémoire tampon adaptative, mémorisée pour chaque chaîne.

### Modifié
- Ouverture environ 4 fois plus rapide avec les gros catalogues.

## 3.11 – 2026-11-25

### Ajouté
- « Qui regarde ? » à l'ouverture, « Sur la TV », statistiques de visionnage, enregistrements sur clé USB ou disque.

### Corrigé
- Gels toutes les 10 secondes et fermetures pendant les mises à jour, petits sauts de l'écran.

## 3.10 – 2026-11-25

### Ajouté
- Épisode suivant automatique, enchaînement des saisons, « Passer le générique ».
- Suggestions du même genre à la fin d'un film.
- Incrustation d'une deuxième chaîne, aperçu en direct, reprise d'un appareil à l'autre, « Tu regardes toujours ? ».

### Corrigé
- Plantage du bouton Chromecast, sources en double après synchronisation.

## 3.9 – 2026-11-25

### Ajouté
- Télécommande par téléphone refaite (temps réel, reste reliée).
- Liste des chaînes façon box et bandeau d'informations pendant la lecture.
- Assistant Google, suivi des séries, temps d'écran pour les profils enfants.

## 3.8 – 2026-11-25

### Ajouté
- Liste des chaînes pendant la lecture, télécommande par téléphone, différé de 30 s, enregistrements, alertes sport, code et avatar par profil.
- Chaînes hors service repérées et masquées.

## 3.7 – 2026-11-25

### Ajouté
- Catégories intelligentes (Nouveautés, Box-office, mieux notés, 4K, plateformes, genres), catégorie « Adultes » unique, catégories épinglées.
- Numéros de chaîne fixes, pause du direct, démarrage automatique avec la TV.

## 3.6 – 2026-11-25

### Corrigé
- Message « Lecture impossible » fermable, navigation TV complète, guide aligné sur l'heure, nombreuses retouches de mise en page.

## 3.5 – 2026-11-25

### Corrigé
- Plantages par manque de mémoire avec les gros catalogues, sources en double, fluidité du défilement.

## 3.4 – 2026-11-24

### Ajouté
- Contenus adultes réglables par profil, sélection des catégories par pays et langue, doublons masqués.


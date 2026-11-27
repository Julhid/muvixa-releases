# Journal des versions

Toutes les évolutions notables de MUVIXA. Format inspiré de [Keep a Changelog](https://keepachangelog.com/fr/1.1.0/).

## 3.44 – 2026-11-27

- Écran de démarrage animé aux couleurs de la bannière : le logo rebondit, « Votre TV. Vos contenus. Vos règles. », puis les icônes des appareils s'allument tour à tour pendant le chargement. Il ne rallonge jamais le chargement.
- Épisode suivant : il ne démarre plus avant la fin de l'épisode. La carte « Épisode suivant » apparaît pendant les dernières secondes (au plus 8 % de l'épisode, pratique pour les épisodes courts) et l'épisode suivant se lance à la vraie fin. Le passage anticipé ne se fait que pour une série dont tu as déjà sauté le générique avec « Lire », et avec la vraie durée du flux.
- Les génériques appris par les versions précédentes (parfois faussés) sont remis à zéro.

## 3.43 – 2026-11-27

- Logo unifié : l'en-tête, le menu latéral sur TV, l'écran de démarrage et la présentation affichent maintenant le vrai logo MUVIXA, identique à l'icône de l'appli.

## 3.42 – 2026-11-27

- Télécommande : le menu d'un épisode (OK maintenu) s'ouvre au relâchement et reste affiché (il se refermait aussitôt).
- Télécommande : les pages « À propos & soutien » et « Statistiques » défilent avec les flèches.
- Remerciements : Enzo rejoint la liste des testeurs.
- Page GitHub : fonctionnalités, questions fréquentes et captures d'écran mises à jour.

## 3.41 – 2026-11-26

- Nouvel écran « À propos & soutien » (onglet Plus) : version, soutien du projet sur Ko-fi (QR code sur TV), remerciements aux testeurs, bibliothèques utilisées.
- Épisodes à la télécommande : OK maintenu ouvre un petit menu (vu / non vu, télécharger l'épisode). Sur téléphone, l'appui long marque toujours directement vu / non vu.
- Avance rapide sur la barre de lecture plus douce en restant appuyé : un pas toutes les 0,4 s, de 10 s jusqu'à 2 min au maximum.

## 3.40 – 2026-11-26

- Barre de lecture à la télécommande : ◀ ▶ avancent de plus en plus vite (10 s, 30 s, 1 min, 2 min, 5 min) en maintenant ou en appuyant plusieurs fois. La position visée s'affiche, la lecture y saute au relâchement.
- Épisode suivant : petite carte discrète dans le coin, proposée plus tard (45 s avant la fin par défaut) pour ne plus couper la fin de l'épisode.
- Appui long sur OK à la télécommande : marque un épisode vu / non vu (et l'incrustation d'une chaîne fonctionne aussi). L'icône de téléchargement ne prend plus le focus.

## 3.39 – 2026-11-26

- Séries : les épisodes déjà vus ont une pastille verte ✓. Appui long sur un épisode pour le marquer « vu » ou « non vu ». Suit le profil sur les appareils synchronisés.
- La fiche d'une série propose le premier épisode pas encore vu.
- Historique : nouveau bouton « Effacer l'historique des chaînes » (les chaînes disparaissent aussi de « Récemment » sur l'accueil).
- Correctif : un film ou un épisode terminé pouvait réapparaître dans « Continuer » après une synchronisation.

## 3.38 – 2026-11-26

- Historique : dans Sources & réglages, deux boutons « Effacer l'historique des films » et « Effacer l'historique des séries ». Les titres en cours disparaissent aussi de « Continuer » sur l'accueil, et ne reviennent pas avec la synchronisation.

## 3.37 – 2026-11-26

- Qualité des chaînes : dans Sources & réglages › Lecture, choisis Automatique, 4K, Full HD, HD, SD ou HEVC. La TNT et toutes les chaînes en plusieurs versions suivent ce choix (HD ou SD pour l'ADSL).
- Son compatible pour VLC : nouvelle option pour les box où un film ou une série a l'image sans le son.
- Infos du flux (VLC) : chaque piste son est détaillée (nom, format, canaux), la piste en cours est marquée.

## 3.36 – 2026-11-26

- Choix du pays : sous « Source », une ligne « Pays » (Tous · 🇫🇷 France · 🇪🇸 Espagne…) dans le Direct, les Films et les Séries. Elle n'apparaît que s'il y a plusieurs pays. La France est toujours en premier.
- Noms des pays traduits dans les 8 langues.

## 3.35 – 2026-11-26

- Profils : le nom se modifie (crayon à côté de « Mon profil »).
- Bouton « Quitter MUVIXA » aussi sur téléphone, en bas de l'onglet Plus.
- Catégories : « Tout afficher » affiche aussi toutes les langues quand le filtre « Français de France » est actif (avant, rien ne changeait).
- Comptes Xtream ajoutés depuis la télécommande web : format choisi automatiquement, comme dans l'appli.
- Derniers textes non traduits (codes de profil, recherche vocale, notification de lecture…).

## 3.34 – 2026-11-26

- Avatar photo : dans Profils, touche 📷 pour choisir une photo de ta galerie. Elle est recadrée, allégée, et suit ton profil sur tes appareils synchronisés (TV comprise).

## 3.33 – 2026-11-26

- Pays et langues en plus du français : dans Plus › Catégories, toucher un pays (Espagne, Italie…) l'ajoute au français, chaînes, films et séries compris. Avant, il restait vide quand « Français de France uniquement » était actif.
- Validité de l'abonnement affichée en couleur dans Sources & réglages : date de fin et jours restants (vert, orange sous 30 jours, rouge sous 7 jours).
- Correctif : avec l'interface en espagnol, allemand, italien, portugais, néerlandais ou polonais, un compte Xtream actif pouvait être refusé à l'ajout.
- Correctif : erreurs « accès refusé » et « trop de connexions » reconnues quelle que soit la langue.

## 3.32 – 2026-11-26

- Télécommande : la présentation du premier lancement répond enfin aux flèches (le menu caché dessous gardait le focus). Le premier choix est sélectionné d'office.
- Champs de saisie : haut et bas en sortent, et le champ actif est entouré (on n'y reste plus bloqué sur les box).
- Plusieurs fournisseurs : choix de la source (Toutes, ou une seule) en haut du direct, des films et des séries.
- Bouton Quitter dans le menu, sur TV et box.
- Ajout des liens depuis un ordinateur : l'adresse du clavier distant s'affiche à côté du QR code.
- Guide TV plus rapide : sources lues en même temps, dates lues bien plus vite, chaînes inutiles ignorées.
- Page de téléchargement : sur TV et box, toujours la version armeabi-v7a.

## 3.31 – 2026-11-26

- Interface disponible en espagnol, allemand, italien, portugais, néerlandais et polonais (en plus du français et de l'anglais). La langue suit celle de l'appareil, réglable dans Sources & réglages.
- Jours et mois affichés dans la langue choisie (guide TV, statistiques, rappels).
- Widget traduit dans les 8 langues.

## 3.30 – 2026-11-26

### Ajouté
- « À regarder plus tard » : bouton sur les fiches films et séries, rangée sur l'accueil et dans Films/Séries, retrait automatique une fois vu ; synchronisé entre appareils.
- Rangées « Parce que tu as regardé… » propres à chaque profil.
- Widget pour l'écran d'accueil du téléphone : reprendre la lecture et 4 chaînes favorites.

## 3.29 – 2026-11-26

### Ajouté
- Qualité automatique du direct : bascule vers une version plus légère de la même chaîne en cas de saccades, gardée 30 minutes.
- Recherche dans le guide TV : programmes en cours et des 7 prochains jours, avec rappel ou enregistrement.
- Lecteur sur téléphone : glisser horizontalement pour avancer ou reculer, ou pour changer de chaîne en direct.

## 3.28 – 2026-11-26

### Modifié
- « Passer le générique » affiché 12 secondes seulement au début de l'épisode.
- Épisode suivant proposé dès le début du générique de fin, y compris quand la vidéo n'annonce pas sa durée ; lancement automatique après 10 s.
- Début du générique de fin appris pour chaque série quand on passe à l'épisode suivant.

## 3.27 – 2026-11-26

### Ajouté
- Interface en anglais : suit la langue de l'appareil, réglable dans Sources & réglages (Langue · Language).
- En anglais, tout le catalogue est affiché par défaut au premier lancement.

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


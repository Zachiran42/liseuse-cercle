# Liseuse Cercle

Version0.1.0 Android8+, hors ligne. Sources MIT.

Importe des EPUB, PDF et CBZ locaux, lis-les avec reprise de progression, favoris, taille de texte et thème.

EPUB : texte et chapitres, images intégrées non affichées. PDF/CBZ : lecture page par page. Fichiers sansDRM uniquement.

Recherche, formulaires, photos et pièces jointes privées, rappels si une échéance est présente, sauvegarde ZIP (non chiffrée,1Go maximum), import et export CSV. La liste affiche150résultats : affiner la recherche au-delà. Les pièces jointes restent dans le stockage privé de l’application.

Les photos prises depuis l’application sont des vignettes fournies par l’appareil photo ; importer depuis la galerie pour la qualité originale. Les rappels et minuteurs sont approximatifs selon les restrictions d’économie d’énergie Android.

## Compiler
Configurer .toolchain.json depuis le modèle (JDK21, SDKAndroid36, BuildTools36). Définir MINIGAMES_KEYSTORE_PASSWORD dans l’environnement et fournir à scripts/build.ps1 une clé externe avec -KeyStore et -KeyAlias. Ne jamais publier cette clé. APK signé de développement.

## Limites de validation
Compilation et contrôles automatisés ; aucun téléphone Android physique utilisé. Les interfaces natives, notifications, imports de fichiers et lectures multimédia demandent un essai sur appareil.

## Périmètre0.1.0
EPUB : texte et chapitres, images intégrées non affichées. PDF/CBZ : lecture page par page. Fichiers sansDRM uniquement. Les EPUB utilisant des déclarations DTD et les contenus chiffrés ne sont pas pris en charge. Une pièce jointe principale par fiche. Les sauvegardes incluent les pièces jointes jusqu’à1Go et ne restaurent pas les minuteurs déjà en cours.

## Téléchargement
[APK0.1.0](https://github.com/Zachiran42/liseuse-cercle/releases/latest/download/liseuse-cercle-0.1.0.apk) · [Page de l’application](https://zachiran42.github.io/liseuse-cercle/)

Présente dans le catalogue partagé de Cercle après publication. Ajout personnel également possible avec « Ajouter depuis GitHub » et le lien https://github.com/Zachiran42/liseuse-cercle.

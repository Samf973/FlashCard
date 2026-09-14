# Mémo Versets

Petite application web personnelle, sans serveur, pour :

- retrouver un passage de la Bible par sa référence (« Jean 3:16 », « Ps 23:1-3 », « 1 Jn 4:8 ») ;
- mémoriser des versets par répétition espacée, sous forme de cartes recto-verso.

Elle fonctionne sur téléphone et sur ordinateur, hors connexion une fois installée sur l'écran d'accueil.

## Le texte biblique n'est pas inclus

L'application ne contient aucun texte biblique. Au premier lancement, chaque utilisateur choisit son propre fichier
ePub de la Traduction du monde nouveau, téléchargé sur jw.org (Publications, Bible, format EPUB). Le fichier est lu
dans le navigateur et les versets sont conservés dans la mémoire locale de l'appareil. Rien n'est envoyé sur un serveur.

Les sauvegardes de paquets ne contiennent que des références et la progression de révision, jamais le texte.

## Fichiers

- `index.html` : toute l'application (HTML, CSS, JavaScript, sans dépendance externe).
- `manifest.webmanifest`, `sw.js`, `icon-*.png` : installation sur l'écran d'accueil et fonctionnement hors connexion.

## Installation sur un téléphone Android

Ouvrir l'adresse de la page dans Chrome, puis menu ⋮ → « Ajouter à l'écran d'accueil » (ou « Installer l'application »).

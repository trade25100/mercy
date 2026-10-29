# Mercy Tracker V3 — V1 Remastered

Site statique sans serveur, prêt pour GitHub Pages. Interface inspirée de la V1 et fonctionnalités de la V2.

## Installation
1. Crée un dépôt GitHub.
2. Place `index.html` à la racine de la branche `main`.
3. Dans Settings → Pages, sélectionne Deploy from a branch → main → /(root).
4. Attends le déploiement et ouvre l’URL Pages.

## Fonctionnalités
- Historique initial de six matchs, 1613 SR, objectif 1700 SR.
- Deux boutons Victoire / Défaite, avec saisie manuelle du changement de SR.
- Maps, notes, comparaisons, graphiques, records et objectifs.
- Galerie avec flèches à gauche et à droite et plusieurs URL HTTPS par map.
- Thème d’accent qui change selon le rang personnalisé.
- Export/import JSON et sauvegarde locale automatique.

## Conservation des données
La V3 utilise la même clé de stockage local que la V2 (`mercy-tracker-v2`) pour conserver les données sur le même domaine et le même navigateur. Exporter un JSON avant tout changement de domaine ou de navigateur.

Le modèle de SR et les seuils de rang sont personnels et ne sont pas des données officielles d’Overwatch. Les résultats ne sont pas récupérés automatiquement depuis le jeu. Les images sont des URL fournies par l’utilisateur ; aucun fichier d’image protégé n’est inclus.

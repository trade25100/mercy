# Mercy SR Tracker — GitHub Pages

Site statique en français pour suivre les matchs de Mercy : victoires, défaites, SR, rangs personnalisables, graphique, historique, sauvegarde locale, export et import JSON.

## Installation sur GitHub Pages

1. Décompressez le ZIP.
2. Créez un dépôt GitHub public, par exemple `mercy-sr-tracker`.
3. Ajoutez `index.html` à la racine du dépôt (le README est facultatif), puis validez les changements.
4. Dans le dépôt, ouvrez **Settings > Pages**.
5. Sous **Build and deployment**, choisissez **Deploy from a branch**, branche `main`, dossier `/(root)`, puis **Save**.
6. Ouvrez l'URL affichée par GitHub Pages une fois le déploiement terminé.

Le site fonctionne aussi en ouvrant `index.html` directement dans un navigateur.

## Important

- Les données initiales sont celles du PDF fourni : 1568 SR au départ, victoire +56, défaite -15, soit 1609 SR.
- Les seuils Gold 4 = 1600 et Gold 3 = 1700 sont des paramètres de suivi issus du rapport et non une affirmation sur le classement officiel actuel.
- Les résultats doivent être saisis manuellement : aucune connexion aux serveurs d'Overwatch.
- Les données sont conservées dans le navigateur (`localStorage`) : exportez régulièrement une sauvegarde JSON. Elles ne sont pas synchronisées entre appareils.

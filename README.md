# Minecraft Chest Tracker

Application web statique en français, sans serveur et utilisable gratuitement sur GitHub Pages.

## Fonctionnalités
- Plusieurs coffres avec nom, dimension et coordonnées X/Y/Z.
- Objets et quantités par coffre (ajout et mise à jour via « + Objet »).
- Recherche des coffres contenant un objet et totaux globaux.
- Checklist de 35 objets de base, cochée automatiquement à partir de l'inventaire.
- Captures d'écran facultatives servant de **référence visuelle uniquement** : **aucune reconnaissance automatique des objets ou quantités**.
- Sauvegarde automatique locale (`localStorage`), export et import JSON.

## Installation sur GitHub Pages
1. Créer un dépôt GitHub public.
2. Ajouter `index.html` à la racine du dépôt (et ce README facultativement).
3. Dans le dépôt, aller dans **Settings → Pages**.
4. Choisir **Deploy from a branch**, branche `main`, dossier `/(root)`, puis enregistrer.
5. Ouvrir l'URL GitHub Pages indiquée par GitHub après le déploiement.

## Important
Les données sont enregistrées dans le navigateur et ne se synchronisent pas entre appareils. Utiliser **Exporter JSON** régulièrement pour les sauvegarder. Les images intégrées peuvent grossir fortement le stockage local et le fichier JSON. La checklist est une liste de base personnalisable dans le code JavaScript.

## Modifier les quantités

Dans chaque coffre, utilise **+** pour ajouter un objet, **−** pour en retirer un et **✏️** pour saisir directement une quantité. Mettre la quantité à zéro supprime l’objet du coffre. Les totaux, la recherche et la checklist se mettent à jour automatiquement.

## Ajout d'objets
Dans chaque coffre, sélectionner un des 35 objets, choisir une quantité de 1 à 64, puis cliquer sur Ajouter l’objet. Un objet déjà présent est incrémenté. Les boutons −, + et ✏️ restent disponibles.
